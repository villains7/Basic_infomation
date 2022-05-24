# 基本情報技術者試験対策
## データの探索
* 線形探索法…先頭から順番に探索していく
* 番兵法…探索したいデータを配列の最後尾に追加する。（コミケの最後尾看板みたいな）
* 二分探索法…探索範囲を半分に限定しながら探索する方法
## 正規表現
文字列の集合の規則を表す記法
* . 任意の一文字を表す
* [ - ] 括弧内のいずれかに該当する文字を表す
* 「＊」　直前の文字の0回以上の繰り返しを表す
* ＋　直前の文字の1回以上の繰り返しを表す
* ｜　「or」を表す



## クライアントサーバシステム
### ストアドプロージャ
* 利用頻度の高い命令群（SQL文）をあらかじめサーバー上に用意しておくこと

### スケールアップ
* 個々のサーバーのCPUやメモリなどを増強することでシステムの性能を向上させる（自作PCみたいなイメージ？）

## トランザクション
### 共有ロックと専有ロック
* 共有…トランザクションがデータを参照する前にかけるロックのこと。共有ロック中のデータに関してほかのトランザクションから参照はできるが、更新はできない。
* 専有…トランザクションがデータを更新する前にかけるロックのこと。専有ロック中のデータに関してほかのトランザクションからは参照も更新もできない。

## IPアドレス
* DHCP Lanに接続された端末に対して、そのIPアドレスをPCの起動時などに自動設定するために用いるプロトコル


#### IPアドレスのクラス
* IPv4では２進数32ビットで表している。ホスト部とネットワーク部に分けられ、管理している。
* IPv6では128ビットで表す
