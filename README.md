# K3NG CW keyerの作成
## はじめに
K3NG CW keyerはArduinoをベースとした多機能キーヤです。
すでにたくさんの方が作成され作成が公開されていますが、今回作りやすさに重点を置き新たに作成しました。

## 主な特徴
- CPUボードは、小型のSeeed社のXIAO（SAM D21 Cortex M0+ MCU 48MHz)を使用してコンパクト化
- ディスプレィは視野性の高い0.96inchのOLEDを採用
- 4つのメモリボタンとコマンドボタンをサポート
- パドルとストレートキーを同時に接続可能
- CW DECODERを有効化

## ハードウェア
### 回路図
CPUにSeeedのXIAOを使用している以外は特別な回路はありません。
パドル、ストレートキー、受信入力、受信出力、送信出力はそれぞれ3.5mmのPhone Jackを接続してあります。

![](img/2023-01-15-00-32-20.png)

### PCB
PCBは作りやすさを考慮して9cm☓7cmのサイズとし、スルーホール部品を使用しています。
![](img/2023-01-15-00-34-35.png)


### 外観
ついでにアクリル板で光るパドルを作ってみました。
![](img/2023-02-18-09-33-14.png)

## 謝辞
素晴らしいソフトウェアを提供していただいたK3NGに感謝します。　

https://github.com/k3ng/k3ng_cw_keyer
