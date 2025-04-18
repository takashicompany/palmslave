# Palmslave (miniDivide v2)

Palmslave(パームスレイブ)は16mm(0.8u)の狭ピッチを採用した38キーで分割型のキーボードです。  
[miniDivide](https://github.com/takashicompany/minidivide)の後継機種となります。  
小さく薄いため持ち運びやすく、特にスマートフォンとの相性は抜群です。  
デスクの占有スペースも小さくて済むので普段遣いにも適しています。  
従来のキーボードよりキーの間隔が近いため、最小限の指の動きで文字を打鍵することが可能です。  

キースイッチはChoc v1とChoc v2に対応しています。
キースイッチソケットを採用しているため、気分や好みにあわせてキースイッチを取り替えることが可能です。
BLE Micro Proを用いることでBluetoothによる無線接続も可能です。  

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/01.jpg?raw=true" height = "200px" /><img src = "https://github.com/takashicompany/palmslave/blob/master/images/02.jpg?raw=true" height = "200px" /><img src = "https://github.com/takashicompany/palmslave/blob/master/images/03.jpg?raw=true" height = "200px" /><img src = "https://github.com/takashicompany/palmslave/blob/master/images/04.jpg?raw=true" height = "200px" /><img src = "https://github.com/takashicompany/palmslave/blob/master/images/05.jpg?raw=true" height = "200px" />

# 組み立てる前に

購入前に以降の作業工程を読みながら頭の中で組み立てるイメージをすることを推奨します。  
部品の位置関係や必要な部品を具体的にすることで、ミスを少なくすることが可能です。  
不明点などありましたら、お気軽にお問い合わせください。

# 紹介記事・動画

購入や組み立ての際に以下のページもご覧頂けますと、より理解が深まるかと思います。

- [GreenKeys : takashicompany新作「Palmslave」レビュー｜スモールデバイスに似合う左右分割無線対応キーボード](https://green-keys.info/takashicompany-palmslave-review/)
- [kazy : 狭ピッチ40%分割キーボード「Palmslave」ビルドログ](https://note.com/kazy_developer/n/n3b10e4a06097)

# 部品

## キットに含まれているもの

|部品|個数|備考|
|:--|:--|:--|
|基板|2||
|[ダイオード(表面実装型)](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800di-02-100)|38||
|[スイッチソケット Choc用](https://shop.yushakobo.jp/products/a01ps?variant=37665172553889)|38|[取り付けの向きがありますので、ご注意ください。](https://www.eisbahn.jp/yoichiro/2021/01/kailh_choc_v1_socket.html#gsc.tab=0)|
|[タクトスイッチ](https://akizukidenshi.com/catalog/g/gP-08081/)|2||
|[TRRSソケット](https://shop.yushakobo.jp/products/a0800tr-01-1?_pos=1&_sid=6aacd8367&_ss=r)|2||
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
|[Pro Micro](https://talpkeyboard.net/?category_id=59e2ad48c8f22c3720001301)|2|動作確認済みのものは[こちら](https://talpkeyboard.net/items/62e24e6f8a0bd07fe2d38137)です。高さがあるPro Micro(USB-C採用をしたものなど)はPro Microカバーと干渉してしまうことがあります。背の低いPro Microを選択するかスペーサーを長いものに取り替えるなどで対応できます。|
|[コンスルー](https://shop.yushakobo.jp/products/31)|4|12ピンのものを購入しておけばPro Micro、BLE Micro Proの両方に用いることができます。|
|[TRRSケーブル](https://shop.yushakobo.jp/products/8023)|1|有線接続の際に左右のキーボードを接続します。|

### ケース

ケースはアクリルケースと3Dプリントケースの2種類となります。

#### アクリルケース

データは[こちら](https://github.com/takashicompany/palmslave/tree/master/case/acrylic-plate)です。  
[遊舎工房の「キーボードアクリルプレート」](https://shop.yushakobo.jp/products/keyboard_acrylic_plate?variant=50646933897447)にて発注可能です。  

|部品|個数|備考|
|:--|:--|:--|
|スイッチプレート|2|2mm厚アクリルプレート。|
|側面プレート|2|2mm厚アクリルプレート。|
|ボトムプレート|2|2mm厚アクリルプレート。|
|MCUカバー(Pro Microプレート)|2|2mm厚アクリルプレート。|

#### 3Dプリントケース

データは[こちら](https://github.com/takashicompany/palmslave/tree/master/case/3d-print)です。

|部品|個数|備考|
|:--|:--|:--|
|スイッチプレート(トッププレート)|2||
|ボトムプレート|2||
|MCUカバー(Pro Microプレート)|2||

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

Pro Microにファームウェアを書き込みます。ファームウェアは[Remapから書き込む](https://remap-keys.app/catalog/9hMciuSoDHS5Mp3YbabX/firmware)ことができます。

<img src = "https://github.com/user-attachments/assets/b1b23ce1-76be-411c-ac60-f279fc0dc829" width = "600px" />

Remapでのファームウェア書き込みは[こちら](https://docs.dailycraft.jp/buildguides/firmware/remap.html)を参照すると手順が分かりやすいかと思います。

Remapの使い方は[こちら](https://salicylic-acid3.hatenablog.com/entry/remap-manual)を参照するのが分かりやすいかと思います。

Remapでダイオードとスイッチソケット、Pro Microが正しく動作するかを確認できます。USBでPCに接続しRemapを開いた後に、右下の3点リーダからTest Matrix modeを選択してください。  
<img src = "https://github.com/user-attachments/assets/bbf50785-3b81-409f-b537-e246f61435c5" width = "600px" />

金属製のピンセットなどで赤丸の箇所を通電させることで擬似的にキースイッチの入力を再現できます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1006_b.jpg?raw=true" width = "600px" />

全てのキースイッチが点灯するかを確認します。なお、ファームウェアは左手側をUSBとして接続することを前提としているので、片手側のみを接続した場合は左手側が点灯します。  
<img src = "https://github.com/user-attachments/assets/fff6db54-1183-41e4-b80f-9ce3ca1ff5d8" width = "600px" />

もし点灯しないキーがあった場合はダイオードやスイッチソケットのハンダ付けを再度行うと改善することがあるかと思います。

## 8. 無線化用の部品の取り付け

この項目は**Pro Microでの有線接続で左右のキーボードの全てのキーの入力が確認できた後に実施することを推奨**します。
無線化自体は組み立て終わった後でも実施可能ですので、後回しにしてもOKです。

チップ積層セラミックコンデンサーを取り出します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1024.jpg?raw=true" width = "600px" />

取り付け箇所は基板裏側のリセットスイッチ付近です。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1025.jpg?raw=true" width = "600px" />

ダイオードなどと同様に予備ハンダを行います。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1026.jpg?raw=true" width = "600px" />

ピンセットでコンデンサーを掴みながら予備ハンダを溶かしつつ片側をハンダ付けします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1027.jpg?raw=true" width = "600px" />

コンデンサーのもう片側もハンダ付けを行います。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1028.jpg?raw=true" width = "600px" />

電源スイッチを取り出します。取り付け箇所は基板の裏面のタクトスイッチ付近です。
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1030.jpg?raw=true" width = "600px" />

電源スイッチの足と基板のハンダ付け箇所が合うように載せます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1031.jpg?raw=true" width = "600px" />

電源スイッチの足と基板をハンダ付けします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1032.jpg?raw=true" width = "600px" />

コイン電池ホルダーを取り付けます。取り付け箇所は基板の表側のPro MicroとTRRSソケットの間です。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1033.jpg?raw=true" width = "600px" />

コイン電池ホルダーの足が基板に通るように穴を確認しながら挿します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1035.jpg?raw=true" width = "600px" />

基板の裏面からコイン電池ホルダーの足が出ていることを確認します。基板を裏返した時にコイン電池ホルダーが抜け落ちしまう場合はマスキングテープなどで固定すると作業がスムーズに進められます。赤丸の位置からコイン電池ホルダーの足が出ていることを確認できたら足と基板をハンダ付けします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1036.jpg?raw=true" width = "600px" />

コイン電池ホルダーにCR1632を入れます。Pro Microと同様にBLE Micro Proを取付けます。

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_2143.jpg?raw=true" width = "600px" />

BLE Micro Proの設定手順は[こちら](https://sekigon-gonnoc.github.io/BLE-Micro-Pro/#/getting_started?id=ble-micro-pro-web-configurator%e3%82%92%e4%bd%bf%e3%81%a3%e3%81%a6%e3%83%95%e3%82%a1%e3%83%bc%e3%83%a0%e3%82%a6%e3%82%a7%e3%82%a2%e3%82%92%e6%9b%b8%e3%81%8d%e8%be%bc%e3%82%80)を参考に進めてください。


## 9. ケースとキースイッチの取り付け

以降は左手側での組み立て説明です。右手側も手順は同様です。
アクリルケースと3Dプリントケースの2種類での組み方の説明となります。
大まかな部分の手順は同様ですので、どちらの手順も目を通しておくと理解度が高まります。

### アクリルケース

以下5つの部品を用いて組み立てます。保護シートが貼られている場合は剥がしてください。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1757.jpg?raw=true" width = "600px" />

①スイッチプレートをキースイッチを用いて取り付けます。基板の表側に配置します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1759.jpg?raw=true" width = "600px" />

スイッチプレートと基板をキースイッチを用いて固定します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1042.jpg?raw=true" width = "600px" />

スイッチプレートを基板の表側に載せ、キースイッチをスイッチプレートに挿します。この時キースイッチの足がスイッチソケットに入るように挿します。スイッチは4-5個程度用いて仮止めとします。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1760.jpg?raw=true" width = "600px" />

②ボトムプレートと⑤スペーサープレートを用意します。    
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1761.jpg?raw=true" width = "600px" />

スペーサーと短いネジを2本用意します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1763.jpg?raw=true" width = "600px" />

裏面からネジを挿してスペーサーを用いてスペーサープレートと固定します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1764.jpg?raw=true" width = "600px" />

表面からは以下の写真と同様になっていればOKです。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1765.jpg?raw=true" width = "600px" />

ボトムプレートに③積層プレートAを載せ、さらにその上に④積層プレートBを重ねます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1767.jpg?raw=true" width = "600px" />

スペーサーに加え、長いネジとナットを用います。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1768.jpg?raw=true" width = "600px" />

Pro Micro横のネジ穴は長いネジを裏面から通して表面からスペーサーで固定します。スペーサーは積層プレートAに載せる形となります。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1770.jpg?raw=true" width = "600px" />

他のネジ穴はスイッチプレートから積層プレートA & B → ボトムプレートと通します。
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1769.jpg?raw=true" width = "600px" />

裏返して、ボトムプレートから出たネジをナットで止めます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1771.jpg?raw=true" width = "600px" />

### 3Dプリントケース

スイッチプレートを用意します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1039.jpg?raw=true" width = "600px" />

スイッチプレートと基板をキースイッチで固定します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1042.jpg?raw=true" width = "600px" />

キースイッチを4-5個程度スイッチプレートに挿します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1043.jpg?raw=true" width = "600px" />

基板の上にスイッチプレートを載せ、先ほど挿したキースイッチの足が基板に取り付けたキースイッチソケットに刺さるようにはめ込みます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1044.jpg?raw=true" width = "600px" />

全てのキースイッチを取り付けます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1046.jpg?raw=true" width = "600px" />

ボトムプレートを取り出します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1047.jpg?raw=true" width = "600px" />

先程のスイッチプレート(と基板)にボトムプレートをはめ込みます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1049.jpg?raw=true" width = "600px" />

長いネジとナットを取り出します。  
<img src = "https://github.com/takashicompany/minidivide/raw/master/images/build/IMG_3739.jpg?raw=true" width = "600px" />

ネジをスイッチプレートの表面からネジ穴に挿します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1051.jpg?raw=true" width = "600px" />

裏返してボトムプレートから先ほど挿したネジをナットで留めます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1052.jpg?raw=true" width = "600px" />

短いネジとスペーサーを取り出します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1096.jpg?raw=true" width = "600px" />

ボトムプレートの赤丸の箇所に短いネジを挿します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1099.jpg?raw=true" width = "600px" />

表面から先程挿したネジをスペーサーで固定します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1100.jpg?raw=true" width = "600px" />

### Pro Microカバーの取り付け

以降はアクリルケース・3Dプリントケースのどちらも手順は共通です。  
Pro Microカバーを取り出します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1101.jpg?raw=true" width = "600px" />

スペーサーの上にPro Microカバーを載せ、短いネジで固定します。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1104.jpg?raw=true" width = "600px" />

## 10. ゴム足シールの取付け

ケースの底面に滑り止めとしてゴム足シールを貼り付けます。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1105.jpg?raw=true" width = "600px" />

打鍵スタイルにあわせてお好みの位置に貼り付けてください。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_1106.jpg?raw=true" width = "600px" />

## 11. キーキャップの取り付け

キースイッチにキーキャップを取付けて完成です。  
<img src = "https://github.com/takashicompany/palmslave/blob/master/images/06.jpg?raw=true" width = "600px" />

### 12. 完成した後の楽しみ方

完成しましたら、ぜひSNSなどに写真を投稿頂ければと思います。
Twitterのハッシュタグは [`#Palmslave #自作キーボード`](https://twitter.com/search?q=%23%E8%87%AA%E4%BD%9C%E3%82%AD%E3%83%BC%E3%83%9C%E3%83%BC%E3%83%89%20%23Palmslave&src=typed_query) を付けていただけると幸いです。
キットを組み立てた感想や、キーボードを使った所感などをお待ちしております！

また、毎週日曜日の１9時より実施されている[#KEEP_PD](https://twitter.com/hashtag/KEEB_PD?f=live)に投稿頂くこともオススメです。  
開催の告知は[@KEEB_PD](https://twitter.com/KEEB_PD)にて行われております。

ご不明な点などございましたら、[@takashicompany](https://twitter.com/takashicompany)にメンションやDM頂ければ回答できるかと思います。

<!--

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/palmslave/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

-->
