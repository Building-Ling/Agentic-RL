# Agentic RL：学习与研究计划

> 状态：讨论稿（2026-11-10）  
> 目标：通过持续学习和研究实践，逐步具备参与 Agentic RL、Agent Evaluation、AI Agent 与 AI Safety 研究的能力。

## 长期目标

希望在 2027 年 3–8 月争取一段实际 Research Experience，参与真实实验与论文合作，并于 2027 年秋季入读美国 Master's 项目。

初步兴趣范围是 **Reliable Agentic Systems：Harness、Evaluation 与 Reinforcement Learning**。这只是探索范围，不是最终 Research Question。具体问题需要通过文献、基线、公开 Benchmark、可用算力和实验结果逐步收敛。

## 当前起点

- **PyTorch / Deep Learning**：用过 PyTorch，但希望从 Tensor、Autograd、神经网络、优化和训练流程等核心概念重新建立理解。
- **Reinforcement Learning**：做过 CartPole / PPO 相关工作，目前记得大致流程，但需要重新梳理 MDP、策略梯度、PPO 等概念及其实现。
- **Agent Harness**：有实际项目经验，也对 Lark CLI 有兴趣；目前希望先补整体技术图景和设计取舍，暂不急于深入某个实现。
- **数学基础**：线性代数、微积分和概率统计需要复习；采取遇到概念时针对性补齐的方式。

## 学习与研究原则

1. 建立核心知识树，理解概念之间的关系，不以记 API 和语法为目标。
2. 可以用 LLM 辅助编程，但需要能读懂代码、Debug、验证实验并解释结果。
3. 研究题目保持开放。先探索，再根据已有工作和可验证证据决定是否深入。
4. 优先复用成熟框架，避免为了学习而重复造完整系统；需要亲手实现的部分服务于理解和实验。
5. 研究工作重视对照实验、消融、复现和失败案例分析，不只展示成功结果。
6. 按阶段产出推进，不把每天或每周投入时长设为硬性限制。
7. 每个有价值的探索都可以留下代码与过程记录；暂不规定统一 repo 模板或发布流程。

## 能力建设主线

### PyTorch / Deep Learning

逐步理解 Tensor 与张量形状、Autograd、神经网络模块、损失函数、优化器，以及从数据输入到参数更新的训练流程。以能够解释和排查训练行为为目标。

### Reinforcement Learning

从 MDP、轨迹、回报和策略表示开始，逐渐连接策略梯度、价值函数、优势估计与 PPO。之后再学习 GRPO、Reward Modeling、Rollout 和 Agent RL，并检验它们各自解决的问题与适用条件。

### Agent Harness

先建立架构全景，理解 Agent Runtime、Tool Calling、Context / Memory、Trajectory Collection、Environment Interaction、权限控制、调度和 Evaluation Infrastructure 的职责与取舍。Lark CLI 是一个感兴趣的工具接入层入口；个人助手想法是可能的学习载体，不是预设研究方向。

## 阶段路线

### 2026 年 11 月起：梳理基础与研究版图

- 梳理 PyTorch、RL 和 Harness 的知识树与个人薄弱点。
- 恢复 PyTorch 和 RL 的核心概念，数学按需补齐。
- 初步梳理 Agent Harness、Agentic RL 和 Evaluation 的研究版图与代表性系统。
- 保持多个兴趣方向开放，不提前选定 Research Question。

### 2026 年 11 月–2027 年 1 月：基础学习与小规模探索

- 通过小实验恢复 PyTorch 训练流程和 RL 的实现直觉。
- 阅读相关工作、成熟仓库和公开 Benchmark，逐步比较方法与系统。
- 对有兴趣的问题做可运行的小探索，并记录设计、结果和失败情况。

### 2027 年 1 月–3 月：问题收敛与初步结果

- 从探索中筛选有文献依据、可实现且可验证的问题。
- 明确 Research Question、Hypothesis、Baseline、指标和实验计划。
- 逐步形成可复现实验、公开代码与 Technical Report 初版。
- 开始寻找 Research Collaborator；论文投稿取决于问题质量和证据，不预设为硬指标。

### 2027 年 3 月–8 月：争取并参与研究合作

- 争取加入中国高校、研究院或美国研究组的实际研究工作。
- 根据合作者反馈继续完善问题、实验和报告；必要时调整方向。

## 候选探索（尚未承诺）

- **个人助手**：按天气推送注意事项、结合上下班时间询问是否提前开启空气净化器，并整理记录用户口述事项。
- **Lark CLI / Agent Harness**：理解成熟工具接口如何让 Agent 使用外部业务能力，并进一步连接运行时、权限和评估问题。

现成系统（例如 OpenClaw）可能已覆盖个人助手的多项功能。因此，学习价值应来自理解架构、复用成熟组件和提出可验证的问题，而不是完整重写已有产品。

## 待讨论事项

- PyTorch 与 RL 第一阶段的具体里程碑尚未确定。
- “重新实现并解释一个最小 PPO + CartPole”是一个候选练习，尚未确认。
- Harness 全景的覆盖范围、研究主题和最终 Research Question 都保持开放。
- 是否以及何时公开具体探索成果，之后结合内容和研究进展决定。
