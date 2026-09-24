# Conte

Conte 是 Obsidian 桌面端的科研工作台。本仓库提供预发布安装包和签名更新文件。

> 当前 1.7.14 是预发布版：安装包可公开下载，`license.conte.us.ci` 已接通公网；在线试用、激活、续验及插件内更新正在端到端验收。完成跨平台验收后再提供正式销售与完整使用。

## 安装

1. 在 [Releases](https://github.com/yuxinchaoyi/conte-releases/releases) 下载最新的 `yanxu-research-<版本>.zip`。
2. 解压后，把其中的 `yanxu-research` 文件夹放进笔记库的 `.obsidian/plugins/`。
3. 重启 Obsidian，在“设置 → 第三方插件”中启用 Conte。需要 Obsidian 1.13 或更新的桌面版。

授权入口现已接通公网，首次使用可选择三天试用，或输入激活码。一枚激活码绑定一台电脑；同一台电脑的多个笔记库共用授权。试用、激活和续验需要连接 `https://license.conte.us.ci`，普通 Markdown 笔记仍保存在自己的笔记库。公网授权流程的实测结果以正式验收报告为准。

## 更新

在“设置 → Conte → 检查更新”中确认安装。更新清单由 Conte 签名，安装时逐文件校验；文件从此仓库的 GitHub Releases 下载。更新会保留笔记库、设置和本机授权。插件内更新的跨平台实测仍在进行。

如需 Zotero 返回助手，可从同一 Release 下载 `conte-zotero-<版本>.xpi`，在 Zotero 的插件管理器中安装。
