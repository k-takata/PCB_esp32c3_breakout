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
|J1, J2               |   2|-     |[細ピンヘッダー](https://akizukidenshi.com/catalog/r/rsheader) 1x9、あるいは[丸ピンIC用連結ソケット](https://akizukidenshi.com/catalog/goods/search.aspx?keyword=%E9%80%A3%E7%B5%90%E3%82%BD%E3%82%B1%E3%83%83%E3%83%88&ct=040201&search=%E6%A4%9C%E7%B4%A2%E3%81%99%E3%82%8B) 1x9、あるいは[リードフレーム](https://akizukidenshi.com/catalog/g/g114883/) 1x9|


## 完成品

[![完成品](https://raw.githubusercontent.com/k-takata/PCB_esp32c3_breakout/master/images/boards-thumb.jpg)](https://raw.githubusercontent.com/k-takata/PCB_esp32c3_breakout/master/images/boards.jpg)

## License

CC0
