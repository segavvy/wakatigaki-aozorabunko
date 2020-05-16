# 青空文庫の分かち書き済みテキスト

[「ゼロから作るDeep Learning❷」](https://www.oreilly.co.jp/books/9784873118369/)を勉強中に、日本語で手軽に使える分かち書き済みのコーパスがあると便利かと思いましたので、[青空文庫](https://www.aozora.gr.jp/)のいくつかの作品を[MeCab](https://taku910.github.io/mecab/)で分かち書きしたものを公開します。

分かち書きはGoogle Colabで実行しました。実装の詳細はGoogleドライブで公開している[青空文庫の作品の分かち書き済みテキスト取得.ipynb](https://colab.research.google.com/drive/1nyPp_9PYkmrDOJoiJzxBvCQLzIUWDdeB?usp=sharing)をご参照ください。

# 作品とファイル名

以下、ここで公開している作品名と分かち書き済みのテキストファイル名です。
なお、青空文庫で公開されている作品の利用に当たっては作品本文以外の記載事項を削除しないことが望ましいのですが、テキストファイルに含めてしまうと利用しにくくなるため、テキストファイルには含めず以下に記載しています。

## 吾輩は猫である

ファイル名：neko.txt

```
吾輩は猫である
夏目漱石

底本：「夏目漱石全集1」ちくま文庫、筑摩書房
　　　1987（昭和62）年9月29日第1刷発行
底本の親本：「筑摩全集類聚版　夏目漱石全集　1」筑摩書房
　　　1971（昭和46）年4月5日初版
初出：「ホトトギス」
　　　1905（明治38）年1月、2月、4月、6月、7月、10月
　　　1906（明治39）年1月、3月、4月、8月
※誤植を疑った箇所を、底本の親本の表記にそって、あらためました。
入力：柴田卓治
校正：渡部峰子（一）、おのしげひこ（二、五）、田尻幹二（三）、高橋真也（四、七、八、十、十一）、しず（六）、瀬戸さえ子（九）
1999年9月17日公開
2018年2月5日修正
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## 坊ちゃん

ファイル名：bottyan.txt

```
坊っちゃん
夏目漱石

底本：「ちくま日本文学全集　夏目漱石」筑摩書房
　　　1992（平成4）年1月20日第1刷発行
底本の親本：「夏目漱石全集2」ちくま文庫、筑摩書房
　　　1987（昭和62）年10月27日第1刷発行
※底本の注にれば、本作品の原稿には、「そのうち学校もいやになった。」の後に、漱石自身による２字あけの指定があるという。このファイルでは、その情報にもとづいて、当該の箇所を２字あけとした。
※底本は、物を数える際や地名などに用いる「ヶ」（区点番号5-86）を、大振りにつくっています。
入力：真先芳秋
校正：柳沢成雄
1999年9月13日公開
2011年5月20日修正
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## こころ

ファイル名:kokoro.txt

```
こころ
夏目漱石

底本：「こころ」集英社文庫、集英社
　　　1991（平成3）年2月25日第1刷
　　　1995（平成7）年6月14日第10刷
初出：「朝日新聞」
　　　1914（大正3）年4月20日〜8月11日
※誤植の修正は「漱石全集」岩波書店を参照しました。
※底本は、物を数える際や地名などに用いる「ヶ」（区点番号5-86）を、大振りにつくっています。
入力：j.utiyama
校正：伊藤時也
1999年7月31日公開
2010年10月31日修正
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## 三四郎

ファイル名:sanshiro.txt

```
三四郎
夏目漱石

底本：「三四郎」角川文庫クラシックス、角川書店
　　　1951（昭和26）年10月20日初版発行
　　　1997（平成9）年6月10日127刷
初出：「朝日新聞」
　　　1908（明治41）年9月1日〜12月29日
入力：古村充
校正：かとうかおり
2000年7月1日公開
2014年6月19日修正
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## 草枕

ファイル名:kusamakura.txt

```
草枕
夏目漱石

底本：「夏目漱石全集3」ちくま文庫、筑摩書房
　　　1987（昭和62）年12月1日第1刷発行
底本の親本：「筑摩全集類聚版夏目漱石全集」筑摩書房
　　　1971（昭和46）年4月〜1972（昭和47）年1月
初出：「新小説」
　　　1906（明治39）年9月
入力：柴田卓治
校正：伊藤時也
1999年2月17日公開
2011年5月21日修正
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## 銀河鉄道の夜

ファイル名:gingatetsudou.txt

```
銀河鉄道の夜
宮沢賢治

底本：「銀河鉄道の夜」角川文庫、角川書店
　　　1969（昭和44）年7月20日改版初版発行
　　　1987（昭和62）年3月30日改版50版
入力：幸野素子
校正：土屋隆
2005年8月18日作成
2010年11月1日修正
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## 注文の多い料理店

ファイル名:tyuumon.txt

```
注文の多い料理店
宮沢賢治

底本：「注文の多い料理店」新潮文庫、新潮社
　　　1990（平成2）年5月25日発行
　　　1997（平成9）年5月10日17刷
初出：「イーハトヴ童話　注文の多い料理店」盛岡市杜陵出版部・東京光原社
　　　1924（大正13）年12月1日
入力：土屋隆
校正：noriko saito
2005年1月26日作成
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## セロ弾きのゴーシュ

ファイル名:serohiki.txt

```
セロ弾きのゴーシュ
宮沢賢治

底本：「新編　銀河鉄道の夜」新潮文庫、新潮社
　　　1989（平成元）年6月15日発行
　　　1994（平成6）年6月5日13刷
底本の親本：「新修宮沢賢治全集　第十二巻」筑摩書房
　　　1980（昭和55）年1月
入力：水口充、野口英司
校正：野口英司
1999年7月23日公開
2008年10月25日修正
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## 怪人二十面相

ファイル名:20mensou.txt

```
怪人二十面相
江戸川乱歩

底本：「怪人二十面相／少年探偵団」江戸川乱歩推理文庫、講談社
　　　1987（昭和62）年9月25日第1刷発行
初出：「少年倶楽部」大日本雄辯會講談社
　　　1936（昭和11）年1月号〜12月号
※底本は、物を数える際や地名などに用いる「ヶ」（区点番号5-86）を、大振りにつくっています。
入力：sogo
校正：大久保ゆう
2016年3月4日作成
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## 怪奇四十面相

ファイル名:40mensou.txt

```
怪奇四十面相
江戸川乱歩

底本：「怪奇四十面相／宇宙怪人」江戸川乱歩推理文庫、講談社
　　　1988（昭和63）年1月8日第1刷発行
初出：「少年」光文社
　　　1952（昭和27）年1月号〜12月号
入力：sogo
校正：岡山勝美
2016年3月4日作成
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## 少年探偵団

ファイル名:tannteidan.txt

```
少年探偵団
江戸川乱歩

底本：「怪人二十面相／少年探偵団」江戸川乱歩推理文庫、講談社
　　　1987（昭和62）年9月25日第1刷発行
初出：「少年倶楽部」大日本雄辯會講談社
　　　1937（昭和12）年1月号〜12月号
※「燈」と「灯」の混在は、底本通りです。
入力：sogo
校正：大久保ゆう
2016年3月4日作成
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## 青銅の魔人

ファイル名:mazin.txt

```
青銅の魔人
江戸川乱歩

底本：「妖怪博士／青銅の魔人」江戸川乱歩推理文庫、講談社
　　　1987（昭和62）年11月6日第1刷発行
初出：「少年」光文社
　　　1949（昭和24）年1月号〜12月号
※「お巡りさん」と「お巡さん」の混在は、底本通りです。
入力：sogo
校正：岡村和彦
2016年9月2日作成
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

## 宇宙怪人

ファイル名:utyuukaizin.txt

```
宇宙怪人
江戸川乱歩

底本：「怪奇四十面相／宇宙怪人」江戸川乱歩推理文庫、講談社
　　　1988（昭和63）年1月8日第1刷発行
初出：「少年」光文社
　　　1953（昭和28）年1月号〜12月号
入力：sogo
校正：大久保ゆう
2017年4月3日作成
青空文庫作成ファイル：
このファイルは、インターネットの図書館、青空文庫（http://www.aozora.gr.jp/）で作られました。入力、校正、制作にあたったのは、ボランティアの皆さんです。
```

### マージ済みテキスト

2020年5月16日時点の公開ファイルを1ファイルにマージしたものも公開します。約4.9MBです。
ファイル名:20200516merge.txt
