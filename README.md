# hackintosh-3600X+b450Mortar-max 

自己弄了黑苹果的EFI,希望能帮到想要组黑苹果的人.EFI基于OC_Gen_X定制,添加了inter无线网卡的驱动,OC图形化引导,**其他功能的请自行参考进行修改**。  
## 修改完后请前往**https://opencore.slowgeek.com/** 查看config文件是否配置正确。  
**显卡免驱，但硬件加速没法使用，正在修改中**。  
* Mac版本：bigsur 11.4
* opencore版本：0.7.0 
---  
# 如果可以请为我点个星星
## 配置清单
**主板** | B450Mortar Max
------------ | -------------
**cpu** | Ryzen5 3600X
**内存** | DDR4 3200*2
**显卡** | Nvidia GT 710
**网卡** | RTL8111
## 功能
* 前后面版声音输出正常
* usb输出正常
* 有线网卡驱动成功
* 睡眠唤醒成功
* 采用AMDRyzenCPUPowerManagement，支持变频和电源功率查看
## bios设置
* 高级 -- windows操作系统的配置 -- CSM 改为 UEFI
* 高级 -- windows操作系统的配置 -- 安全引导 -- 禁止安全启动（默认禁止）
* 高级 -- USB设置 -- XHCI Hand-off -- 开启（默认开启）
* 关闭bios里面的串行端口即可支持睡眠唤醒
## 注意
**登陆Apple ID前请先使用Hackintool等工具重新生成序列号等信息，避免与他人重复**
## 致谢
*[Dortania](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#starting-point)
