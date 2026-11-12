# World Conquer 4 Creator

[English](README.md) | **简体中文**

Creator 是《世界征服者 4》的独立 Windows 本地创作工具，简要支持关卡、地图、事件、单位部署编辑及地图图片导出。

**必须先安装官方原版电脑版《世界征服者 4》，才能正常使用 Creator。Creator 不能脱离兼容的本机游戏安装独立运行。**

## 官方权利与工具边界

《世界征服者 4》的商标、美术、音频及原版游戏内容等权利，属于 EasyTech 及相应权利人。Creator 是独立项目，并非 EasyTech 官方产品，也不代表获得官方认可或背书。

- **发布包不含原版游戏素材、游戏数据或游戏本体。** 所需资源仅从用户本机已安装的官方电脑版游戏中读取并在本机准备。
- **不提供局外货币、已拥有将领等账号资源的修改功能。** 不用于增加付费货币、获取将领或授予其他账号权益。
- 工具用于本地关卡与地图创作，不修改游戏 EXE。
- 请通过官方渠道获取游戏，尊重权利人并遵守原版游戏的许可与使用条款。安装 Creator 不代表获得重新分发原版素材的授权。

## 安装与使用

1. 安装官方 Windows 电脑版《世界征服者 4》。
2. 从 [Releases](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/latest) 下载完整的 **Windows-x64** 发布包，将全部文件解压到可写文件夹。较小的 `WC4Editor-<版本>.zip` 是自动更新负载，不是首次安装包。
3. 运行 `WC4EditorLauncher.exe` 并按提示操作。首次使用会读取本机游戏并准备资源，无需另装 Python。
4. 选择关卡开始编辑，或从**设置**打开使用教程。界面语言可在 **Settings → Interface language** 切换。将受支持的修改生效到游戏，需要目标目录可写。

作品及生成资源与程序分开保存在 `%LOCALAPPDATA%\WC4Editor`。更新时先关闭 Creator，将完整新发布包解压到新文件夹，再运行其中的启动器；更新会保留作品，重要作品仍请自行备份。

## 有效期与发布保护

- **每次构建离线有效期为 14 天，第 11 天开始提醒。** 具体生效与到期日期见相应版本的发布说明。
- **到期后仍可查看和导出；编辑、写回与生效需要有效版本。** 到期不会删除已有作品，请更新至有效版本后继续编辑。
- 更新通过签名清单核验发布包；签名线上策略也可将版本设为只读。
- Creator 自有业务实现以编译形式提供，减少实现源码直接分发；编译不代表无法逆向。第三方组件仍按各自许可提供必要告知及源码。

这些措施用于 Creator 的版本与发布管理，不改变原版游戏及其内容的权利归属。

## 第三方组件

安装时会显示适用的运行库条款，第三方告知位于 `resources/licenses`。现有发布提供对应组件源码与替换说明：

- [FFmpeg 源码](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.3.0/NW-runtime-FFmpeg-source-0.118.0.tar.gz)
- [Blink 源码](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.3.0/NW-runtime-Blink-source-0.118.0.tar.gz)
- [源码与运行库替换说明](https://github.com/xiaomaocjka-create/World-Conquer-4-Creator/releases/download/v0.3.0/NW-runtime-source-instructions-0.118.0.zip)

以上是第三方组件源码，不是 Creator 自有实现源码。
