# [rt-net/RaspberryPiMouse](https://github.com/rt-net/RaspberryPiMouse) wiki

このページでは[Raspberry Pi Mouse](https://www.rt-net.jp/products/raspimouse2)に関するよくある質問やデバイスドライバの動作確認情報をまとめています。

[English Version](https://github.com/rt-net/RaspberryPiMouse/wiki/English)

## 関連ページ

* [GitHub: RaspberryPiMouse](https://github.com/rt-net/RaspberryPiMouse)
  * Raspberry Pi Mouseのデバイスドライバ
* [GitHub: RaspberryPiMouse_Hardware](https://github.com/rt-net/RaspberryPiMouse_Hardware)
  * Raspberry Piを使った左右独立二輪方式の小型移動プラットフォームロボット、Raspberry Pi Mouseのハードウェア情報
* [GitHub: raspimouse_ros](https://github.com/rt-net/ryuichiueda/raspimouse_ros)
  * Raspberry Pi Mouse用ROS1パッケージ(Python版)
* [GitHub: raspimouse_ros_2](https://github.com/ryuichiueda/raspimouse_ros_2)
  * Raspberry Pi Mouse用ROS1パッケージ(C++版)
* [GitHub: raspimouse2](https://github.com/rt-net/raspimouse2)
  * Raspberry Pi Mouse用ROS2パッケージ
* [ROS Wiki: raspimouse_ros](http://wiki.ros.org/ja/raspimouse_ros)
  * Raspberry Pi MouseのROS Wiki

## よくある質問

### `insmod`ができない

`rtmouse.ko`をビルドしたあとに、`apt upgrade`などによってカーネルのバージョンが変わると、デバイスドライバがインストールできない場合があります。  
[`utils/build_install.bash`](https://github.com/rt-net/RaspberryPiMouse/blob/master/utils/build_install.bash)を再度実行することでデバイスドライバをビルドし直すことができます。

## 動作確認情報

### 株式会社アールティにて動作確認しているOS/カーネル

### ユーザが動作確認したOS/カーネル