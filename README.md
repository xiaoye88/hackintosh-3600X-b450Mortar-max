# <p align="center">Hackintosh-3600X+b450Mortar-max</p> 
# <div align=center>![Github starts](https://img.shields.io/github/stars/xiaoye88/hackintosh-3600X-b450Mortar-max?style=social)![Github Fork](https://img.shields.io/github/forks/xiaoye88/hackintosh-3600X-b450Mortar-max?style=social)![watch](https://img.shields.io/github/watchers/xiaoye88/hackintosh-3600X-b450Mortar-max?style=social)![download](https://img.shields.io/github/downloads/xiaoye88/hackintosh-3600X-b450Mortar-max/total?style=social)
## &nbsp;&nbsp;&nbsp;&nbsp;更新了最新驱动，最新支持到Sonoma,英特尔无线网卡和蓝牙驱动正常，**其他功能的请自行参考进行修改。**  
### &nbsp;&nbsp;&nbsp;&nbsp;理论上支持同主板锐龙一二三代CPU,显卡驱动采用最新[NootRX](https://github.com/ChefKissInc/NootRX)，支持RDNA2系列不支持免驱的卡，如要使用免驱卡请更换[NootRX](https://github.com/ChefKissInc/NootRX)为[WhateverGreen](https://github.com/acidanthera/WhateverGreen),其余有需要修改的地方请自行尝试，尝试前请备份好EFI。
### 因为采用新显卡驱动，目前所有RDNA2系列显卡均支持硬解，请自行查看。
---
### Mac版本：Sonoma 14.3.1
### OpenCore版本：0.9.8
---  
# 如果可以请为我点个星星
## 配置清单
**类型** | 硬件配置
------------ | -------------
**主板** | B450Mortar Max
**cpu** | Ryzen5 3600X
**内存** | DDR4 8G 3200*4
**显卡** | AMD Radeon™ RX 6700 XT
**有线网卡** | Realtek RTL8111
**无线网卡** | Ax200NGW
## 功能
* 前后面版声音输出正常
* usb输出正常
* 睡眠唤醒成功
* 有线网卡驱动成功
* 无线网卡驱动成功，蓝牙正常，隔空投送和随航无法使用
* 采用AMDRyzenCPUPowerManagement，支持变频和电源功率查看
## bios设置
* windows操作系统的配置 -- CSM 改为 UEFI
* windows操作系统的配置 -- 安全引导 -- 禁止安全启动（默认禁止）
* USB设置 -- XHCI Hand-off -- 开启（默认开启）
* USB设置 -- Above 4G Decoding -- 开启
* 串行/COM 端口/并口 -- 关闭
* CPU设置 -- IOMMU -- 关闭
## 注意
**登陆Apple ID前请先使用Hackintool等工具重新生成序列号等信息，避免与他人重复**
## 效果图![效果](https://github.com/xiaoye88/hackintosh-3600X-b450Mortar-max/blob/main/Sonoma.png)
## 联系方式
* [![Telegram](https://img.shields.io/badge/Telegram-@Dialectsuds-blue.svg?style=social)](https://t.me/DialectSudr)
* [![Twitter](https://img.shields.io/twitter/url?label=Twitter&style=social&url=https%3A%2F%2Ftwitter.com%2Fxiaoxi_ye)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Ftwitter.com%2Fxiaoxi_ye)
* [![QQ](https://img.shields.io/badge/QQ-@Dialectsuds-blue.svg?style=social)](http://wpa.qq.com/msgrd?v=3&uin=1208194001&site=qq&menu=yes)
## 致谢
* [Dortania](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#starting-point)
* [黑果小兵的部落阁](https://blog.daliansky.net)
* [OS_Gen-X](https://github.com/Pavo-IM/OC-Gen-X)
