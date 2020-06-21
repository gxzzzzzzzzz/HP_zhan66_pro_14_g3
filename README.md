# HP_zhan66_pro_14_g3

The repository provides OpenCore configuration files for HP-zhan-66-pro-14-g3. base from https://github.com/xiaoshimu/hp-zhan-66-pro-15-g3. TKS xiaoshimu

##申明：支持正版，本项目仅限于研究技术、学习和测试，测试成功觉得适合自己，请购买苹果公司官方正品产品。

xiaoshimu是三代战66第一人（公开分享），也许还有大神也已经搞定了，但是没有分享出来，咱不知道，也用不上。
感谢乐于分享的xiaoshimu，让众多三代战66机友少走弯路。
本来想偷个懒，做伸手党，有大神搞定三代战66，我们跟着混就行了，自己折腾黑果实在是太耗精力。
但是目前看来15寸和14寸还是有一些差异，不能直接用，需要单独处理，因此单独开一个项目，整合各路大神的成果，为pro14g3的机友们节省点时间。
最大差异可能来自于USB部分，使用xiaoshimu的版本无法驱动全部USB端口，蓝牙和USB wifi网卡也无法正常工作，好在移植了一位外国友人的定制驱动，目前基本工作正常。

电脑型号：HP ZHAN 66 Pro 14 G3 笔记本电脑
操作系统：macOS Catalina 10.15.5(19F96)
处理器：英特尔 Core i5-10210U @ 1.60GHz 四核
主板：惠普 86A5 ( Intel 400 Series )
内存：8 GB ( DDR4 2666MHz ) 后增加至16G双通道
BIOS：S72 Ver. 01.05.04
硬盘：英特尔 660P SSD 512G (固态硬盘)，目前MacOS安装在加装的512G机械硬盘上用于测试。
显卡：英特尔 UHD Graphics 620
显示器：LG LGD060F 1920x1080( 14 英寸 )
声卡：英特尔 ALC236
网卡/蓝牙：英特尔 AX201
网卡：Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter


进展：
CPU：目前限定在1.6G，测试xiaoshimu的版本可以到突发4G，待整合
显卡：仿冒UHD630，工作正常
网卡：有线网卡+usb外置网卡（comfast 811ac，Realtek 8811芯片，暂时顶一下，内置WIFI有大牛在研究，貌似已经有突破进展，指日可待）
触摸板：HID支持，有时候开机触摸板失灵，关机重启后可恢复，待修复
电池：可以显示电量和充电状态
显示器亮度：曾经可以，后来搞没了，待修复
蓝牙：已支持，和触摸板一样，有时开机不工作，睡眠再唤醒后，恢复。待修复
SD卡：暂未支持，但是xiaoshimu已支持，待合并
USB端口：已定制，来自于国外友人
声卡：研究中，敬请期待，目前appleALC中ALC236的全部layout-id试用都无效，可能需要定制一个。
摄像头：已支持
睡眠：xiaoshimu已支持，USB不工作时看起来正常，USB驱动好了之后，休眠就有点不正常了，睡了秒醒，有时候睡死，只能强制关机。待修复

暂时无解：
显卡：Nvidia GeForce MX250 已屏蔽
指纹：不支持。 
