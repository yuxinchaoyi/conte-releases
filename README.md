# Conte

Conte 是 Obsidian 桌面端的科研工作台。本仓库当前为私有试运行仓库，供有访问权的账户检查安装包和更新文件。

> 当前 1.7.14 是预发布版：仓库为 private，普通用户无法下载；授权域名尚未上线，三天试用、激活、续验和插件内检查更新暂不可用。完成公网验收并开放下载后再提供正式销售与完整使用。

## 安装

1. 有仓库访问权的测试人员在 [Releases](https://github.com/yuxinchaoyi/conte-releases/releases) 下载最新的 `yanxu-research-<版本>.zip`。
2. 解压后，把其中的 `yanxu-research` 文件夹放进笔记库的 `.obsidian/plugins/`。
3. 重启 Obsidian，在“设置 → 第三方插件”中启用 Conte。需要 Obsidian 1.13 或更新的桌面版。

授权服务开放后，首次使用可选择三天试用，或输入激活码。一枚激活码绑定一台电脑；同一台电脑的多个笔记库共用授权。试用、激活和续验需要连接 `https://license.conte.us.ci`，普通 Markdown 笔记仍保存在自己的笔记库。

## 更新

正式开放下载后，在“设置 → Conte → 检查更新”中确认安装。更新清单由 Conte 签名，安装时逐文件校验；文件从此仓库的 GitHub Releases 下载。仓库保持 private 期间，普通客户端无法沿该路径下载更新文件。更新会保留笔记库、设置和本机授权。

如需 Zotero 返回助手，可从同一 Release 下载 `conte-zotero-<版本>.xpi`，在 Zotero 的插件管理器中安装。
