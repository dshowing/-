
>python3.6实现的跳一跳外挂，，有点意思

## 准备
### PC端（Windows10）
* python3.6环境
* Android的adb工具包
 - adb.exe
 - adb_installer
 - adb_driver

### 手机端
* 开启USB调试

## 跑脚本

保证CMD命令行下可以使用`adb`和`python`命令，否则就添加环境变量
连接手机，`adb devices`命令确保发现手机设备；
执行tyt.py脚本，测试是否能够准确的跳到中心；通过修改脚本中`press_coefficient`的值来调整跳跃距离，远了就调小，近了就调大。
