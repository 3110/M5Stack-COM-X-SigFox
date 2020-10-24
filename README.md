# M5Stack COM.X SigFox 拡張モジュール用プログラム

## サンプルプログラム（`sample.m5f`）

[M5Stack COM.X Sigfox の使い方](https://www.kccs-iot.jp/20200918-technical/)と同じ機能を M5Stack Core2 を使って UiFlow で実装したもの。A ボタンで`AT$SF=CAFE`を送信，B ボタンで`AT$SF=C0FFEE,1`を送信し，Ack として返ってきた RSSI と BSID を表示，C ボタンでデバイス ID と PAC 番号を表示する。

![](https://i.gyazo.com/21567c08928185e52f093b2fa405babe.png 'UiFlow画面')

変数`isM5Core2`を`false`にすれば M5Stack で動くはず。
