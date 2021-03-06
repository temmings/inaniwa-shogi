# 稲庭将棋

本プログラムは、対コンピュータ戦において、時間切れ勝ちを狙う将棋プログラムです。



## 動作環境

Windows 7での動作を確認しています。



## インストール

本プログラムを使用するには、USI(Universal Shogi Interface)に対応した将棋ソフトが必要になります。代表的なソフトはこちらです。

* [将棋所](http://www.geocities.jp/shogidokoro/)
* [USI将棋](http://www.geocities.jp/shogi_depot/)
* [プチ将棋](http://www.geocities.jp/shogi_depot/)
* [ShogiGUI](https://sites.google.com/site/shogixyz/)

これらの将棋ソフトに、本プログラムをUSIエンジンとして登録すれば、使用可能となります。登録の仕方は、将棋ソフトの説明を参考にしてください。



## アンインストール

将棋ソフトにUSIエンジンとして登録している場合は、まずは将棋ソフトから登録を解除してください。登録を解除したら、「Inaniwa.exe」およびその他の同梱ファイル（後述）を削除して完了です。



## 同梱ファイル

* Inaniwa.exe
    * 稲庭将棋の本体です。これをUSIエンジンとして将棋ソフトに登録します。単体では動作しないので、ご注意ください。
* README.md
    * このファイルです。
* src/
    * ソースディレクトリです。将棋プログラムの開発者の方向けです。Microsoft Visual Studio Express 2012 for Windows Desktopでのビルドを確認しています。



## 使い方

将棋ソフトの説明を参考にしてください。



## その他

* 途中局面からの対局には対応していません（対局自体は可能ですが、期待した手を指しません）。平手の初期局面からご利用ください。
* 稲庭将棋は、第20回世界コンピュータ将棋選手権に出場しました。本プログラムは、そのときのプログラムをほぼそのままUSIに対応させたものです。



## 謝辞

本プログラムは、こちらの将棋プログラムを元に変更を加えたものです。

* [れさぴょん](http://homepage1.nifty.com/Ike/lesserpyon/)
* [Lesserkai（れさ改）](http://www.geocities.jp/shogidokoro/)

ここに感謝いたします。



## 使用条件

本プログラムは、「れさぴょん」を元に作成された「Lesserkai」に、さらに独自の変更を加えたものです。使用条件は、「れさぴょん」および「Lesserkai」に準じます。以下に、使用条件を引用します。

* 「れさぴょん」の「readme.txt」より引用

> * れさぴょんの著作権は作者（池泰弘）が保有します。
> * れさぴょんの使用によるいかなる損害に対しても、作者は責任を負いません。
> * 動作しないなどの各種の問い合わせに対して、作者は返答の義務を負いません。また、アップデートやバグ修正の義務も負いません。
> * れさぴょんの再配布は、作者の名誉を毀損することなく、商業利用が目的でない場合に限り、許可します。
> * 再配布の際に、自分で思考ルーチンを強化したり、ＧＵＩを強化したりして、バイナリとして配布することも、上記の条件に反しない限り、許可します。
> * もちろん、このソースを元に強化したプログラムで、世界コンピュータ将棋選手権など各種大会に参加することも自由です。ただし、全く思考ルーチンを改良しないで参加する事はご遠慮下さい。

* 「Lesserkai」の「お読みください.txt」より引用

> 仕様許諾条件
> 
> Lesserkaiは、池泰弘様作成の将棋ソフト「れさぴょん」を元に作成したものです。
> コマンド入出力部分は変更していますが、思考ルーチンは「れさぴょん」ほとんどそのままですので、仕様許諾条件としては「れさぴょん」に準ずるものとします。
> 詳しくは「れさぴょん」のページをご覧下さい。
> 
> http://homepage1.nifty.com/Ike/lesserpyon/



## 履歴

* 2014/09/07 1.1.0
    * GitHubにて公開
    * Visual Studio 2012に対応
    * 文字コードをUTF-8に変更
    * 他
* 2011/04/13 1.0.0
    * [Vector](http://www.vector.co.jp/soft/winnt/game/se490174.html)にて公開
