# 2019gsc_taizo-ueda

## 「ドローンハイウェイ」より効率的な道
2020年01月20日
青山学院大学 地球社会共生学部 地球社会共生学科
1A117022上田泰三

ゼミ論発表資料
https://docs.google.com/presentation/d/1FmUF8nuasxyPJplhDiuKgrQ1J1SR8vT0-4qp_y-FLQI/edit?usp=sharing

ゼミ論文印刷提出用
https://docs.google.com/document/d/1l8VbFMBj1spI-erAVALvcVfAaI-Tqab8B9wG4XFmQQo/edit

# 本文

## はじめに
当初私は、夢あふれるタケコプターの実現を目指していましたが、先行研究において既に実質不可能であった。だが、せっかく自腹で購入したドローンはどうしても使いたく新たにドローンと物流についてより効率的に実現するにはどうしたらいいか研究していこうと考えた。

何年か前に比べて確かにドローンは身近になった。しかし、現在ドローンは主に動画撮影のツールとして使われている。一方海外ではもう既にドローンを使った宅配の実証実験を行をれたりしている。また、日本国内においても楽天株式会社が、自身が保有するゴルフ場の敷地内において、スマホから注文したドリンクなどを指定の場所までドローンが届ける、といったサービスをすでに提供している。他にも東京電力ベンチャーズ株式会社、株式会社ゼンリン、楽天株式会社がドローンの安全飛行を支援する「ドローンハイウェイ」を活用したドローン物流の実用化を電鉄塔、送電線、変電所、電柱を使い行おうとしている。

本研究ではドローンを物流のツールとして使うためにはどうしたら良いか、どのような空路を通ってより効率的に運行できるかを研究し、1日も早く物流業界へのドローン導入を可能にすることを目指す。
***
## 研究方法
・B棟9階のビューラウンジで検証を行う。B棟9階のビューラウンジの広さは縦:横:高=6.5m:8m:4mである

・自分自身で購入したドローン(Snaptain S5C)を使用しB棟9階のビューラウンジの角から対角線上角(6.5m x 8m)にバッテリー1つ分(約10分)でA、Bと２パターン飛ばす。

Aパターン:送電線上を空路とするドローンハイウェイのように上下するように離陸直後上空4mまで上昇し、途中、中間地点で高度1mまで降下したのちに再び上空4mまで上昇させて最短距離で2つの地点を結ぶ。

Bパターン:河川の上を運行するように高度を一定の2mとし壁にそって途中直角に曲がり遠回りして対角線へ向かう。(6.5m直進し、1度直角し8m直進する)

・二つともバッテリーがなくなるまでドローンを飛ばす

・離着陸も共に行う

・今回使用するドローンの基本情報
```
重量：135g

伝送距離：最大50m

周波数：2.4Ghz

モーター：816コアレスモーター

バッテリー：3.7V/550mAh

連続作動時間：約10分

充電時間：約90分

操作モード：モード1/モード2 切り替え可能

機体サイズ：35x20x9cm
```
***
## 結果
Aパターンは5往復

Bパターン6.5往復であった。

今回の実験ではBパターンはAパターン1.3倍エネルギー効率が良い。
送電線上の「ドローンハイウェイ」よりも河川上の「ドローンハイウェイ」の方がエネルギー効率が1.3倍良いと言える。
***
## 考察
ドローンは一定の高度で走行した方が効率的であった。しかし、バッテリーは10分も持たずより容量アップしたバッテリーを搭載する必要がある。
今回の実験では室内で行い風などの影響は考えずに行った。水平移動が可能と考えられる河川や海沿いは川沿いは山から海にかけて風の通り道であり、海沿いは海面との温度差によって生じる風も考慮しなければならない。
東京電力ベンチャーズ株式会社、株式会社ゼンリン、楽天株式会社がドローンの安全飛行を支援する「ドローンハイウェイ」の利点としては高圧電線を充電ポイントとしてとして利用すれば、結果長距離運送可能である。
***
## 結論
ドローンを飛ばす上では最短距離よりも高度を一定にして飛ばした方がエネルギー効率が良い。
一方、送電線上のドローンハイウェイにもメリットがあり、電鉄塔にドローンの充電スポットを設置すれば結果長距離物を運搬することが可能である。
ドローンをA地点からB地点に飛ばすには必ず三次元地図データが必要になる。そのデータにエネルギー効率よく安全に飛ばすことができる（空港の情報、住宅密集地情報、建物や送電鉄塔、地形を三次元データ化）情報を組み込められたら実現に向かうと考えられる。
***
## 課題
①風なども考慮し、室内ではなく実際に野外で検証する必要がある。

②荷物が落下した場合の安全性の確保、顧客への補償

・人件費（ドローン1体につき操縦者が1人となると効率が悪くビジネスとしては非現実的）/自動操縦技術の向上

・ドローンの運動エネルギー、充電スポット、航空券などを踏まえて客観的にどのルート効率的にドローンを飛ばす三次元地図データの技術開発
***
## 参考文献
・SNAPTAIN S5C WiFi FPV Drone

https://snaptain.com/products/snaptain-s5c-wifi-fpv-drone

・東京電力グループ・ゼンリン・楽天、「ドローンハイウェイ」を活用したドローン物流の共同検討を開始～世界初、送電設備を安全な空の道として利用した配送の実証実験に成功～

https://www.tepcoventures.co.jp/news/2018-0712-2/

参考文献リスト：https://docs.google.com/spreadsheets/d/1vM-OsIvlGfE0kiQxPubhylJ-mlmyRSgle_Xy7tiEZZI/edit#gid=0
***
## 謝辞
本研究を進めるにあたり青山学院大学古橋研究室の古橋教授をはじめ多くの方々より多大な助言を賜りました。厚く感謝を申し上げます。
