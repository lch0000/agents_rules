# Python 项目开发与提交规范

此仓库保存可复用的 Python 项目协作约定，涵盖代码结构、接口文档、dotenv 环境变量、验证流程及 Git 提交习惯。

- [通用规范 AGENTS.md](AGENTS.md)
- [ChatGPT 文档 Python 项目通用开发与提交规范](https://chatgpt.com/space/page_e530984b15788191978b3b760684ad32)（需有访问权限）

## 在新项目中使用

将本仓库的 `AGENTS.md` 复制到新项目根目录，再补充项目的技术栈、目录职责、启动与测试命令、接口文档版本和部署要求。已有同名文件时合并相关约定，不直接覆盖项目规范。

## 作为本机 Codex 默认约定

如需跨项目自动加载，可将通用内容合并到 Codex 主目录的 `AGENTS.md`，默认路径为 `~/.codex/AGENTS.md`。如果设置了 `CODEX_HOME`，使用该目录。安装前检查已有全局规范和 `AGENTS.override.md`，保留原有约定。

本仓库和 ChatGPT 文档用于存储与查阅；仅将内容保存到这两个位置，不会自动安装为本机全局约定。更换机器时需自行同步，修改任意一份后也需同步另一份。

## 维护

通用约定放在本仓库，项目特例放在各项目自己的 `AGENTS.md`。提交标题采用 `[类型] 中文说明`，例如 `[docs] 更新Python项目通用协作规范`。

参考：[Codex AGENTS.md 官方说明](https://learn.chatgpt.com/docs/agent-configuration/agents-md)。
