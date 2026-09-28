# Conte

Conte 是 Obsidian 桌面端的科研工作台。本仓库提供预发布安装包和签名更新文件。

> Conte 1.7.22 为预发布版，不作为正式销售版本。源码自动化测试 479/479 通过；独立 Obsidian 预览库已验收文件夹表格入口补齐/撤销/重做保留修改日期及日期表头右对齐。用户拖动实测、真实 Vault 升级、插件内更新安装、Windows 与 Zotero 目标应用验收仍待完成。

## 安装

1. 在 [Releases](https://github.com/yuxinchaoyi/conte-releases/releases) 下载最新的 `yanxu-research-<版本>.zip`。
2. 解压后，把其中的 `yanxu-research` 文件夹放进笔记库的 `.obsidian/plugins/`。
3. 重启 Obsidian，在“设置 → 第三方插件”中启用 Conte。需要 Obsidian 1.13 或更新的桌面版。

授权入口现已接通公网，首次使用可选择三天试用，或输入激活码。一枚激活码绑定一台电脑；同一台电脑的多个笔记库共用授权。试用、激活和续验需要连接 `https://license.conte.us.ci`，普通 Markdown 笔记仍保存在自己的笔记库。公网授权流程的实测结果以正式验收报告为准。

## 更新

在“设置 → Conte → 检查更新”中确认安装。更新清单由 Conte 签名，安装时逐文件校验；文件从此仓库的 GitHub Releases 下载。更新会保留笔记库、设置和本机授权。插件内更新的跨平台实测仍在进行。

如需 Zotero 返回助手，可从同一 Release 下载 `conte-zotero-<版本>.xpi`，在 Zotero 的插件管理器中安装。
