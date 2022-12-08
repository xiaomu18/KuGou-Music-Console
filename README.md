
# KuGou Music Console

KuGou Music Console 是一个 使用Python编写的 基于命令行的轻量级酷狗音乐客户端

## 特点&优点

* API 稳定: 调用 Web 版 Kugou API，使用稳定。
* 轻量级: 运行时几乎不占 CPU 和内存。程序仅 10 MB (要不是该死的 python 打包我还能做的更小)
* 基于命令行: 开发人员专属 (我相信能上 Github 的人都是碰过命令行的)

## 功能概述

KuGouMusicConsole 目前支持以下功能：

* 从酷狗音乐平台数据库搜索歌曲
* 获取歌曲的详细信息、下载地址及封面图片
* 使用内置的命令行音乐播放器(支持暂停，调整音量, 显示歌词)播放歌曲
* 动态歌词显示
* 下载歌曲

功能持续更新中, 目前功能还未完善.

## 下载地址
[下载最新的 KuGou Music Console 构建](https://github.com/xiaomu18/KuGouMusicConsole/releases)

## 系统要求

### Windows

(Windows NT) Windows 7 or later. [ 已在 Windows 7, 8, 10, 11 上进行测试 ]
* 你可以试试在 Windows NT (2000, 98, 95 上进行测试) 反正我没试过

由于使用 VS 2019 编译可能不适配旧版本。Windows 10适配。

### Linux & Mac

暂不适配 ( 因动态歌词显示使用 Win32 API )
