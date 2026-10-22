# 安装包来源记录

核实日期：2026-10-22。下载后仅重命名，文件内容未修改；未执行或安装这些程序。

## Windows 1.25.0

- 官网入口：<https://rrsp.app/>（同下载页面亦可通过 <https://d.rrsp.com.cn/> 访问）。
- 页面加载的下载模块：<https://cdn.rrmj.plus/c-next/siteapp/assets/index-C3S9PuKZ.js>。
- 页面实际调用的版本 API：<https://api.rrmj.plus/configs/lastest/package-url?ct=win_rrsp_gw>。
- API 返回的官方安装包：<https://dlapp-new.jimihua.plus/pc/windows/1.25.0/RRClientSetup_win_rrsp_gw_1.25.0.exe>；下载最终 URL 与该 URL 一致。
- 官网显示版本来自下载 URL 的版本目录：`1.25.0`。
- 静态读取安装器 PE 资源：`ProductName=人人视频`，`FileVersion=1.25.0.19`，`ProductVersion=1.25.0.19`。
- 安装器 PE Machine 为 `0x014c`（x86）；未独立核实内部应用架构和系统兼容性。
- 原始文件名：`RRClientSetup_win_rrsp_gw_1.25.0.exe`。
- 镜像文件：`rrtv-windows-1.25.0.exe`；大小：`171889248` 字节。
- SHA-256：`ec7464ab48b46a8c3bde9caeed4db2a32350657cf8e8af37a593241825d5d240`。

## Android 10.40.2

- 官网入口：<https://rrsp.app/>。
- 页面下载模块：<https://cdn.rrmj.plus/c-next/siteapp/assets/index-C3S9PuKZ.js>。
- 页面读取官方配置 API 的 `androidXbRrDownLoadUrl` 字段，得到安装包地址。
- 官方 APK：<https://dlapp.rrsp.com.cn/android/rrsp/download/RRSP_10.40.2_android_rrsp_xb_RRSP_signed.apk>；下载无重定向。
- 静态解析 APK 的 `AndroidManifest.xml`：`package=com.example.pptv`，`versionName=10.40.2`，`versionCode=1040002`，`minSdk=24`，`targetSdk=31`。
- APK 原生库目录与 aapt 输出一致：`arm64-v8a`、`armeabi-v7a`。
- 原始文件名：`RRSP_10.40.2_android_rrsp_xb_RRSP_signed.apk`。
- 镜像文件：`rrtv-android-10.40.2.apk`；大小：`145168931` 字节。
- SHA-256：`5218e4a466e1aa186829a50e5a29dce92cec2c89151dfd45b32f0bed4d462a74`。

## macOS 1.2.3

- 来源：用户提供的原始附件 `人人视频_Mac_1.2.3.dmg`，本次未重新从官网下载。
- 版本 `1.2.3` 来自原始文件名；未独立核实应用内版本、CPU 架构与系统要求。
- 镜像文件：`rrtv-mac-1.2.3.dmg`；大小：`34598940` 字节。
- SHA-256：`cfe5ff2841eb5969f921cc08b285f331162207291be9cff8bdb594d9ca70dc19`。

官网链接和配置可能随发布变化；镜像链接固定到各平台对应的 GitHub Release。每个平台独立选择版本。
