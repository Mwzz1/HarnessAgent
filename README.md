该项目是一套 Python 实现的本地智能体运行时（Agent Runtime），同时提供网页交互工作台与命令行两种使用入口。 该框架串联起大模型推理、工具调用执行、操作权限校验、会话状态持久化、会话恢复、长期记忆、技能（Skills）以及智能体自进化整套能力，既可以用来做代码分析、编程辅助，也适合学习、二次扩展 Agent 的底层运行逻辑。

### \## 快速启动 

执行命令 `python -m agents.web`，可以一键启动后端服务与网页前端。 前端使用原生 HTML/CSS/JS 开发，由 Python 后端直接托管，不需要额外安装 npm 依赖、单独启动前端服务。

### ## 来源与许可

本项目的底层 Agent Runtime 参考并复用开源项目 [claude-code-from‑scratch](https://github.com/Windy3f3f3f3f/claude-code-from-scratch)，涵盖工具系统、提示词模板、记忆模块、MCP协议、子智能体等实现。上游代码遵循 MIT 开源协议，原作者版权与完整许可声明见仓库根目录 [LICENSE](LICENSE)，本项目在其基础之上做了修改与功能扩展。
