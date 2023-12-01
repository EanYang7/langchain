# 🦜️🔗 LangChain

⚡ 通过组合composability构建LLMs的应用程序⚡

寻找JS/TS库？查看 [LangChain.js](https://github.com/langchain-ai/langchainjs).

## 快速安装

使用pip:
```bash
pip install langchain
```

使用conda:
```bash
conda install langchain -c conda-forge
```

## 🤔什么是LangChain?

**LangChain** 是一个用语言模型驱动的应用程序开发框架。它使得可以开发以下类型的应用程序：

+ **具备上下文感知性**：将语言模型连接到上下文来源（提示说明、少量示例、用于支撑其回应的内容等）。
+ **推理**：依赖于语言模型进行推理（根据提供的上下文如何回答，采取什么行动等）。

这个框架包含几个部分。

- **LangChain库**：Python和JavaScript库。包含各种组件的接口和集成，用于将这些组件组合成链和代理的基本运行时，以及链和代理的现成实现。
- **[LangChain模板](https://github.com/EanYang7/langchain/tree/master/templates)**：一系列易于部署的各种任务的参考架构。
- **[LangServe](https://github.com/langchain-ai/langserve)**：一个用于将LangChain链部署为REST API的库。
- **[LangSmith](https://smith.langchain.com/)**：一个开发者平台，可让您调试、测试、评估和监视任何LLM框架构建的链，并与LangChain无缝集成。

**此存储库包含** `langchain` ([here](libs/langchain)), `langchain-experimental` ([here](libs/experimental)), and `langchain-cli` ([here](libs/cli)) Python **包，以及** [LangChain 模板](templates).

![LangChain Stack](docs/static/img/langchain_stack.png)

## 🧱你可以使用LangChain构建什么？
❓ **检索增强生成 Retrieval augmented generation**

- [文档](https://python.langchain.com/docs/use_cases/question_answering/)
- 端到端示例 : [Chat LangChain](https://chat.langchain.com) 和[repo](https://github.com/langchain-ai/chat-langchain)

💬 **分析结构化数据**

- [文档](https://python.langchain.com/docs/use_cases/qa_structured/sql)
- 端到端示例 : [SQL Llama2 模板](https://github.com/langchain-ai/langchain/tree/master/templates/sql-llama2)

🤖 **聊天机器人**

- [文档](https://python.langchain.com/docs/use_cases/chatbots)
- 端到端示例 : [Web LangChain (web researcher chatbot)](https://weblangchain.vercel.app) 和 [repo](https://github.com/langchain-ai/weblangchain)

还有更多！前往[用例](https://python.langchain.com/docs/use_cases/)部分了解更多信息。

## 🚀 LangChain如何帮助？
LangChain库的主要价值主张包括：

1. **组件**：用于处理语言模型的可组合工具和集成。组件是模块化且易于使用的，无论您是否使用LangChain框架的其他部分。
2. **现成的链**：用于完成高级任务的内置组件组合

现成的链使您可以轻松入门。组件使您可以轻松自定义现有链并构建新链。

组件分为以下**模块**：

📃  **模型输入/输出：**

这包括提示管理、提示优化、通用的LLM接口以及用于处理LLM的常用实用工具。

**📚 检索：**

数据增强生成涉及特定类型的链，这些链首先与外部数据源交互，以获取用于生成步骤的数据。示例包括长文本摘要和特定数据源的问答。

**🤖 代理：**

代理涉及LLM决定采取哪些行动、采取该行动、看到一个观察结果，并重复该过程直到完成。LangChain提供了代理的标准接口、可供选择的代理以及端到端代理的示例。

## 📖 文档

请参阅[这里](https://python.langchain.com/)以获取完整的文档，其中包括：

- [入门](https://python.langchain.com/docs/get_started/introduction)：安装、设置环境、简单示例
- [界面](https://python.langchain.com/docs/expression_language/)、[模块](https://python.langchain.com/docs/modules/)和[集成](https://python.langchain.com/docs/integrations/providers)的概述
- 用例演示和最佳实践[指南](https://python.langchain.com/docs/use_cases/qa_structured/sql)
- [LangSmith](https://python.langchain.com/docs/langsmith/)、[LangServe](https://python.langchain.com/docs/langserve)和[LangChain模板](https://python.langchain.com/docs/templates/)的概述
- [参考](https://api.python.langchain.com/)：完整的API文档
