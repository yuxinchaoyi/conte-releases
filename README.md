# Conte

Conte 是 Obsidian 桌面端的科研工作台。本仓库提供预发布安装包和签名更新文件。

> Conte 1.7.22 为预发布版，不作为正式销售版本。v1.7.22 发布时源码测试 479/479 通过；当前源码新增授权模拟时钟 E2E 后为 480/480。独立 Obsidian 预览库已验收文件夹表格入口补齐/撤销/重做保留修改日期及日期表头右对齐。真实 Vault 已从 Conte 设置的“检查更新→安装并重启”由 1.7.15 更新至 1.7.22，运行版本、授权和 544 条 Markdown 路径已核实，Editing Toolbar 可见；用户拖动实测和 Windows GUI 仍待验收。macOS Zotero 10.0.4 隔离 profile 中手动安装 1.2.2 后，PDF 选区触发助手并在剪贴板产生带页码 Zotero 链接通过；1.2.0 原生更新检查未发现更新，实际 Obsidian 回跳/写入未测，真实 Zotero 助手仍为 1.2.0，本轮未升级，Windows Zotero 仍待验收。

## 安装

1. 在 [Releases](https://github.com/yuxinchaoyi/conte-releases/releases) 下载最新的 `yanxu-research-<版本>.zip`。
2. 解压后，把其中的 `yanxu-research` 文件夹放进笔记库的 `.obsidian/plugins/`。
3. 重启 Obsidian，在“设置 → 第三方插件”中启用 Conte。需要 Obsidian 1.13 或更新的桌面版。

授权入口现已接通公网，首次使用可选择三天试用，或输入激活码。一枚激活码绑定一台电脑；同一台电脑的多个笔记库共用授权。试用、激活和续验需要连接 `https://license.conte.us.ci`，普通 Markdown 笔记仍保存在自己的笔记库。公网授权流程的实测结果以正式验收报告为准。

## 更新

在“设置 → Conte → 检查更新”中确认安装。更新清单由 Conte 签名，安装时逐文件校验；文件从此仓库的 GitHub Releases 下载。更新会保留笔记库、设置和本机授权。该路径已在 macOS 真实 Vault 完成 1.7.15→1.7.22 实测，其他平台的插件内更新仍待验收。

如需 Zotero 返回助手，可从同一 Release 下载 `conte-zotero-<版本>.xpi`，在 Zotero 的插件管理器中安装。
