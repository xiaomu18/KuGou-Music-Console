
# 🌈 KuGou Music Console

### KMC (Kugou Music Console) 是一个 使用 Python3 编写的 基于命令行的轻量级酷狗音乐客户端
[![Page Views Count](https://badges.toozhao.com/badges/01GPX3XTFGGV167JY4DS78CHWS/green.svg)](https://badges.toozhao.com/stats/01GPX3XTFGGV167JY4DS78CHWS "Get your own page views count badge on badges.toozhao.com")最后更新时间: 2022/12/15  |  数据库 API 保证可用  |  持续更新中...


## 🌷 特点&优点

* **API 稳定：** 调用 Web 版 Kugou API，使用稳定。
* **轻量级：** 运行时几乎不占 CPU 和内存。大小仅 10 MB (要不是该死的 python 打包我还能做的更小)
* **基于命令行：** 开发人员专属 (我相信能上 Github 的人都是碰过命令行的)
* **内置专属音乐播放器：** KMC Music Player 可在命令行模式下为您带来无损的播放质量。(甚至可播放 320K 的无损 flac)

## 🍂 功能概述

KuGouMusicConsole 目前支持以下功能：

* 从酷狗音乐平台数据库搜索歌曲
* 获取歌曲的 **详细信息(歌手，专辑，歌曲大小，时长，比特率，哈希值，歌词，封面、歌曲下载地址)**
* 使用 **内置的命令行音乐播放器(支持暂停，调整音量, 显示歌词，单曲循环)** 播放歌曲
* 动态歌词显示
* 下载歌曲

功能持续更新中 (本人学生，时间有限，更新较慢), 目前功能还未完善.

## 🌳 下载地址
在这里 [下载最新的 KuGou Music Console 构建](https://github.com/xiaomu18/KuGouMusicConsole/releases)

## 🍁系统要求

### Windows

**(Windows NT) Windows 7 or later.** [ 已在 Windows 7, 8, 10, 11 上进行测试 ]
* 不适配 Windows NT (2000, 98, 95, ME, XP) < Windows 7 的系统

本程序使用 **Windows 10 64Bit 专业版 - Python3.8.10 64Bit** 环境构建  
exe 文件由于使用 **Pyinstaller > 3.2.1** 构建可能不适配旧系统。

### Linux & Mac

暂不适配 ( 因动态歌词显示使用 Win32 API ) **后期尽量适配**

## 🌹 说在后面的话

### 开发不易，感谢支持。求个 Star 🙏🙏🙏
你们的支持，就是我开发的动力。

真的不容易，开发中途源代码所在的磁盘被病毒格式化了，后来又重新写的。😥 唉~  
命好苦啊 😭😭😭 (本来是可以恢复的，但该死的病毒给我把扇区都填充成 00 了)

### 关于不开源这件事
不是不想开源，而是怕 API 被过度滥用导致封禁
想要学习对原理有兴趣的同学可以加我 QQ，我会发源码的。
