# AI-For-Beginners-Zh


![img](https://img.shields.io/github/license/microsoft/AI-For-Beginners.svg)![img](https://img.shields.io/github/contributors/microsoft/AI-For-Beginners.svg)![img](https://img.shields.io/github/issues/microsoft/AI-For-Beginners.svg)![img](https://img.shields.io/github/issues-pr/microsoft/AI-For-Beginners.svg)![img](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)


## 人工智能初学者课程

通过我们为期12周、共24课的完整课程体系，探索**人工智能**（AI）的奇妙世界！课程包含实践课程、测验和实验环节，专为初学者设计，涵盖TensorFlow、PyTorch等工具以及AI伦理知识。

![ai-overview](pics/ai-overview.png)

## 你将学到什么

**课程思维导图**

在本课程中，你将学习：

- 人工智能的不同方法，包括传统的符号主义方法——**知识表示**与推理（GOFAI）。
- **神经网络**与**深度学习**，现代AI的核心技术。我们将使用最流行的两大框架TensorFlow和PyTorch的代码来阐释这些重要概念。
- 用于图像和文本处理的**神经网络架构**。我们会介绍一些最新模型，但可能无法完全覆盖最前沿的技术。
- 一些不太主流的AI方法，如**遗传算法**和**多智能体系统**。

本课程不会涉及的内容：

> 可在Microsoft Learn课程集合中找到本课程的所有补充资源

- **AI在商业中的应用案例**。建议学习Microsoft Learn上的"面向商业用户的AI入门"学习路径，或与INSEAD合作开发的AI商学院课程。
- **传统机器学习**，相关内容在我们的《机器学习初学者课程》中有详细介绍。
- 使用**认知服务**构建的实用AI应用。建议从Microsoft Learn的视觉、自然语言处理、**Azure OpenAI服务的生成式AI**等模块开始学习。
- 特定的ML**云平台框架**，如Azure Machine Learning、Microsoft Fabric或Azure Databricks。建议学习"使用Azure Machine Learning构建和运营机器学习解决方案"和"使用Azure Databricks构建和运营机器学习解决方案"学习路径。
- **对话式AI**和**聊天机器人**。有专门的"创建对话式AI解决方案"学习路径，也可参考这篇博客文章获取更多信息。
- 深度学习背后的**深奥数学知识**。建议阅读Ian Goodfellow、Yoshua Bengio和Aaron Courville合著的《深度学习》，该书也可在https://www.deeplearningbook.org/在线获取。

如需温和了解**云端AI**主题，可考虑学习"Azure人工智能入门"学习路径。

## 课程内容

| | 课程链接| PyTorch/Keras/TensorFlow| 实验|
| ---| ---| ---| ---|
| 0| 课程设置| 搭建开发环境| |
| I| **AI简介**| | |
| 01| AI简介与历史| -| -|
| II| **符号主义AI**| | |
| 02| 知识表示与专家系统| 专家系统/本体论/概念图| |
| III| **神经网络入门**| | |
| 03| 感知机| Notebook| 实验|
| 04| 多层感知机与自定义框架构建| Notebook| 实验|
| 05| 框架入门(PyTorch/TensorFlow)与过拟合| PyTorch / Keras / TensorFlow| 实验|
| IV| **计算机视觉**| PyTorch / TensorFlow| 探索Azure计算机视觉|
| 06| 计算机视觉入门.OpenCV| Notebook| 实验|
| 07| 卷积神经网络与CNN架构| PyTorch / TensorFlow| 实验|
| 08| 预训练网络、迁移学习与训练技巧| PyTorch / TensorFlow| 实验|
| 09| 自编码器与变分自编码器| PyTorch / TensorFlow| |
| 10| 生成对抗网络与艺术风格迁移| PyTorch / TensorFlow| |
| 11| 目标检测| TensorFlow| 实验|
| 12| 语义分割.U-Net| PyTorch / TensorFlow| |
| V| **自然语言处理**| PyTorch / TensorFlow| 探索Azure自然语言处理|
| 13| 文本表示.词袋/TF-IDF| PyTorch / TensorFlow| |
| 14| 语义词嵌入.Word2Vec与GloVe| PyTorch / TensorFlow| |
| 15| 语言模型.训练自定义词嵌入| PyTorch / TensorFlow| 实验|
| 16| 循环神经网络| PyTorch / TensorFlow| |
| 17| 生成式循环网络| PyTorch / TensorFlow| 实验|
| 18| Transformer.BERT| PyTorch / TensorFlow| |
| 19| 命名实体识别| TensorFlow| 实验|
| 20| 大语言模型、提示词编程与小样本任务| PyTorch| |
| VI| **其他AI技术**| | |
| 21| 遗传算法| Notebook| |
| 22| 深度强化学习| PyTorch / TensorFlow| 实验|
| 23| 多智能体系统| | |
| VII| **AI伦理**| | |
| 24| AI伦理与负责任AI| Microsoft Learn: 负责任AI原则| |
| IX| **扩展内容**| | |
| 25| 多模态网络、CLIP与VQGAN| Notebook| |

## 每节课包含

- 课前阅读材料
- 可执行的Jupyter Notebook（通常针对特定框架，如**PyTorch**或**TensorFlow**）。可执行Notebook包含大量理论内容，因此理解主题至少需要完成一个版本的Notebook（PyTorch或TensorFlow任选其一）。
- 部分主题的**实验环节**，让你有机会将所学知识应用到具体问题中。
- 部分章节包含指向**MS Learn**模块的链接，涵盖相关主题。

## 开始学习

- 我们创建了设置课程来帮助你搭建开发环境。 - 针对教育工作者，我们也准备了课程搭建指南！
- 如何在VSCode或Codespace中运行代码

按以下步骤操作：

Fork仓库：点击本页面右上角的"Fork"按钮。

克隆仓库：`git clone https://github.com/microsoft/AI-For-Beginners.git`

别忘了给本仓库加星(🌟)以便日后查找。

## 结识其他学习者

加入我们的官方AI Discord服务器，结识正在学习本课程的其他学习者，建立联系并获得支持。

## 测验

> **关于测验的说明**：所有测验都包含在etc\quiz-app文件夹的Quiz-app中，它们链接在课程内。测验应用可以本地运行或部署到Azure；请按照`quiz-app`文件夹中的说明操作。测验内容正在逐步本地化。

## 寻求帮助

你有建议或发现拼写或代码错误？请提交issue或创建pull request。

## 特别感谢

- **✍️ 主要作者：** Dmitry Soshnikov博士
- **🔥 编辑：** Jen Looper博士
- **🎨 思维导图插画师：** Tomomi Imura
- **✅ 测验创建者：** Lateefah Bello, MLSA
- **🙏 核心贡献者：** Evgenii Pishchik

## 其他课程

我们的团队还开发了其他课程！查看：

- 生成式AI初学者课程
- 生成式AI初学者课程 .NET版
- 使用JavaScript的生成式AI
- 人工智能初学者课程
- 数据科学初学者课程
- 机器学习初学者课程
- 网络安全初学者课程
- Web开发初学者课程
- 物联网初学者课程
- XR开发初学者课程
- 精通GitHub Copilot的结对编程
- 精通GitHub Copilot的C#/.NET开发
- 选择你的Copilot冒险
