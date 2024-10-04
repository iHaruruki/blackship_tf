# BlackShip_tf

## URDFの記述手順

` $cd ~/catkin_ws/src`

` $catkin_create_pkg vis_lecture std_msgs rospy roscpp tf`

### urdf_tutrialパッケージのインストール

` $sudo apt-get install -y ros-noetic-urdf-tutorial `

### URDFファイルの作成


### URDFのチェック

` $cd catkin_ws/src/作成したpkg`

` $check_urdf |作成したファイル名|`

### URDFの表示

` $cd catkin_ws/src/作成したpkg`

` $roslaunch urdf_tutorial display.launch model:=|作成したファイル名|`
