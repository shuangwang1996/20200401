# 20200401
操作方法及成果展示
     用Vivaodo打开\ZYBO-master\Projects\hdmi_in\proj路径下的hdmi_in.xpr文件，然后点击File->Launch SDK,在SDK中import hardware，连接HDMI线、VGA线和USB转串口线，再点击program FPGA，再下载到硬件平台，就可以运行了。
我们的设计工程完成了四个功能：

功能一：1.HDMI→ VGA视频格式转换
功能二：运行prewitt算子，实现视频边缘检测。
功能三：计时运算一帧prewitt算子时间。
功能四：NEON优化加速prewitt算子。


