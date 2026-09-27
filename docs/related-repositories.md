# 相关 GitHub 仓库

查阅日期：2026-09-27。以下说明依据各项目公开 README；未对这些项目逐一运行测试，也不以仓库名称推定协议版本兼容性。

| 仓库 | 定位 | 本项目可参考的内容 |
| --- | --- | --- |
| [a2aproject/A2A](https://github.com/a2aproject/A2A) | 官方规范与文档 | Agent Card、Message、Task、Artifact 与协议操作 |
| [a2aproject/a2a-python](https://github.com/a2aproject/a2a-python) | 官方 Python SDK | 客户端、服务端及协议适配 |
| [a2aproject/a2a-samples](https://github.com/a2aproject/a2a-samples) | 官方多语言示例 | HelloWorld、远端调用及框架集成 |
| [a2aproject/a2a-inspector](https://github.com/a2aproject/a2a-inspector) | 官方调试工具 | 查看 Agent Card、交互消息与基础校验 |
| [a2aproject/a2a-tck](https://github.com/a2aproject/a2a-tck) | 官方兼容性测试套件 | 按其支持版本核对协议行为 |
| [google/adk-python](https://github.com/google/adk-python) | Agent 开发与编排框架 | 多 Agent 组合、工作流与人工介入 |
| [i-am-bee/beeai-framework](https://github.com/i-am-bee/beeai-framework) | Python / TypeScript 多 Agent 框架 | 工作流、可观测性及 A2A 服务暴露 |
| [themanojdesai/python-a2a](https://github.com/themanojdesai/python-a2a) | 社区 A2A 库 | AgentNetwork、工作流与路由接口设计 |

社区 `python-a2a` 与官方 `a2a-python` 是不同项目；选型时核对包名、版本和兼容范围。

建议先阅读官方规范与 SDK，运行官方最小示例，再对照 ADK、BeeAI 和社区库的编排设计。运行依赖以所选发布版本的文档为准。
