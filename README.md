#### 提醒

- 默认密码：无
- 固件包的增减基于我目前用到的设备
- 上游为 openwrt 官方，原汁原味，一些 package 取自第三方
- 内置一些 usb 无线 ac 网卡与千兆有线网卡
- 各设备内置的应用，可以查看 config 文件夹
- 如需添加其他包或设备，请 fork 后自行在如下文件中添加
    - scripts/
    - config/
- 不同版本，存储在不同的 branch，所以想自行编译的话，请 fork 所有分支
- OneCloud 有两个版本。
    - emmc 固件为直刷包，用 USB_Burning_Tool 工具刷入
    - sdcard 固件可以用 balenaEther 等工具刷入 U 盘/SD 卡，前提需要 eMMC 上已经刷入 hzyit [eMMC 底包](https://github.com/hzyitc/u-boot-onecloud/releases/download/build-20221028-0940/eMMC.burn.img)，或包含该底包的固件。
    - 启动顺序为 USB -> SD card -> eMMC

#### 感谢

- [![coolsnowwolf](https://img.shields.io/badge/Lede-Lean-orange.svg?style=flat&logo=appveyor)](https://github.com/coolsnowwolf/lede)
- [![Lienol](https://img.shields.io/badge/OpenWrt-Lienol-orange.svg?style=flat&logo=appveyor)](https://github.com/Lienol/openwrt)
- [![CTCGFW](https://img.shields.io/badge/OpenWrt-CTCGFW-orange.svg?style=flat&logo=appveyor)](https://github.com/immortalwrt/immortalwrt)
