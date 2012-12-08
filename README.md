HumanInterface
==============
　Android端末を用いたヒューマノイドロボットを操作するためのヒューマンインターフェースのコンポーネントです。  
  MotionLoaderと接続することにより、端末上に表示されるGUIの各ボタンに割り振られたIDを押された時に出力することができます。  
　またInPortにはセンサモジュールを接続することにより、実装したセンサの計測値を受け取り、ユーザーの操作をサポートする機能が実装されています。
　例えば本実験では加速度センサを実装し、ロボットが転倒したら起き上がりモーションを再生するよう促される機能を実装しました。  

GUIの説明
--------
[![画像1][image1]](http://cloud.github.com/downloads/s-ryuki/Pictures/HumanInterface_GUI_Guide2.png)
[image1]:http://cloud.github.com/downloads/s-ryuki/Pictures/HumanInterface_GUI_Guide2.png
