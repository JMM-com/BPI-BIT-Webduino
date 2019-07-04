
# &emsp;&emsp;&emsp;&emsp;&emsp;BPI-BIT MicroPython 固件发布主页

[![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badge/)
![](https://img.shields.io/github/release/BPI-STEAM/BPI-BIT-MicroPython.svg)
![](https://img.shields.io/github/license/BPI-STEAM/BPI-BIT-MicroPython.svg)
![](https://img.shields.io/badge/support-esp%20idf-red.svg)
![](https://img.shields.io/badge/support-smartconfig-FF00FF.svg)
![](https://img.shields.io/badge/custom-firmware-0AAAAF.svg)

## 烧写教程

[刷入 MicroPython 固件](https://bpi-steam-docs.readthedocs.io/zh_CN/latest/bpi-mpy/tutorials/flash_mpy.html)

## 基础教程

[Python 菜鸡教程](https://www.runoob.com/python3/python3-tutorial.html)

[BPI-BIT 基础文档](https://bpi-steam-docs.readthedocs.io/zh_CN/latest/bpi-mpy/tutorials/index.html)

## 相关软件

| [正式发布中心](http://bpi-steam-docs.readthedocs.io/zh_CN/latest/bpi-mpy/release.html) | 正式发布 Release 版本软件的地方。                            |
| :----------------------------------------------------------: | ------------------------------------------------------------ |
| [intellij-MicroPython](https://github.com/BPI-STEAM/BPI-BIT-MicroPython/releases/tag/pycharm) | 用于 Pycharm Mpfshell 的插件，还未并入官方主仓。             |
| [vscoe-mpfshell](https://github.com/junhuanchen/vscode-mpfshell) | 用于 VsCode Mpfshell 的插件，可在 VSCODE 中直接得到。        |
| [EspTouch](https://github.com/EspressifApp/EspRelease/tree/master/EspTouch) | 用于 esp32 的 Smartconfig 辅助 WIFI 配网 APK 软件            |
|   [MobaxTerm](https://mobaxterm.mobatek.net/download.html)   | 免费绿色版的超级终端，支持大量远端连接，常用 Serial 和 FTP。 |
| [BleTool](https://github.com/BPI-STEAM/BPI-BIT-MicroPython/releases/tag/BleTool) | 提供 MicroPython 蓝牙示例代码 和 安卓主机蓝牙调试工具。      |

## 固件源码

[BPI-STEAM/micropython](https://github.com/BPI-STEAM/micropython)

## CHANGELOG

### 20190528 第一个版本

- 网络层各种加持，mdns、smartconfig、XSocket、Mqtt 等等内置。
- 兼任 microbit 接口函数。
- 内置了一些常用模块代码。
