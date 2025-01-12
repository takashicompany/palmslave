# Palmslave

# 部品

## キットに含まれているもの

|部品|個数|備考|
|:--|:--|:--|
|基板|2||
|[ダイオード(表面実装型)](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800di-02-100)|38||
|[タクトスイッチ](https://akizukidenshi.com/catalog/g/gP-08081/)|2||
|[TRRSソケット](https://shop.yushakobo.jp/products/a0800tr-01-1?_pos=1&_sid=6aacd8367&_ss=r)|2||
|[スイッチソケット Choc用](https://shop.yushakobo.jp/products/a01ps?variant=37665172553889)|38|[取り付けの向きがありますので、ご注意ください。](https://www.eisbahn.jp/yoichiro/2021/01/kailh_choc_v1_socket.html#gsc.tab=0)|
|ゴム足シール|8||
|[チップ積層セラミックコンデンサー](https://akizukidenshi.com/catalog/g/gP-02151/)|2|BLE Micro Proでの無線化の際に使用。|
|[電源スイッチ(MK12C02)](https://ja.aliexpress.com/item/32798526843.html)|2|BLE Micro Proでの無線化の際に使用。|
|[HU1632](https://www.monotaro.com/p/8835/2765/)|2|BLE Micro Proでの無線化の際に使用。|
|短いネジ(M2 6mm)|12||
|長いネジ(M2 10mm)|12||
|ナット(M2)|12||
|長いスペーサー(M2 8mm)|6||

## ご自身で用意頂くもの

### 部品

|部品|個数|備考|
|:--|:--|:--|
|[キースイッチ](https://shop.yushakobo.jp/collections/all-switches/products/pg1350)|38|Choc v1、v2に対応しています。Lofreeのキースイッチにも対応しています。|
|0.8uキーキャップ(16mm)|38|詳細は後述|
|[Pro Micro](https://talpkeyboard.net/?category_id=59e2ad48c8f22c3720001301)|2|動作確認済みのものは[こちら](https://talpkeyboard.net/items/62e24e6f8a0bd07fe2d38137)|
|[コンスルー](https://shop.yushakobo.jp/products/31)|4|12ピンのものを購入しておけばPro Micro、BLE Micro Proの両方に用いることができます。|
|[TRRSケーブル](https://shop.yushakobo.jp/products/8023)|1|有線接続の際に左右のキーボードを接続します。|

### ケース

#### アクリルケース

|部品|個数|備考|
|:--|:--|:--|
|スイッチプレート|2|2mm厚アクリルプレート。|
|側面プレート|2|2mm厚アクリルプレート。|
|ボトムプレート|2|2mm厚アクリルプレート。|
|Pro Microプレート|2|2mm厚アクリルプレート。|

#### 3Dプリントケース

|部品|個数|備考|
|:--|:--|:--|
|スイッチプレート|2|2mm厚アクリルプレート。|
|側面プレート|2|2mm厚アクリルプレート。|
|ボトムプレート|2|2mm厚アクリルプレート。|
|Pro Microプレート|2|2mm厚アクリルプレート。|

# 組み立て方

## 1. 基板の左右と表裏を確認する

基板はリバーシブル構造となっています。作業ミスを減らすためにマスキングテープなどで表面に左右が分かるように記入することを推奨します。

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_0989.jpg?raw=true" width = "600px" />

## 2. ダイオードの取り付け

ダイオードを取り付けます。ダイオードはキースイッチの入力を伝達するのに必要な機構です。基板の裏面に取り付けます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_0992.jpg?raw=true" width = "600px" />

ダイオードには向きがあります。基板に `[□ ▷|□]` と印刷された箇所に取り付けます。この時 `▷|` の縦線とダイオードの縦線が同じ側になるように配置します。
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_0993.jpg?raw=true" width = "600px" />

ダイオードを取り付ける前に、ダイオード配置箇所のハンダ付け面の片方にハンダを溶かして乗せておきます。(予備ハンダ)
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_0995.jpg?raw=true" width = "600px" />

ピンセットでダイオードを掴みながら予備ハンダを溶かしてダイオードの片側を基板とハンダ付けします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_0996.jpg?raw=true" width = "600px" />

もう一方もハンダ付けします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_0998.jpg?raw=true" width = "600px" />

基板の片側で18箇所、左右で38箇所にダイオードをハンダ付けしたら完了です。
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_0999.jpg?raw=true" width = "600px" />

## 3. キースイッチソケットの取り付け

キースイッチソケットを基板に取り付けます。キースイッチソケットはキースイッチを固定するために使用する部品です。基板の裏面に取り付けます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1002.jpg?raw=true" width = "600px" />

ダイオードと同様にハンダ付け箇所の片側に予備ハンダをします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1003.jpg?raw=true" width = "600px" />

ピンセットでキースイッチソケットを掴みながら予備ハンダを溶かしてキースイッチソケットをハンダ付けします。
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1004.jpg?raw=true" width = "600px" />

反対側もハンダ付けします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1006.jpg?raw=true" width = "600px" />

こちらダイオードと同様に片側で18箇所、左右で38箇所に取り付けます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1007.jpg?raw=true" width = "600px" />

## 4. リセットスイッチの取り付け

リセットスイッチとして、タクトスイッチを基板に取り付けます。リセットスイッチはファームウェアを書き込む際に利用します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1008.jpg?raw=true" width = "600px" />

リセットスイッチの取付箇所は基板の裏側になります。
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1009.jpg?raw=true" width = "600px" />

ダイオードやキースイッチソケットと同様に、タクトスイッチのハンダ付け箇所の1つに予備ハンダをします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1010.jpg?raw=true" width = "600px" />

ピンセットでタクトスイッチを掴みながら予備ハンダを溶かしてハンダ付けします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1011.jpg?raw=true" width = "600px" />

タクトスイッチ足4つ全てをハンダ付けします。左右の基板どちらにも取り付けてください。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1012.jpg?raw=true" width = "600px" />

## 5. Pro Microの取り付け

MCU（Micro Controller Unit）として、Pro Microを取り付けます。MCUは主にキーボードの入力をPCなどの外部デバイスに伝達します。Palmslaveは BLE Micro Proを用いた無線化に対応していますが、動作が正しくない場合のトラブルシューティングの観点から最初はPro Microによる有線接続で組み立てることを推奨します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1013.jpg?raw=true" width = "600px" />

Pro Microを基板に取り付ける際は[コンスルー](https://shop.yushakobo.jp/products/31)を使用することを強く推奨します。コンスルーを用いることでMCUが故障した歳の交換が容易になる・Pro Microを用いて組み立てた後にBLE Micro Proへの移行が容易になります。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1014.jpg?raw=true" width = "600px" />

コンスルーを基板に表側に挿します(ハンダ付けなどはしないでください）。Pro Microを指す場合は奥側(写真では右下)のBATとGNDのピン穴は空けておきます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_2083.jpg?raw=true" width = "600px" />

コンスルーにPro Microを載せます。コンスルーを載せる際には基板のピンの印字とPro Microのピンの印字が合致することを確認してください。**左手側と右手側でPro Microの表裏が異なります。** [こちらのPro Micro](https://shop.yushakobo.jp/products/pro-micro)では **左手側にはPro Microの部品が基板側になるように配置します。** **右手側はPro Microの部品が表側になるように配置します。** 以降は左手側の取り付け例となります。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_2085.jpg?raw=true" width = "600px" />

コンスルーとPro Microをハンダ付けします。Pro Microによってはハンダ付けをせずに導通できるものもあります。BLE Micro Proの場合もハンダ付けは不要です。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_2087.jpg?raw=true" width = "600px" />

右手側も同様の手順で取り付けます。先述した通り右手側はPro Microの表裏が逆になります。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_2091.jpg?raw=true" width = "600px" />

## 6. TRRSソケットの取り付け

左右のキーボードをTRRSケーブルで接続する際のTRRSソケットを取り付けます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1020.jpg?raw=true" width = "600px" />

TRRSソケットを基板の表側に載せます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1021.jpg?raw=true" width = "600px" />

基板を裏返してTRRSソケットの足が基板裏面から出ていることを確認します。4つの足が出ている状態が正しいです。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1022.jpg?raw=true" width = "600px" />

基板とTRRSソケットの足をハンダ付けします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1023.jpg?raw=true" width = "600px" />

## 7. ファームウェアの書き込み

2025/01/12時点では[miniDivide(v1)のファームウェア](https://github.com/takashicompany/minidivide?tab=readme-ov-file#6-%E3%83%95%E3%82%A1%E3%83%BC%E3%83%A0%E3%82%A6%E3%82%A7%E3%82%A2%E3%81%AE%E6%9B%B8%E3%81%8D%E8%BE%BC%E3%81%BF)をご利用ください。
書き込み手順や確認事項も同様となります。

## 9. ケースとキースイッチの取り付け

以降は左手側での組み立て説明です。右手側も手順は同様です。

### アクリルケース

以下5つの部品を用いて組み立てます。保護シートが貼られている場合は剥がしてください。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1757.jpg?raw=true" width = "600px" />

スイッチプレートをキースイッチを用いて取り付けます。基板の表側に配置します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1759.jpg?raw=true" width = "600px" />

スイッチプレートと基板をキースイッチを用いて固定します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1042.jpg?raw=true" width = "600px" />

スイッチプレートを基板の表側に載せ、キースイッチをスイッチプレートに挿します。この時キースイッチの足がスイッチソケットに入るように挿します。スイッチは4-5個程度用いて仮止めとします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1760.jpg?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1761.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />
