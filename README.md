Magic Lantern 简体中文汉化版
===========================

本仓库是 [Magic Lantern](https://github.com/reticulatedpines/magiclantern_simplified)
的简体中文汉化版本，由 LANMIN 维护。汉化修改仅保存在本仓库，不代表 Magic Lantern
原作者或官方项目。

## 汉化内容

- 汉化主菜单、子菜单、功能说明、帮助文字及模块介绍。
- 修复“最近使用”等动态菜单回退显示英文的问题。
- 中文语言包位于 `ML/data/zh_cn.bin`，翻译源文件位于
  `data/languages/zh_cn.txt`。

## 字体

中文和可显示的英文统一使用 [Fusion Pixel Font](https://github.com/TakWolf/fusion-pixel-font)
12px 简体中文字形，避免中英文混用不同字体。字体会根据 Magic Lantern 原有菜单字号
进行整数缩放，以适配不同菜单、说明文字和屏幕布局。

Fusion Pixel Font 按 SIL Open Font License 1.1 授权，许可证副本位于
[`data/fonts/FusionPixel-OFL.txt`](data/fonts/FusionPixel-OFL.txt)。

## 使用说明

请下载与相机型号及佳能固件版本完全对应的编译包，并将压缩包中的全部文件复制到存储卡。
不要混用不同机型或不同固件版本的文件。Magic Lantern 属于非官方软件，使用前请自行了解
相关风险并备份存储卡数据。

## 原项目介绍

Magic Lantern
-------------

Magic Lantern (ML) is a software enhancement that offers increased
functionality to the excellent Canon DSLR cameras.
  
It's an open framework, licensed under GPL, for developing extensions to the
official firmware.

Magic Lantern is not a *hack*, or a modified firmware, **it is an
independent program that runs alongside Canon's own software**. 
Each time you start your camera, Magic Lantern is loaded from your memory
card. Our only modification was to enable the ability to run software
from the memory card.

ML is being developed by photo and video enthusiasts, adding
functionality such as: HDR images and video, timelapse, motion
detection, focus assist tools, manual audio controls much more.

For more details on Magic Lantern please see [http://www.magiclantern.fm/](http://www.magiclantern.fm/)

There is a sibling repo for our patched version of Qemu that adds support
for emulating camera ROMs. This allows testing without access to a physical
camera, and automating tests across a suite of cameras.  
https://github.com/reticulatedpines/qemu-eos  
https://github.com/reticulatedpines/qemu-eos/tree/qemu-eos-v4.2.1 (current ML team supported branch)
