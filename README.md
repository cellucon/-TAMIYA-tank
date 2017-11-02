とりあえず動けば良い、RCカーでなくても良いなら、以下のものあります。
私も最初はこれでした。

* タミヤ タンク工作基本セット
* 秋月電子 http://akizukidenshi.com/catalog/g/gK-09102/  ￥1,170
* ツインモーターギヤボックス
* 秋月電子 http://akizukidenshi.com/catalog/g/gK-09099/ ￥635
* 単3電池ケース　http://akizukidenshi.com/catalog/c/cum3/

DCモーターのコントロールですが、マイコンからのPWM信号をフルブリッジFETでDCモーターを動かす必要があります。私は東芝TA7291Pで作ったんですが、調べていたら以下のようなものもありました。

* ＴＢ６６１２使用　Ｄｕａｌ　ＤＣモータードライブキット
* 秋月電子 http://akizukidenshi.com/catalog/g/gK-11219/  ￥350

これ、3.3Vでも動くし、BuletoothモジュールとArduinoを3.3Vで単一電源で行ける？
いいんじゃないの？今度やってみます。

また、BLEモジュールの RN4020 http://akizukidenshi.com/catalog/g/gK-11102/ で　I2Cインターフェース内蔵のモータドライバ http://akizukidenshi.com/catalog/g/gK-06489/ でも行けそうです。
（こちらはAndroidアプリをBLE用に変更しなければですが）

参考までに　masato-ka's diary　RN4020でI2Cの値を読み取る　http://masato-ka.hatenablog.com/entry/2017/10/17/084148
