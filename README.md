# robosys_ros2
ロボットシステム学の課題2のリポジトリ
[![test](https://github.com/konnddo/robosys_ros2/actions/workflows/test.yml/badge.svg)](https://github.com/konnddo/robosys_ros2/actions/workflows/test.yml)

##概要
 * パブリッシャーのtalkerとサブスクライバーのlistenerの通信の様子を再現する。

##ノードとトピック
 * talker
    * 0.5秒ごとに0から1ずつカウント。
 * listener
    * メッセージを受け取り、画面に数字として表示
 * /countup
    * Int16型の変数にメッセージを格納。

##インストール方法
 * ros2がインストールされているUbuntuにクローンを作る。

##実行方法
 * 端末1$ ros2 run mypkg talker
 * 端末2$ ros2 run mypkg listener

##動作環境
 * ros2がインストールされているUbuntu

##テスト環境
 * Ubuntu 22.04

##ライセンス
 * このソフトウェアパッケージは，3条項BSDライセンスの下，再配布および使用が許可されます。
 * このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作ととしたものです。
   * [ryuichiueda/my_slides/robosys2022] [https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022]
 * ©　2023　Mei Kondo
