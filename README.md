# SeeleAssistant A script for Honkai Impact 3rd/崩坏三/崩坏3 崩坏三全自动托管项目（Hopefully）
不会代码的舟游脚本up下岗再就业了  
此脚本仍在测试阶段，维护更新正常进行  
维护已经存续时间2023.10.03（创立）-2023.10.04（最后维护）  
## 注意事项
·此Readme只是临时用于说明  
·此脚本基于Windows下python的子项目Airtest，此脚本暂时只对安卓模拟器生效（Hopefully），您需要下载安装蓝叠国际蓝叠5（Bluestacks5）Pie-64，并在其中安装崩坏3以使用此脚本，至少目前不支持windows版本直接运行此项目  
·AirtestIDE可以直接修改此脚本  
·此脚本本人由于精力有限只对蓝叠国际（蓝叠5） Pie64版本做支持，使用其他模拟器需要改main.py里的adb连接与模拟器启动位置，蓝叠模拟器启动器不管你怎么装启动器都在C盘，故可以直接使用（不用我适配了）  
·如果你使用其他模拟器，那么恭喜你，你多半要成为你自己的售后了，接售后，但不完全接
## 脚本说明
安装脚本（克隆仓库）
```
git clone -b Dev-seele https://github.com/BronOfFireUnkn/SeeleAssistantCode.git
```
·此脚本基于airtest，需要python≥3.10，最新的airtest不支持3.9及以下版本  
·安装完毕python后 
```
pip install airtest
```
在config配置文件中修改变量，运行start_android.bat即可,此脚本会自动git pull拉取更新，无需更新选择NO UPDATE即可  
·如果您想参与测试，请在AirtestIDE中（需要下载AirtestIDE）打开test_All.py即可运行
## 支持项目
### ·未通过稳定性测试
接取委托，万象虚境，日本（不是Japan），舰团，金币购买，委托接取，委托处理（马上就做），打工，日常派遣，不知道还有啥反正忘了  
### ·已通过稳定性测试
惊喜不惊喜，这里一项都没有  
## 反馈
bronoffire_unkn@petalmail.com
## 更新计划
·目前日常基本全支持，接下来更新打委托（脚本为啥只做了接委托），更新往世乐土起码到2.25（希望能办得到）  
·还有稳定性也需要校正（这需要相当长的一段时间，大约1-2周，这种一天只有一次的甚至更久）  
## 吐槽
其实你从功能上来看可以看成是HonKai Helper的重制版，只不过他好多写的不细，也好久没更新了，受不了一点，还是决定自己搓一个炸弹出来
