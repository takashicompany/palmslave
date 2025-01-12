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

### 3. キースイッチソケットの取り付け

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

### 4. リセットスイッチの取り付け

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

### 5. Pro Microの取り付け

MCU（Micro Controller Unit）として、Pro Microを取り付けます。MCUは主にキーボードの入力をPCなどの外部デバイスに伝達します。Palmslaveは BLE Micro Proを用いた無線化に対応していますが、動作が正しくない場合のトラブルシューティングの観点から最初はPro Microによる有線接続で組み立てることを推奨します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1013.jpg?raw=true" width = "600px" />

Pro Microを基板に取り付ける際は[コンスルー](https://shop.yushakobo.jp/products/31)を使用することを強く推奨します。コンスルーを用いることでMCUが故障した歳の交換が容易になる・Pro Microを用いて組み立てた後にBLE Micro Proへの移行が容易になります。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1014.jpg?raw=true" width = "600px" />

コンスルーを基板に指します。
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1015.jpg?raw=true" width = "600px" />

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
