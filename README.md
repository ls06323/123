# 这台电脑上的 DSH 能力清单

由 DSH（DeepSeek Harness）在 2026-11-04 自动生成并提交，用于验证 Git 与 GitHub 的完整闭环。

## 已安装并验证的能力
- **代码智能（LSP）**：8 个 lsp_* 工具，支持 TypeScript 与 Python 的诊断、补全、跳转、重命名、格式化。
- **浏览器控制**：34 个 bcdp_* 工具，通过 CDP 驱动本机 Edge，可打开网页、点击、填表、截图、执行 JS。
- **桌面控制**：computer / windows / ui_elements 工具，可操作 Windows 应用（按应用授权、Esc 暂停）。
- **GitHub**：gh_* / pr_* 15 个工具，可读写 Issue、PR、CI 状态，可创建分支、提交、推送、开 PR。
- **MCP / SSH**：已装连接器框架，暂无配置的 MCP 服务器和远程机器。
- **PTC 模式**：内置，可程序化调用工具，适合批量任务。

## 说明
- 本文件由 DSH 通过便携版 Git 提交，token 仅用于本次推送，未写入仓库。
- 原仓库是空的，这是它的第一个提交。
