# ESP32-C3-WROOM-02 Breakout Board

## 概要

[ESP32-C3-WROOM-02](https://akizukidenshi.com/catalog/g/g117493/)を2.54mmピッチに変換するための基板です。

秋月電子の[AE-ESP-WROOM-02](https://akizukidenshi.com/catalog/g/g109715)は一部のピンがGNDに接続されているため、そのままではESP32-C3-WROOM-02に使うことはできません。[改造](https://twitter.com/k_takata/status/1746381656318157104)すれば使えなくもないですが、面倒な上にピン名も異なっていて間違えやすいため、ESP32-C3-WROOM-02用の基板を作成しました。

ESP32-C3-WROOM-02を使う上で必須のEN端子のプルアップ抵抗も基板上に実装することができるようになっています。


## 使用したソフトウェア

KiCad 7.0


## 回路図

[![schema](https://raw.githubusercontent.com/k-takata/PCB_esp32c3_breakout/master/images/schema.png)](https://raw.githubusercontent.com/k-takata/PCB_esp32c3_breakout/master/images/schema.pdf)

## 基板パターン図

![PCB pattern](https://raw.githubusercontent.com/k-takata/PCB_esp32c3_breakout/master/images/pcb-pattern.png)

4層基板になっています。

## 部品表

| Reference           |個数|値    | 説明 |
|---------------------|----|------|------|
|R1                   |   1| 10kΩ|EN端子プルアップ抵抗、2012サイズ|
|U1                   |   1|[ESP32-C3-WROOM-02-N4](https://akizukidenshi.com/catalog/g/g117493/)|Wi-Fi モジュール|
|-                    |   2|-     |[細ピンヘッダー](https://akizukidenshi.com/catalog/r/rsheader) 1x9、あるいは[丸ピンIC用連結ソケット](https://akizukidenshi.com/catalog/goods/search.aspx?search=on&goods_specification=%E7%A8%AE%E5%88%A5%EF%BC%9A%E4%B8%B8%E3%83%94%E3%83%B3%E3%83%98%E3%83%83%E3%83%80&ct=040201) 1x9|


## 完成品

T.B.D.
<!--
[![完成品](https://raw.githubusercontent.com/k-takata/PCB_esp32c3_breakout/master/images/envmeter-thumb.jpg)](https://raw.githubusercontent.com/k-takata/PCB_esp32c3_breakout/master/images/envmeter.jpg)
-->

## License

CC0
