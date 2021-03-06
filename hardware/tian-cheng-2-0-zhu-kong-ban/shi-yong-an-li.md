# 使用案例

甜橙 2.0 主控板在案例中作为主控制器使用，使用 MicroUSB 线上传程序。在 Mixly 和 Arduino IDE 中，需要正确选取开发板类型和 COM 口才能正常上传程序。以下将介绍在 Mixly 和 ArduinoIDE 编译环境下如何选取开发板类型和COM 口。

注：

\(1\)只有通过 MicroUSB 将主控板连接到电脑之后才能在编程软件中查看并选择 COM 端口。

\(2\)主控板连接到电脑上的 USB 接口不同，对应的 COM 口也不同。

\(3如果在编程软件中有多个 COM 口而不清楚哪一个是主控板对应的 COM 口，可阅读 章节1.2.2中的（4）内容检查 COM 口。

## 1.2.1 Mixly 中选择主控板类型和 COM 口

\(1\)打开 Mixly，其编译环境如图 1.2-1 所示。

![&#x56FE; 1.2-1](../../.gitbook/assets/ying-jian-125759.png)

\(2\)在 Mixly 中选取甜橙 2.0 主控板型号为 Arduino\/Genuino Uno，如图 1.2-2 所示。

![&#x56FE;1.2-2](../../.gitbook/assets/ying-jian-125830.png)

\(3\)通过 MicroUSB 线将主控板连接到电脑的 USB 端口，在 Mixly 中选取与主控板对应的 COM 端口如图 1.2-3 所示，示例中主控板对应的端口为 COM9。

![&#x56FE;1.2-3](../../.gitbook/assets/ying-jian-125929.png)

## 1.2.2 ArduinoIDE 中选择主控板类型和 COM 口

\(1\)打开 ArduinoIDE，其编译环境如图 1.2-4 所示。

![&#x56FE; 1.2-4](../../.gitbook/assets/ying-jian-126006.png)

\(2\)在 ArduinoIDE 中选取甜橙 2.0 主控板型号为 Arduino\/Genuino Uno，如图 1.2-5。

![&#x56FE; 1.2-5](../../.gitbook/assets/ying-jian-126079.png)

\(3\)通过 MicroUSB 线将主控板连接到电脑的 USB 端口，在 ArduinoIDE 中选取与主控板对应的 COM 端口如图 1.2- 6 所示，示例中主控板对应的端口为 COM6。

![&#x56FE; 1.2-6](../../.gitbook/assets/ying-jian-126185.png)

\(4\)检查 COM 口 如果在编程软件中找不到主控板对应的 COM 口，可通过以下方法查看主控板对应的 COM 口是否正常。 选中电脑桌面的计算机图标，点击鼠标右键，在弹出列表中选择“管理”，在弹出的计算机管理窗口左侧栏中选择“设备管理器“，在窗口右侧栏打开“端口”列表，查看主控板对应的 COM 口，如图 1.2-7，图示 COM 口显示正常。

注： 如果不显示 COM 口或者 COM 口有黄色叹号则表示驱动未安装，需要安装驱动。

![&#x56FE; 1.2-7](../../.gitbook/assets/ying-jian-126416.png)

