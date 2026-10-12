# World Conquer 4 Creator

[English](README.md) | **简体中文**

《世界征服者 4》的本地关卡与地图编辑器，以 Windows 桌面程序分发。本仓库仅保存发布包及介绍文档。

## 下载与启动

1. 从 [Releases](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/latest) 下载 **World-Conquer-4-Creator-0.2.4-Windows-x64.zip**。
2. 将整个发布包解压到可写文件夹。
3. 运行 `WC4EditorLauncher.exe`，按提示完成安装。

无需安装 Python，但需要本机已有兼容的游戏安装；首次使用时会在本机生成所需资源。发布包不包含游戏素材及游戏数据。

编辑器界面保持简体中文，上方语言入口只切换介绍文档。0.2.4 已在维护者的 Windows 11 电脑上、移除程序搜索路径中的 Python 后验证；尚未完成另一台净机的验收。

## 编辑与作品

支持关卡、事件、单位部署、空袭和征服地图编辑，并可从桌面窗口导出普通地图与征服地图。

程序版本、生成资源、作品和备份分别存放于 `%LOCALAPPDATA%\WC4Editor`。更新保留作品；重要作品请保留自己的备份。

受保护的游戏目录可以作为资源来源。部署要求目标可写，并将受支持的关卡文件与对应校验记录一起更新；编辑器不修改游戏 EXE。

## 编译与源码保护

自有 Python 与 JavaScript 业务逻辑已编译，包括地图与单位绘制、动画、编辑交互、选关、图鉴和更新。发布包不附带可直接阅读的实现 `.py`／`.js` 文件，本机 HTTP 服务也不返回这些实现源码。

HTML／CSS、加载信号、数据和界面文字、动态事件调用表达式及 GPU 着色器字符串仍可见。编译产物仍可逆向；这不是绝对保密承诺，也不是完整的 C++ 绘制重写。

## 更新与有效期

更新使用签名清单核验下载包，准备好的版本在下次启动时生效。激活恢复会保留前一版本与作品。

每次构建离线有效期为 14 天，第 11 天开始提醒；到期后仍可查看和导出，编辑与部署需要有效版本。签名线上策略也可以将版本设为只读。具体日期见发布说明。

## 第三方组件

安装时会显示适用的 Windows 运行库条款。第三方告知位于安装目录的 `resources/licenses`。FFmpeg LGPLv2.1+、Blink 对应源码及运行库替换说明随同本次发布提供：

- [FFmpeg 源码](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.2.4/NW-runtime-FFmpeg-source-0.118.0.tar.gz)
- [Blink 源码](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.2.4/NW-runtime-Blink-source-0.118.0.tar.gz)
- [源码与运行库替换说明](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.2.4/NW-runtime-source-instructions-0.118.0.zip)

这些是第三方组件源码，不是编辑器实现源码。下载包不含游戏素材、游戏数据、用户作品、研究、仓库历史或签名私钥；0.1.0 继续保持撤回。

本项目是独立工具，并非 EasyTech 官方产品。《世界征服者 4》及其素材的权利属于相应权利人。
