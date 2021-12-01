# <p align="center">Hackintosh-3600X+b450Mortar-max</p> 
# <div align=center>![Github starts](https://img.shields.io/github/stars/xiaoye88/hackintosh-3600X-b450Mortar-max?style=social)![Github Fork](https://img.shields.io/github/forks/xiaoye88/hackintosh-3600X-b450Mortar-max?style=social)![watch](https://img.shields.io/github/watchers/xiaoye88/hackintosh-3600X-b450Mortar-max?style=social)![download](https://img.shields.io/github/downloads/xiaoye88/hackintosh-3600X-b450Mortar-max/total?style=social)
## &nbsp;&nbsp;&nbsp;&nbsp;自己制作的黑苹果的EFI,希望能帮到想要组黑苹果的人.EFI基于OpenCore自行修改,添加了inter无线网卡及蓝牙的驱动、OC图形化引导,**其他功能的请自行参考进行修改。**  
### &nbsp;&nbsp;&nbsp;&nbsp;修改完后请前往[OpenCore config.plist Sanity Checker](https://opencore.slowgeek.com)查看config文件是否配置正确。理论上支持同主板锐龙一二三代CPU和大部分免驱显卡免驱，请自行尝试，尝试前请自行备份EFI。
### 启用了英特尔蓝牙无线网卡驱动，不需要的请自己关闭。
### 显卡免驱，但硬件加速没法使用，正在修改中  
---
### Mac版本：bigsur 11.5.2
### OpenCore版本：0.7.5
---  
# 如果可以请为我点个星星
## 配置清单
**类型** | 硬件配置
------------ | -------------
**主板** | B450Mortar Max
**cpu** | Ryzen5 3600X
**内存** | DDR4 8G 3200*2
**显卡** | Nvidia GT 710
**有线网卡** | RTL8111
**无线网卡** | Ax200NGW
## 功能
* 前后面版声音输出正常
* usb输出正常
* 睡眠唤醒成功
* 有线网卡驱动成功
* 无线网卡驱动成功，蓝牙正常，隔空投送和随航无法使用
* 采用AMDRyzenCPUPowerManagement，支持变频和电源功率查看
## bios设置
* 高级 -- windows操作系统的配置 -- CSM 改为 UEFI
* 高级 -- windows操作系统的配置 -- 安全引导 -- 禁止安全启动（默认禁止）
* 高级 -- USB设置 -- XHCI Hand-off -- 开启（默认开启）
* 关闭bios里面的串行端口即可支持睡眠唤醒
## 注意
**登陆Apple ID前请先使用Hackintool等工具重新生成序列号等信息，避免与他人重复**
## 效果图![效果](https://github.com/xiaoye88/hackintosh-3600X-b450Mortar-max/blob/5f59e52b86b4809b25c5f0adf7bf3bb1279181e7/bigsur.png)
## 联系方式
* [![Telegram](https://img.shields.io/badge/Telegram-@Dialectsuds-blue.svg?style=social)](https://t.me/DialectSudr)
* [![Twitter](https://img.shields.io/twitter/url?label=Twitter&style=social&url=https%3A%2F%2Ftwitter.com%2Fxiaoxi_ye)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Ftwitter.com%2Fxiaoxi_ye)
* [![QQ](https://img.shields.io/badge/QQ-@Dialectsuds-blue.svg?style=social)](http://wpa.qq.com/msgrd?v=3&uin=1208194001&site=qq&menu=yes)
## 致谢
* [Dortania](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#starting-point)
* [黑果小兵的部落阁](https://blog.daliansky.net)
* [OS_Gen-X](https://github.com/Pavo-IM/OC-Gen-X)
