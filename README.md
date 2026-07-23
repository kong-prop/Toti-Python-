# Toti (饕餮)

> 去中心化专家集群 · 四层记忆网络 · 沙盒安全隔离 · 自我进化闭环

Toti 是一个运行于 Windows 环境的个人 AI 助手系统，以 **20% 的开发成本验证 95% 的核心架构逻辑**。本项目为 Python 试验机版本，所有接口、协议、数据格式与 .NET 正式版 100% 兼容。

## 核心特性

- 🧠 **神经中枢**：双通道异步消息总线，协程槽实现复杂任务串/并行编排
- 🧬 **海马体**：L1~L4 四层记忆网络（缓存/SQLite/图数据库/向量库）
- 🎯 **大脑皮层**：去中心化专家集群，三级决策链路（Tier0 反射 / Tier1 本地模型 / Tier2 上报协同）
- 🛠️ **四肢工具舱**：原子工具热插拔，`importlib` 动态加载毫秒级生效
- 🩸 **血液系统**：TOON 文本语言 + CBOR 二进制协议，双态统一信号模型
- 🛡️ **沙盒安全层**：物理影子目录 + 内存虚拟 FS，OpLog 预演与确定性重放
- 🔄 **自我进化**：自我认知专家主动反思 + 自我进化专家生成代码热加载

## 技术栈

- **核心**：Python 3.12+ · asyncio · FastAPI · Uvicorn
- **记忆**：ChromaDB · aiosqlite · NetworkX · cachetools
- **协议**：Lark (EBNF) · cbor2 · Pydantic
- **AI**：OpenAI SDK · Ollama · 本地小模型 (Phi-3/Qwen2.5)
- **系统**：psutil · pywin32 · watchdog

## 快速开始

```bash
uv venv
uv sync
python main.py
