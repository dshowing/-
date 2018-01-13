
>python3.6实现的跳一跳外挂，，有点意思

## 准备

### PC端（Windows10）

* python3.6环境
* Android的adb工具包
    * adb.exe
    * adb_installer
    * adb_driver

### 手机端

* 开启USB调试

## 跑脚本

python3.6环境下调用PIL图像识别库，需要安装：

```
C:\Users\watt>pip list
olefile (0.44)
Pillow (4.3.0)
pip (9.0.1)
setuptools (28.8.0)

C:\Users\watt>pip install Pillow
```

保证CMD命令行下可以使用`adb`和`python`命令，否则就添加环境变量
连接手机，`adb devices`命令确保发现手机设备；
执行tyt.py脚本，测试是否能够准确的跳到中心；通过修改脚本中`press_coefficient`的值来调整跳跃距离，远了就调小，近了就调大。
