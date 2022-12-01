# robosys202x

これらのプログラムは授業により製作したものです。



## 内容について

・LICENCE、README.md　は著作権関係


・test.bash、.github/workflows　はテストプログラムです。


・plus.py　は足し算のプログラムです。基本的には[seq]コマンドなどをパイプで入力する様になっています。
また、入力には[sys.stdin]を使っているので、それに対応する入力のやり方であれば大丈夫です。
->入力例:seq 5 | ./plus.py


![test](https://github.com/moritaddaiki/robosys202x/actions/workflows/test.yml/badge.svg)
<-これはテストプログラムに通過しているか示すものです。


## 必要なソフトウェア
* Python
  テスト済み: 3.7～3.10

## テスト環境
* ubuntu
(作者はubuntu22.04.1 LTS を使っています。)


## このプログラムの使用方法について

１．ubuntu22.04.1 LTSを開いて任意の名前のディレクトリを作成します。ディレクトリを作成しなかった場合は現在開かれている場所にクローンしてきたリポジトリが作成されます。

２．リポジトリの[< >Code]の画面の右くらいにある緑色の[<>Code]というボタンをクリックします。

３．[clone]という文字の下に[HTTPS][SSH][GitHub CLI]と書いてある部分の[SSH]を選択して下に出てきたリポジトリパスをコピーします。

４．（１.）で作成したディレクトリで[git clone <コピーしたリポジトリパス>]を実行します。

５．コードはこれでクローン完了です。




## ライセンスについて

このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます.

詳しい内容は「LICENSE」をご確認ください。
 © 2022 Daiki Morita
