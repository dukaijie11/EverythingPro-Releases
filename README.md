# EverythingPro

EverythingPro 是基于 Everything 索引引擎的 Windows 桌面文件检索工具。记得文件名、扩展名或目录时，可直接使用 Everything 原生查询语法。仅掌握用途或相关线索时，可通过 AI 将自然语言转换为多组查询，在本机索引中查找候选文件。

**[下载最新正式版](https://github.com/dukaijie11/EverythingPro-Releases/releases/latest)**　·　[安装包下载（全部版本）](https://github.com/dukaijie11/EverythingPro-Releases/releases)　·　[使用说明](docs/USER-GUIDE.md)　·　[版本说明](ReleaseNote/)　·　[问题反馈](https://github.com/dukaijie11/EverythingPro-Releases/issues)

![EverythingPro 1.0.0 文件搜索主窗口，使用组合表达式检索预算或报销工作簿](docs/images/file-search.png)

## 快速开始

1. 在 Windows 10 或 Windows 11 **x64** 上运行安装包，按系统提示授予安装权限。安装器自动复用兼容的 Everything，或配置随包提供的独立引擎。
2. 打开 EverythingPro，待底部显示「Everything 已连接」，在「文件搜索」中输入 `ext:pdf dm:today`，即可查找今天修改过的 PDF。普通文件搜索无需 API Key。
3. 双击结果打开文件，或选中结果后按 `Ctrl + Enter` 在资源管理器中定位。在其他应用中按 `Ctrl + Alt + Space` 可调出快捷搜索。

## 按任务查阅

| 任务 | 手册章节 |
| --- | --- |
| 使用文件名、路径、扩展名或日期组合查询 | [文件搜索与查询语法](docs/USER-GUIDE.md#file-search) |
| 自定义文件类型、对结果排序、复制完整路径 | [筛选与结果操作](docs/USER-GUIDE.md#results) |
| 配置 DeepSeek、OpenAI 或兼容网关 | [配置 AI 服务](docs/USER-GUIDE.md#ai-service) |
| 按用途检索文件，查看 AI 生成的条件及发送的数据 | [自然语言查询与深度搜索](docs/USER-GUIDE.md#ai-search) |
| 修改全局唤醒键、设置登录启动 | [快捷搜索与窗口设置](docs/USER-GUIDE.md#shortcuts) |
| 检查更新、修复引擎连接或处理升级失败 | [应用内更新](docs/USER-GUIDE.md#updates) · [故障排查](docs/USER-GUIDE.md#troubleshooting) |

## 下载与文档

从发行页的 **Assets** 下载 `EverythingPro-<版本号>-Setup-x64.exe`。历史版本各自的发行页保留对应安装包。离线手册含可在浏览器中打开的 HTML、Markdown 原文和界面截图。[全部发行版本](https://github.com/dukaijie11/EverythingPro-Releases/releases) · [下载 1.0.0 离线手册](https://github.com/dukaijie11/EverythingPro-Releases/releases/download/v1.0.0/EverythingPro-1.0.0-User-Manual-zh-CN.zip)

Everything 索引引擎与 SDK 由 voidtools 提供。安装包内附第三方组件声明及许可证。[Everything 官方网站](https://www.voidtools.com/)
