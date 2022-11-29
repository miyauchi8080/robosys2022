[![test](https://github.com/miyauchi8080/robosys2022/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/miyauchi8080/robosys2022/actions/workflows/test.yml)
# robosys2022
## 機能
* 標準入力からの数を足した数を標準出力する。

## 必要なソフトウェア
* python
* 動作確認済　3.7-3.10
* ubuntu 22.04.1 LTS

## 使用法

### 導入法
~~~
$ git clone https://github.com/miyauchi8080/robosys2022.git

$ cd robosys2022

$ chmod +x plus

$ ls -l plus
~~~
* 上記のように端末に打ち込み -rwxrwxr-x 1 と表示されることを確認。

### 例　
~~~
$ seq 5 | ./plus

15
~~~
* 上記の例は１～５までの数字を合計している。

## ライセンス

* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* © 2022 Koji Miyauchi

## 謝辞
* このソフトウェアパッケージは上田隆一氏の指導を受け制作しました。
