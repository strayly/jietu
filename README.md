# 截图快手（预构建可执行版）

免费的Windows 截图 / 录屏小工具，可以截长图，录屏，简单，实用，不错的工具。


## 运行方式
1. 下载本仓库（或 Releases 中的压缩包）并解压。
2. 双击 `QuickShot.exe` 即可启动。
3. 悬浮球常驻系统托盘；快捷键：`Ctrl+Shift+A` 截图、`Ctrl+Shift+Q` 截全屏、`Ctrl+Shift+S` 结束长截图。
4. 点击悬浮球（左键 / 右键均可）即弹出功能菜单：截图、录屏、截全屏、设置、帮助、退出等。

## 目录说明
- `QuickShot.exe`：程序入口。
- `_internal/`：运行依赖（Python 运行时、Pillow、ffmpeg、资源等），**不要单独移动或删除**。

## 帮助与反馈
- 在线帮助 / 使用说明 / 问题反馈：https://www.licstack.com/quickshot/help.html

## 版本
当前预构建版本：`1.0.5`

> 注：录屏功能依赖 `_internal/imageio_ffmpeg/binaries/ffmpeg-win-x86_64-v7.1.exe`，已随本仓库一并提供，无需另行安装 ffmpeg。
