HumanInterface
==============
　Android端末を用いたヒューマノイドロボットを操作するためのヒューマンインターフェースのコンポーネントです。  
  MotionLoaderと接続することにより、端末上に表示されるGUIの各ボタンに割り振られたIDを押された時に出力することができます。  

コンポーネントの仕様
----
　　　[![画像1][image1]](https://github.com/downloads/s-ryuki/Pictures/HumanInterface_Comm.png)
[image1]:https://github.com/downloads/s-ryuki/Pictures/HumanInterface_Comm.png

　InPortにはセンサモジュールを接続することにより、実装したセンサの計測値を受け取り、ユーザーの操作をサポートする機能が実装されています。
　例えば本実験では加速度センサを実装し、ロボットが転倒したら起き上がりモーションを再生するよう促される機能を実装しました。  

GUIの説明
--------
[![画像2][image2]](http://cloud.github.com/downloads/s-ryuki/Pictures/HumanInterface_GUI_Guide2.png)
[image2]:http://cloud.github.com/downloads/s-ryuki/Pictures/HumanInterface_GUI_Guide2.png

使用方法
--------
　(1)使用するAndroid端末にアプリをインストールします。  
　(2)アプリを立ち上げます。  
　(3)IPアドレス欄に接続する先のIPアドレスを入力します。  
　(4)「START」を押すと通信を開始し、PCのRTSytemEditor上にコンポーネントが表示されます。  
　(5)上記のように繋ぎ、Activateします。  
　(6)正常に接続されるとAndroid端末上に「onActivate」と表示され、使用可能となります。  
　(7)各ボタンを押すことで、ボタンに割り振られたコマンドが送られ、MotionLoderで設定されたモーションが再生されます。  
　(8)使用を終了するときは「STOP」ボタンを押せば接続が切れ、「Deactivete」と表示されます。  
