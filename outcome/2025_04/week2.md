# 本周工作（4.7 ~ 4.14）

Lichee Pi 4A![alt text](image.png)
- YOLOX 测试用例编译通过，用 cpu 运行正常
    - ![](../../assets/2025_04/picture_03.png)
    - ![](../../assets/2025_04/picture_02.jpg)
- yolov5n 测试用例编译通过，用 npu 运行未正常识别图像，正在排查问题
    - ![](../../assets/2025_04/picture_04.png)
- 发现 sipeed lichee pi 4a wiki 部分参数设置有误，导致后续编译报错，准备提 pr 修改