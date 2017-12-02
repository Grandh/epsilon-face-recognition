# epsilon-face-recognition
The first ARM algorithm contest of zhejiang university. This repository created by A5 epsilon team.

# Introduction
当前维护的主程序目录为：python2 

## 环境配置
### Required Environment
- python 2.7.12
- numpy
- scipy
- matplotlib   
> 上面三个库，在一般的windows或ubuntu下，直接pip install 即可   
- opencv3.2 （cv2 for python)
> 安装OpenCV3.2, 安装完成后，进入安装后的opencv\build\python路径，选择2.7文件夹，将x64文件夹下的cv2.pyd（pyd文件是一种Python动态模块，可以把他理解为C++中的dll文件），将cv2.pyd 复制到python安装目录\lib\site-packages。
在python的IDLE中   
执行   
```
import cv2
cv2.__version__
```
若输出版本号"3.20"，则OpenCV3 for python配置成功

### Test Environment
#### 摄像头调用与OpenCV环境  
- 确保笔记本自带摄像头可工作，或连接外置摄像头    
- 在./test文件夹下，运行   
```
python __init__.py 0
```
- 若输出Video窗口，显示视频流即python & OpenCV方面的环境配置成功