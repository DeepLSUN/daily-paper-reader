<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-06
- 运行时间：2026-09-06 22:58:10 UTC
- 运行状态：成功
- 本次总论文数：25
- 精读区：10
- 速读区：15

### 今日简报（AI）
今日精读10篇、速读15篇，聚焦大模型效率与理论方法；最值得关注张量方法贯穿语言模型全流程，以及偏差感知剪枝提升压缩质量。速读中可留意图游走自蒸馏与层级混合专家思路，下一步建议从剪枝或张量应用入手深入实验验证。
- 详情：[/202609/06/README](/202609/06/README)

### 精读区论文标签
1. [Tensor Methods for Language Models: From Token Representation to Training, Adaptation, Inference, Compression, and Interpretability](/202609/06/2608.30505v1-tensor-methods-for-language-models-from-token-representation-to-training-adaptation-inference-compression-and-interpretability)  
   标签：评分：9.0/10、query:llm
   evidence：面向LLM全生命周期组织张量分解与张量网络方法，涵盖训练、推理、压缩与可解释性
2. [Debias-SparseGPT: Bias-Aware Pruning for Large Language Models](/202609/06/2609.02496v1-debias-sparsegpt-bias-aware-pruning-for-large-language-models)  
   标签：评分：9.0/10、query:llm
   evidence：面向LLM高效部署的偏置感知剪枝压缩方法
3. [Evaluating Criterion-Conditioned Behaviour of Large Language Models in Content Moderation](/202609/06/2609.03814v1-evaluating-criterion-conditioned-behaviour-of-large-language-models-in-content-moderation)  
   标签：评分：9.0/10、query:llm
   evidence：DECO基准用于诊断大模型在内容审核中是否按单个准则做判断
4. [Quantifying Error Tolerance in Synthetic Data: An Atomic-level Operand vs. Operator Perturbation Study](/202609/06/2608.29144v1-quantifying-error-tolerance-in-synthetic-data-an-atomic-level-operand-vs-operator-perturbation-study)  
   标签：评分：8.0/10、query:llm-synth
   evidence：量化LLM训练合成数据错误容忍度的原子级框架
5. [AgentLogs: A Dataset for Opening the Black Box of GitHub's Cloud Agent](/202609/06/2608.29204v1-agentlogs-a-dataset-for-opening-the-black-box-of-githubs-cloud-agent)  
   标签：评分：8.0/10、query:agent
   evidence：AgentLogs提供GitHub上Copilot云智能体大规模行动数据，含30.7万任务与54.9万会话，与自主智能体系统研究直接相关
6. [When to Adapt: Conditional Memory Adapters for Retention-Preserving Domain Specialization](/202609/06/2608.29327v1-when-to-adapt-conditional-memory-adapters-for-retention-preserving-domain-specialization)  
   标签：评分：8.0/10、query:llm
   evidence：面向LLM领域特化微调的条件记忆适配器以保持通用能力
7. [AgenticRag-R1: Agentic Reinforcement Learning with Stack Memory for Multi-Step Reasoning, Retrieval and Memorizing](/202609/06/2608.29622v1-agenticrag-r1-agentic-reinforcement-learning-with-stack-memory-for-multi-step-reasoning-retrieval-and-memorizing)  
   标签：评分：8.0/10、query:agent
   evidence：提出记忆栈与细粒度动作空间的智能体强化学习RAG框架，贴合Agent综合主题
8. [PRACTICE: From Experience to Expertise in Self-Evolving Embodied Agents](/202609/06/2608.30760v1-practice-from-experience-to-expertise-in-self-evolving-embodied-agents)  
   标签：评分：8.0/10、query:agent
   evidence：具身智能体自我进化与持久技能库
9. [CA-OPD: Confidence-Aware On-Policy Distillation for Structured Visual Prediction](/202609/06/2609.02401v1-ca-opd-confidence-aware-on-policy-distillation-for-structured-visual-prediction)  
   标签：评分：8.0/10、query:post-train
   evidence：置信度感知的在线蒸馏方法，直接对应on-policy蒸馏训练方法
10. [Cliff: Learning Process Rewards from the First Mistake](/202609/06/2609.02817v1-cliff-learning-process-rewards-from-the-first-mistake)  
   标签：评分：8.0/10、query:post-train
   evidence：面向大语言模型强化学习后训练的奖励塑形策略

### 速读区论文标签
1. [Call Neighbours Yourself: Graph Walks with Destination-Conditioned On-Policy Self-Distillation](/202609/06/2608.29588v1-call-neighbours-yourself-graph-walks-with-destination-conditioned-on-policy-self-distillation)  
   标签：评分：8.0/10、query:post-train
   evidence：提出目标条件在线自蒸馏方法，用在线策略自蒸馏训练大模型的交互动作决策
2. [HiVe: Beyond Static Prompts for Multitask Learning via Hierarchy-based Vertical Mixture-of-Experts](/202609/06/2608.29790v2-hive-beyond-static-prompts-for-multitask-learning-via-hierarchy-based-vertical-mixture-of-experts)  
   标签：评分：8.0/10、query:llm
   evidence：用层级垂直混合专家实现输入自适应提示组合，属于大模型参数高效微调方法
3. [GenRubric: Self-Evolving Rubric Generation for Scalable LLM Evaluation](/202609/06/2608.29856v1-genrubric-self-evolving-rubric-generation-for-scalable-llm-evaluation)  
   标签：评分：8.0/10、query:llm
   evidence：面向大语言模型评测研究，提出自演化评分标准生成框架，属于评测方法的重要进展
4. [DataFoundry: Evolving Data Preparators via Recursive Self-Improvement](/202609/06/2608.29966v1-datafoundry-evolving-data-preparators-via-recursive-self-improvement)  
   标签：评分：8.0/10、query:llm-synth
   evidence：通过递归自我改进演化数据制备器，用于构建LLM领域适配所需的高质量训练数据
5. [CAST: Critique-Aware Supervision for Training Reliable Long-Horizon Tool-Calling Agents](/202609/06/2608.30147v1-cast-critique-aware-supervision-for-training-reliable-long-horizon-tool-calling-agents)  
   标签：评分：8.0/10、query:agent
   evidence：面向长时程工具调用智能体的可靠性训练，提出批评感知监督方法，属于自主智能体系统研究
6. [EDGE: Engine for Deterministic Graph Evaluation through Conversation Simulation from Graph Structured DSL Configuration](/202609/06/2608.29971v1-edge-engine-for-deterministic-graph-evaluation-through-conversation-simulation-from-graph-structured-dsl-configuration)  
   标签：评分：7.0/10、query:agent
   evidence：面向多智能体编排工作流，提出AgentGraph DSL与图遍历的确定性对话评测框架，属智能体评测/框架设计类工作。
7. [Beyond Uncertainty: Multi-Solver Disagreement Rewards for Self-Evolving Reasoning Curricula](/202609/06/2608.30035v1-beyond-uncertainty-multi-solver-disagreement-rewards-for-self-evolving-reasoning-curricula)  
   标签：评分：7.0/10、query:llm-synth
   evidence：通过挑战者模型生成合成问题，构建无人工数据的自进化课程
8. [Learning to Reason and Use Tools through Unsupervised Fine-Tuning in Task-Oriented Dialog Systems](/202609/06/2608.30426v1-learning-to-reason-and-use-tools-through-unsupervised-fine-tuning-in-task-oriented-dialog-systems)  
   标签：评分：7.0/10、query:llm-synth
   evidence：利用ICL推理生成推理轨迹、经LLM裁判过滤后微调对话模型，再用自改进循环自我增强，属于自训练/合成数据式后训练方法。
9. [Enhancing Low-Resource Language Reasoning via High-Resource Language Feature Transfer](/202609/06/2608.30462v1-enhancing-low-resource-language-reasoning-via-high-resource-language-feature-transfer)  
   标签：评分：7.0/10、query:llm
   evidence：面向低资源语言推理增强的LLM机制性干预与稀疏特征迁移
10. [TrainSDC: Characterizing and Mitigating Silent Data Corruption in Large Language Model Training](/202609/06/2608.30769v1-trainsdc-characterizing-and-mitigating-silent-data-corruption-in-large-language-model-training)  
   标签：评分：7.0/10、query:llm
   evidence：大模型训练中静默数据损坏的刻画与缓解研究
11. [Stratified Consistency Distillation for Natural Language Formalization](/202609/06/2608.30258v1-stratified-consistency-distillation-for-natural-language-formalization)  
   标签：评分：6.0/10、query:post-train
   evidence：基于微调的分层一致性蒸馏，用于LLM形式化任务训练
12. [PRO-Step: Step-level Process Reward Optimization for Retrieval-Augmented Generation](/202609/06/2609.01658v1-pro-step-step-level-process-reward-optimization-for-retrieval-augmented-generation)  
   标签：评分：6.0/10、query:post-train
   evidence：训练生成式过程奖励模型提供步骤级监督，可用于奖励模型训练与RLHF相关研究
13. [Task-Level Natural Language Priors as Learning Signals for Low-Resource LLM Training](/202609/06/2609.02244v1-task-level-natural-language-priors-as-learning-signals-for-low-resource-llm-training)  
   标签：评分：6.0/10、query:llm
   evidence：面向低资源LLM训练提出以自然语言先验作为辅助学习信号的训练方法
14. [CoMerge: Conflict-Driven Preference Optimization for Multi-Task Model Merging](/202609/06/2609.02273v1-comerge-conflict-driven-preference-optimization-for-multi-task-model-merging)  
   标签：评分：6.0/10、query:llm
   evidence：提出CoMerge冲突驱动偏好优化框架，将模型合并用于高效构建多任务LLM，属于LLM构建训练技术
15. [Towards a Statistical Understanding of Mixture-of-Experts](/202609/06/2609.03501v1-towards-a-statistical-understanding-of-mixture-of-experts)  
   标签：评分：6.0/10、query:llm
   evidence：对MoE稀疏专家架构中的路由与激活等设计进行统计理论分析，与大模型架构主题相关。


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
