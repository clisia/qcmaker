## 4.5红外接收传感器
![](/assets/硬件1215099.png)

<extoc></extoc>




### 5.2.1简介

红外接收传感器是将红外线光信号变成电信号的半导体器件，可直接输出红外码。红外接收传感器带有接收信号指示灯，当接收到红外信号时，该模块的指示灯会闪烁。本传感器要配合红外信号发射装置一起使用，如：红外发射传感器或者红外遥控器。

### 5.2.2 红外接收传感器在 Mixly 中使用示例

本示例介绍红外接收传感器接收红外发射模块的使用方法和通过红外遥控器控制 LED 灯亮灭的案例。

（1）打开 Mixly，在左侧模块栏选择 通信 →ir\_item 红外接收，如图 4.5-1 所示，修改红外接收管脚为红外接收传感器连接到主控板的端口，或者直接使用主控板自带红外接收器，管脚为 12，修改后如图 4.5-2 所示。

![](/assets/硬件1215416.png)

图 4.5-1

![](/assets/硬件1215426.png)

图 4.5-2

（2）将以上程序上传到主控板，若连接红外发射传感器的主控板正常运行，则可以观察到红外接收传感器的指示灯闪烁，打开 Mixly 的串口监视器可以看到红外接收传感器接收到红外发射传感器发送的数据，如图 4.5-3 所示。

![](/assets/硬件1215545.png)


图 4.5-3

（3）按照图 4.5-4 连接程序，可以实现遥控器远程控制 LED 灯，示例使用遥控器 A 按键控制 LED 灯亮，B 按键控制LED 灯灭。示例中的判断值可以根据遥控器上按键的数值对应做改动，遥控器按键对应的数值可以利用以上示例通过串口打印查看。

![](/assets/硬件1215680.png)

图 4.5-4

（4）在 Mixly 示例程序文件中打开“红外遥控接收示例”，上传到主控板后，可通过红外遥控器控制 LED 灯的亮灭。

### 5.2.3 红外接收传感器应用场景举例

红外接收传感器可以接收红外发射传感器或者红外遥控器发出的红外信号，并且可以进行一对多遥控，该传感器常用于通过红外信号进行远程遥控的场景中。

例：红外遥控小车、红外遥控全彩 LED 灯。
