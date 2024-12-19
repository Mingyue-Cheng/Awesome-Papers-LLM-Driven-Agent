以下是中文版的 README：

---

# LLM 驱动的智能体研究精选论文集

本仓库汇集了关于**大语言模型（LLM）驱动智能体**的前沿研究论文，重点关注其理论基础、技术进展以及实际应用，为研究人员提供系统化的学习资源。

## 智能体定义

智能体（Agent）的广义定义为：通过传感器**感知环境**并通过执行器**作用于环境**的实体。对于 LLM 驱动的智能体而言，这种感知-行动循环由大语言模型的能力所支持，使智能体能够实现自主或协作的推理、计划与行动。

---

## LLM 驱动智能体的技术框架

本仓库按照智能体的结构与协作方式，将论文分为两个主要领域：

### 1. **单智能体技术**
单智能体系统专注于单个智能体通过 LLM 独立完成复杂任务，其核心技术包括以下三个方面：

#### 1.1 复杂任务推理
- **任务规划（Planning）：** 将多步任务分解为可执行子任务，结合层次化任务规划或树状推理方法。
- **逻辑推理（Thought）：** 利用如**Chain-of-Thought (CoT)** 等技术提升 LLM 的多步推理能力。
- **深度思考（Deliberation）：** 基于中间结果的迭代优化策略，逐步改进行动或解决方案。

#### 1.2 与外界环境的交互
- **动作与工具调用（Action & Tool Use）：** 集成外部 API、检索增强生成（RAG）以及动态资源使用，提升任务解决能力。
- **外界反馈（Feedback Integration）：** 利用强化信号或用户交互进行迭代学习和性能优化。

#### 1.3 自主学习与进化
- **自我反思与批评（Self-Reflection & Critique）：** 智能体自动评估任务结果并定位错误。
- **自主改进（Self-Improvement）：** 基于观察到的不足或反馈更新内在模型或策略。

---

### 2. **多智能体协作**
多智能体系统通过多个 LLM 驱动的智能体实现协作行为，进一步扩展了单智能体的能力。其主要研究方向包括：

#### 2.1 分布式问题求解
- **任务分解与分配：** 将复杂任务分解为子任务，并分配给具备特定技能的智能体进行并行执行。
- **一致性机制：** 利用投票、协商等协议在智能体之间就共享目标或结果达成一致。

#### 2.2 协同合作行为
- **角色分工：** 在同一环境下为智能体分配不同角色（如规划者、执行者、批评者），以形成互补优势。
- **通信策略：** 设计高效且上下文感知的通信协议，用于信息交换或行动协调。

#### 2.3 智能体社会
- **模拟社会行为：** 模仿人类社会系统中的交互，例如协作问题求解或竞争环境中的对抗。
- **多智能体强化学习：** 在合作或对抗场景下训练智能体，优化群体层级的目标。

---

## 贡献指南

我们欢迎社区贡献，包括但不限于：
1. **新增论文：** 提交与 LLM 驱动单智能体或多智能体系统相关的高质量论文。
2. **论文解读：** 提供现有论文的总结或评论，以加深理解。
3. **实际应用：** 提交真实世界中的实现案例或展示 LLM 驱动智能体的实际效用。

请通过提交 Pull Request 来贡献内容，并附上简要的描述。

---

## 致谢

本仓库受益于人工智能领域的快速发展以及大语言模型在自主智能体系统中的变革潜力。特别感谢所有在这一激动人心的研究领域中做出贡献的学者与研究人员。

---

如需进一步修改，请随时告知！