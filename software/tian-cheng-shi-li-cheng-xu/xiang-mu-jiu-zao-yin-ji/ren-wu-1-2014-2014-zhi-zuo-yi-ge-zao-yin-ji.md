### 任务1——制作一个噪音计

#### 1、任务目标

根据模拟声音传感器检测到的噪音的大小，控制舵机转动到不同的角度。

#### 2、流程图

![img](/assets/image320.jpg)

图3.9-2

#### 3、程序编程

![img](/assets/image322.jpg)

图3.9-3

#### 4、硬件连接

硬件连接： 舵机——9；模拟声音传感器——A0。注意插线时的颜色对应。

![img](/assets/image324.jpg)

图3.9-4

#### 5、Q&A

Q：无论怎么调节噪声，舵机都没有转动到180度位置？

A：查看程序中是否正确使用了“约束”程序块，二看延时的时间，是否太小，因为舵机的转动需要一定时间。

#### 6、拓展

1、知识点总结

1）“舵机”程序块；

2）“映射”与“模拟输入”程序块的结合；

2、相关案例

1）本项目任务2；