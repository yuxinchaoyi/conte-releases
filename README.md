# Conte

Conte 是 Obsidian 桌面端的科研工作台。本仓库提供预发布安装包和签名更新文件。

> Conte 1.7.23 为 GitHub 预发布版本，仅供验收，不作为正式销售版本。收件箱“完成”“编辑日程”“延后任务”三个按钮在隔离 Obsidian 预览库真实 pointer 点击通过：完成状态与计数正确、编辑表单打开正确、延期日期与计数更新正确；自动日记事件不再进入收件箱。源码自动化测试 484/484 通过。全新临时 Vault 的两份副本完整加载后，7/7 个模块 UUID 保持。现有真实 Vault 的 1.7.23 更新验收待完成，目前仍运行 1.7.22；Windows 与 Zotero 目标应用未覆盖。

## 安装

1. 在 [Releases](https://github.com/yuxinchaoyi/conte-releases/releases) 下载最新的 `yanxu-research-<版本>.zip`。
2. 解压后，把其中的 `yanxu-research` 文件夹放进笔记库的 `.obsidian/plugins/`。
3. 重启 Obsidian，在“设置 → 第三方插件”中启用 Conte。需要 Obsidian 1.13 或更新的桌面版。

授权入口现已接通公网，首次使用可选择三天试用，或输入激活码。一枚激活码绑定一台电脑；同一台电脑的多个笔记库共用授权。试用、激活和续验需要连接 `https://license.conte.us.ci`，普通 Markdown 笔记仍保存在自己的笔记库。公网授权流程的实测结果以正式验收报告为准。

## 更新

在“设置 → Conte → 检查更新”中确认安装。更新清单由 Conte 签名，安装时逐文件校验；文件从此仓库的 GitHub Releases 下载。更新会保留笔记库、设置和本机授权。该路径已在 macOS 真实 Vault 完成 1.7.15→1.7.22 实测，其他平台的插件内更新仍待验收。

如需 Zotero 返回助手，可从同一 Release 下载 `conte-zotero-<版本>.xpi`，在 Zotero 的插件管理器中安装。
