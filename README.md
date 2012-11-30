HumanInterface
==============
　Android端末を用いたヒューマノイドロボットを操作するためのヒューマンインターフェースのコンポーネントです。  
MotionLoaderと接続することにより、端末上に表示されるGUIの各ボタンに割り振られたIDやアナログ量などを送ることができます。  
　またInPortにはセンサモジュールを接続することにより、実装したセンサの計測値を受け取り、ユーザーの操作を  
サポートする機能が実装されています。例えば本実験では加速度センサを実装し、ロボットが転倒したら起き上がりモーションを  
再生するボタンの色が変わるという機能を実装しました。  

GUIの説明
--------
![画像1][image1](http://cloud.github.com/downloads/s-ryuki/Pictures/HumanInterface_GUI_Guide.png)
[image1]:http://cloud.github.com/downloads/s-ryuki/Pictures/HumanInterface_GUI_Guide.png