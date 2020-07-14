# HP_zhan66_pro_14_g3<br>
<br>
<br>
The repository provides OpenCore configuration files for HP-zhan-66-pro-14-g3. base from https://github.com/xiaoshimu/hp-zhan-66-pro-15-g3. TKS xiaoshimu<br>
<br>

**申明：支持正版，本项目仅限于研究技术、学习和测试，测试成功觉得适合自己，请购买苹果公司官方正品产品。**


xiaoshimu是三代战66第一人（公开分享），也许还有大神也已经搞定了，但是没有分享出来，咱不知道，也用不上。<br>
感谢乐于分享的xiaoshimu，让众多三代战66机友少走弯路。<br>
<br>

---

电脑型号：HP ZHAN 66 Pro 14 G3 笔记本电脑<br>
操作系统：macOS Catalina 10.15.5(19F96)<br>
处理器：英特尔 Core i5-10210U @ 1.60GHz 四核<br>
主板：惠普 86A5 ( Intel 400 Series )<br>
内存：8 GB ( DDR4 2666MHz ) 后增加至16G双通道<br>
BIOS：S72 Ver. 01.05.04<br>
硬盘：英特尔 660P SSD 512G (固态硬盘)，目前MacOS安装在加装的512G机械硬盘上用于测试。<br>
显卡：英特尔 UHD Graphics 620<br>
显示器：LG LGD060F 1920x1080( 14 英寸 )<br>
声卡：英特尔 ALC236<br>
无线网卡/蓝牙：英特尔 AX201<br>
有线网卡：Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter<br>
<br>

**提醒：请不要直接使用配置文件里的三码登录正常的appleID，建议自行算号并验证后使用。**

**初次使用，建议重建一下缓存，否则触摸板或蓝牙可能会不工作，如果一切正常就不需要了**

---

**暂时无解：**

显卡：Nvidia GeForce MX250 已屏蔽<br>
指纹：不支持。 <br>
内置MIC：无法使用。<br>
<br>

---

**2020-07-13更新(完成度70%)：**

提供OC和Clover 两种启动模式，请根据喜好选用。OC引导更快速，未来的发展方向，但对新手不够友好；Clover调试起来相对比较方便。

CPU：已睿频，可以短时间突发到4G（功耗20+W），长时间稳定运行在3.3G附近（功耗10W左右，与环境温度有关）<br>
显卡：仿冒UHD630，工作正常<br>
网卡：有线网卡+usb外置网卡（comfast 811ac，Realtek 8811芯片，暂时顶一下，内置WIFI有大牛在研究，貌似已经有突破进展，指日可待）<br>
触摸板：HID支持，99%正常，偶有开机触摸失灵，重启后可恢复<br>
电池：可以显示电量和充电状态<br>
显示器亮度：使用fn+F3/F4调整亮度（偶尔无反应时，试试不按fn）<br>
蓝牙：已支持，80%情况OK，个别时候没驱动起来，需要重启（反复重启不能恢复的时候，试试冷开机到windows再重启进mac）<br>
SD卡：不完善支持，一般SD卡OK，不要尝试用卡套转接的tf卡，会直接掉电死机<br>
USB端口：支持全部内置和外置端口，暂时未发现异常<br>
声卡：除内置MIC外，工作正常，使用layout-id 11，内置喇叭和耳机自动切换。系统默认选择内置MIC，外接带MIC的耳机时，请手动选择外置MIC为录音设备<br>
摄像头：已支持，工作正常<br>
睡眠：睡眠和唤醒正常，使用 sudo pmset -a standby 0 powernap 0 hibernatemode 0 避免睡眠中被意外唤醒<br>
<br>

---

**2020-06-22更新(完成度30%)：**

CPU：目前限定在1.6G，测试xiaoshimu的版本可以到突发4G，待整合<br>
显卡：仿冒UHD630，工作正常<br>
网卡：有线网卡+usb外置网卡（comfast 811ac，Realtek 8811芯片，暂时顶一下，内置WIFI有大牛在研究，貌似已经有突破进展，指日可待）<br>
触摸板：HID支持，有时候开机触摸板失灵，关机重启后可恢复，待修复<br>
电池：可以显示电量和充电状态<br>
显示器亮度：曾经可以，后来搞没了，待修复<br>
蓝牙：已支持，和触摸板一样，有时开机不工作，睡眠再唤醒后，恢复。待修复<br>
SD卡：暂未支持，但是xiaoshimu已支持，待合并<br>
USB端口：已定制，来自于国外友人<br>
声卡：研究中，敬请期待，目前appleALC中ALC236的全部layout-id试用都无效，可能需要定制一个。<br>
摄像头：已支持<br>
睡眠：xiaoshimu已支持，USB不工作时看起来正常，USB驱动好了之后，休眠就有点不正常了，睡了秒醒，有时候睡死，只能强制关机。待修复<br>
<br>

