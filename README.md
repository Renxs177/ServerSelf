# ServerSelf

夸克迷你开发者套件Atom-N可能是市面上最小的Linux卡片电脑, 本套件包含一个搭载四核CPU的高度集成SOM核心板，以及一个多功能IO扩展底板，可以在40mm x 35mm的尺寸上运行Linux系统, 并具备出色的扩展功能。您可以将它用于搭建个人服务器、开发智能语音助手、设计机器人等场景。
开发板的核心是一块名为Quark-N的SOM核心板，它基于Allwinner H3, 架构为四核Cortex-A7 CPU + Mali400 MP2 GPU，PCBA使用6层高密度沉金PCB工艺制造，集成了完整的片上ARM-Linux系统（包含CPU、DDR、eMMC），核心板尺寸只有惊人的2x3cm！
此外，H3上的绝大多数GPIO都通过M.2 Key-A金手指接口引出了，以最小化底板的设计难度。Atom-N的底板原理图和PCB文件完全开源，且提供核心板的PCB库，您可以轻松地设计两层板PCB作为底板，以实现您的有趣想法。
由于核心板Quark-N上已经包含了eMMC，因此底板的设计甚至可以不考虑SD卡，理论上只要在底板上提供电源，添加一个用于终端交互的串口，就能完整地运行调试系统了！
本开发套件的底板名为 Atom-N，通过M.2接口连接Quark-N。
Atom-N上扩展搭载了麦克风、MPU6050 IMU（加速度计和陀螺仪）、板载4个按键、1.35寸的IPS显示屏、Wi-Fi/蓝牙模块、喇叭功放、两个USB-A接口、以及2.0mm排针的额外GPIO（包含I2C、SPI、UART等）。
您可以基于Atom-N方便地进行项目原型验证，然后设计自己的底板用于实际项目。
reference：https://wiki.seeedstudio.com/cn/Quantum-Mini-Linux-Development-Kit
