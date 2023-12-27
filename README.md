# robosys2023_ros2
[![test](https://github.com/konnddo/robosys_ros2/actions/workflows/test.yml/badge.svg)](https://github.com/konnddo/robosys_ros2/actions/workflows/test.yml)

ロボットシステム学、課題2のリポジトリ

## ノードとトピック
 * talker
    * 0.5秒ごとに0から1ずつカウント。
 * listener
    * メッセージを受け取り、画面に数字として表示
 * /countup
    * Int16型の変数にメッセージを格納。

## 実行方法
 * 端末1
```
ros2 run mypkg talker
```
 * 端末2
```
ros2 run mypkg listener
```

## 実行結果
```
[INFO] [Listener]: Listen: 142
[INFO] [Listener]: Listen: 143
・・・
```

## 動作環境
 * Ubuntu22.04 LTS
 * ROS2

## テスト環境
 * Ubuntu 22.04

## ライセンス
 * このソフトウェアパッケージは，3条項BSDライセンスの下，再配布および使用が許可されます。
 * このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作ととしたものです。
   * [ryuichiueda/my_slides/robosys2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
 * ©　2023　Mei Kondo
