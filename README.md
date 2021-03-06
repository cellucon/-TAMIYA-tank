#セルコンがとりあえず動けば良い人用
大きなRCカーでなくても良いなら、以下のものあります。
私も最初はこれでした。

タミヤ タンク工作基本セット
* 秋月電子 http://akizukidenshi.com/catalog/g/gK-09102/  ￥1,170

ツインモーターギヤボックス
* 秋月電子 http://akizukidenshi.com/catalog/g/gK-09099/ ￥635

単3電池ケース
* 秋月電子 http://akizukidenshi.com/catalog/c/cum3/

DCモーターのコントロールですが、マイコンからのPWM信号をフルブリッジFETでDCモーターを動かす必要があります。

私は東芝TA7291Pで基板を作ったんですが、調べていたら以下のようなものもありました。

* ＴＢ６６１２使用　Ｄｕａｌ　ＤＣモータードライブキット
* 秋月電子 http://akizukidenshi.com/catalog/g/gK-11219/  ￥350

これ、3.3Vでも動くし、BuletoothモジュールとArduinoを3.3Vで単一電源で行ける？
いいんじゃないの？今度やってみます。

また、BLEモジュールの RN4020 http://akizukidenshi.com/catalog/g/gK-11102/ で　I2Cインターフェース内蔵のモータドライバ http://akizukidenshi.com/catalog/g/gK-06489/ でも行けそうです。
（こちらはAndroidアプリをBLE用に変更しなければですが）

参考までに　masato-ka's diary　RN4020でI2Cの値を読み取る　http://masato-ka.hatenablog.com/entry/2017/10/17/084148


## Licenses and Credits ライセンスとクレジット

### Arduinoのハードウエアのライセンスは、[Creative Commons](https://creativecommons.jp/licenses/) Attribution Share-Alike license(CC-BY-SA)です。

つまり、

* 著作権者のクレジット表記義務(BY)：原著作権者のクレジットを明記しなければいけません。
* 同一条件の継承義務(SA)：作品を改変・変形または加工した場合、その制作品をこの作品と同一の許諾条件でのみ、頒布することができます。

## Arduino Credits
https://www.arduino.cc/en/Main/Credits

Arduino is an open-source project founded by Massimo Banzi, David Cuartielles, Tom Igoe, Gianluca Martino, and David Mellis. It builds on the work of many people, projects, and institutions. This page attempts to summarize those contributions.

![image](https://cdn.arduino.cc/homepage/images/what_is-board.png)

Arduinoのハードウエアのライセンスより同一条件の継承義務(SA)です。

### Creative Commons License CC-BY-SA
<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.ja"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />
このハードウェアは <a rel="license" href="https://creativecommons.org/licenses/by/4.0/legalcode.ja">クリエイティブ・コモンズ 表示 - 継承 4.0 国際 ライセンス</a>の下に提供されています。

以下は許可されます。
* 非営利の場合のみ使用許可(NC)はありません：この作品を営利目的で利用してもいいです。
* 改変の禁止(ND)はありません：作品を改変・変形または加工してもいいです。
