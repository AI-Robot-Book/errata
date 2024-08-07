# 正誤表
- すみません．訂正がありますm(_ _ )m．

更新日：2024-7-25

## 未対応
|    正誤箇所     |                誤                 |　             正                |  
| :-----------:  | :-------------------------------- |:--------------------------------|
||||

## 第5刷で対応
|    正誤箇所     |                誤                 |　             正                |  
| :-----------:  | :-------------------------------- |:--------------------------------|
| p.192 上から5行目 |`colcon build --packages-select simple_arm_discription`|`colcon build --packages-select simple_arm_description`|
| p.217 上から1行目 | 形状データを読み込み． | 形状データの読み込み． |
| p.251 プログラムリスト33行目 | self.happy_action[no]| self.happy_actions[no]|
| p.264 上から10行目 | aRb逆行列をかけて | aRbの逆行列をかけて |
| p.289 上から2行目 | 紫色と黄色の動く矢印 | 紫色と黄色の動く球 |

## 第4刷で対応
|    正誤箇所     |                誤                 |　             正                |  
| :-----------:  | :-------------------------------- |:--------------------------------|
| p.67 1行目 | ● ビルド： | ● ビルド：次のコマンドでビルドします． |
| p.67 10行目に追加 |  | ● サービスノードとクライアントノードの作成 (改行) サービスノード`bringme_service_node.py`とクライアントノード`bringme_client_node.py`のプログラムを作成します． |
| p.83 上から14行目 |Google Cloud Speech API|Google Speech Recognition| 
| p.91 上から6行目 |Google Cloud Speech API|Google Speech Recognition| 
| p.101 下から6行目 | ● 外界センサを使う4手法| ● 外界センサを使う3手法|
| p.101 下から5行目 | 4手法| 3手法|
| p.101 下から2行目 | 3 距離と方位を使う方法| この行を全部削除|
| p.101 下から1行目 | 4 形状を使う方法| 3 形状を使う方法|
| p.114 チャレンジ4.2 | move_time(self, time)| move_time(self, time, linear_vel, angular_vel)|

## 第3刷で対応
|    正誤箇所     |                誤                 |　             正                |  
| :-----------:  | :-------------------------------- |:--------------------------------|
| p.47 プログラムリスト2.1 4行 | `<name>happy</name>` | `<name>hello</name>` |
| p.47 7, 8行 | `happy_node` | `hello_node` |
| p.47 8行 | happyパッケージ | helloパッケージ |
| p.47 プログラムリスト2.2 3行 | `happy` | `hello` |
| p.47 プログラムリスト2.2 24行 | `happy_node = happy.happy_node:main` | `hello_node = hello.hello_node:main` |
| p.81 下から1行目 |Google Cloud Speech API|Google Speech Recognition|  
| p.83 下から5行目 |Google Cloud Speech API|Google Speech Recognition|  
| p.84 上上ら2行目 |Google Cloud Speech API|Google Speech Recognition|  
| p.86 上から3行目 |音声を計コンピュータなどにより…|音声をコンピュータなどにより…|  
| p.94 下から4行目 |Google Cloud Speech API|Google Speech Recognition|  
| p.98 式(4.1) |sin &theta; | cos &theta; |  
| p.98 式(4.2) |cos &theta; | sin &theta; |  
| p.103 上から5行目 | ● 角度を使う方法| ● 方位を使う方法|
| p.103 図4.5 キャプション | 図4.5 角度を使った自己位置推定| 図4.5 方位を使った自己位置推定|
| p.107 式(4.31) |sin &theta; | cos &theta; |  
| p.107 式(4.32) |cos &theta; | sin &theta; |   
| p.192 上から5行目 |`colcon build --packages-select simple_arm`|`colcon build --packages-select simple_arm_description`|
| p.209 上から17行目 | `colcon build` | `colcon build --packages-select crane_plus_commander` |
| p.219 上から12行目 | 静的な座標を | 静的な座標系を |
| p.220 下から4行目 |`rviz2 -d install/crane_plus_description/share/crane_plus_description/launch/display.rviz`|`rviz2 -d ~/airobot_ws/install/crane_plus_description/share/crane_plus_description/launch/display.rviz `|

## 第2刷で対応
|    正誤箇所     |                誤                 |　             正                |  
| :-----------:  | :-------------------------------- |:--------------------------------|
| p.2  下から4行目|カレル・チャペット　　　 　 　　      |カレル・チャペック    　           | 
| p.30 表2.1 トピックの行|データに伝送経路　　 　　      |データの伝送経路　　　　           | 
| p.36 上から3行目|次節からHappy Mini　　　　 　　      |4.3.3節からHappy Mini　           | 
| p.66　プログラムリスト 2.16 2行目 | `2   <member_of_group>rosidl_default_generators</memberof_group>`|`2   <exec_depend>rosidl_default_runtime</exec_depend>`</br>`3   <member_of_group>rosidl_interface_packages</member_of_group>` | 
| p.154 上から7行目 |`pip3 install opencv-contrib-python`|`pip3 install opencv-contrib-python==4.5.5.64`|
| p.154 下から10行目 |`git clone https://github.com/ultralytics/yolov5`|`git clone -b v6.2 https://github.com/ultralytics/yolov5`|
