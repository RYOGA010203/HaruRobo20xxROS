# HaruRobo20xxROS
いつかの関東春ロボコンor関東夏ロボコンで使用したROSのプログラム群。 catkin_wsのsrcにコピペして、catkin_makeします。 初回のcatkin_makeは必ず失敗し、2回目からはビルドが成功します。 Terminalを開き「roslaunch kantoharu20_3wheel 20harurobo_shudo.launch」を入力すれば、プログラムが起動します。
roslaunchができたのにCAN通信ができないときは、USBポートに接続許可を与えるとうまくいく可能性があります。その場合はTerminalを開き「sudo chmod 777 /dev/ttyACM0」と入力。
