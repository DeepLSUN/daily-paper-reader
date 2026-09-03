<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-03
- 运行时间：2026-09-03 23:50:36 UTC
- 运行状态：成功
- 本次总论文数：25
- 精读区：10
- 速读区：15

### 今日简报（AI）
今日精读聚焦多智能体系统级联故障归因与采样令牌在线蒸馏，两篇均获9.0高分；速读覆盖多模态指令数据自进化、流匹配自蒸馏及少轨迹训练优化。最值得关注的方向是“先检测后归因”的故障定位方法，以及解决多样性瓶颈的蒸馏策略——它们直接影响Agent可靠性与大模型训练效率。建议普通读者优先精读这两篇9分论文，理解多智能体鲁棒性与蒸馏最新突破口。
- 详情：[/202609/03/README](/202609/03/README)

### 精读区论文标签
1. [Detect Before You Attribute: Cascade Failure Attribution for Multi-Agent Systems](/202609/03/2608.29646v1-detect-before-you-attribute-cascade-failure-attribution-for-multi-agent-systems)  
   标签：评分：9.0/10、query:agent
   evidence：面向多智能体系统的级联失败归因方法，属于自主智能体可靠性研究方向
2. [Influence-Directed Distillation: Solving the Diversity Bottleneck in Sampled-Token On-Policy Distillation](/202609/03/2608.29846v1-influence-directed-distillation-solving-the-diversity-bottleneck-in-sampled-token-on-policy-distillation)  
   标签：评分：9.0/10、query:post-train
   evidence：针对采样令牌在线蒸馏提出方法改进，解决多样性蒸馏失败问题
3. [TopoCompress: Long Context Compression via Graph-Wired Semantic Trajectories](/202609/03/2608.30811v2-topocompress-long-context-compression-via-graph-wired-semantic-trajectories)  
   标签：评分：9.0/10、query:llm
   evidence：直接面向LLM长上下文推理压缩，提出免训练且模型无关的方法以降低推理开销与延迟。
4. [Towards Agentic Cloud Engineering: Graph and Loop Engineering with a Zero-Trust Agent Harness](/202609/03/2609.00050v1-towards-agentic-cloud-engineering-graph-and-loop-engineering-with-a-zero-trust-agent-harness)  
   标签：评分：9.0/10、query:agent
   evidence：提出自主云工作流智能体框架，直接匹配智能体框架设计
5. [DynaNDE: Dynamic Near-Data Expert Scheduling for Batched MoE Inference](/202609/03/2609.00407v1-dynande-dynamic-near-data-expert-scheduling-for-batched-moe-inference)  
   标签：评分：9.0/10、query:llm
   evidence：面向MoE大模型批处理推理的NPU近数据动态专家调度框架
6. [Patterning in Practice: Debiasing Reward Models with Susceptibilities](/202609/03/2609.00699v1-patterning-in-practice-debiasing-reward-models-with-susceptibilities)  
   标签：评分：9.0/10、query:post-train
   evidence：对偏好数据训练的奖励模型进行去偏，是奖励模型训练侧的重要方法
7. [On-Policy Distillation Meets Off-Policy GRPO: Training Compact Instruction-Following Rerankers](/202609/03/2609.01947v1-on-policy-distillation-meets-off-policy-grpo-training-compact-instruction-following-rerankers)  
   标签：评分：9.0/10、query:post-train
   evidence：将off-policy GRPO教师优化与on-policy学生蒸馏结合用于语言模型训练
8. [When Tool Outputs Become Commands: Separating Action Induction from Runtime Authorization in Tool-Augmented LLM Agents](/202609/03/2608.27146v1-when-tool-outputs-become-commands-separating-action-induction-from-runtime-authorization-in-tool-augmented-llm-agents)  
   标签：评分：8.0/10、query:agent
   evidence：面向工具增强型LLM智能体的安全框架，分离动作归纳与执行授权
9. [Parser States Already Know: Structure-Conditioned KV Persistence for Structured Generation](/202609/03/2608.28276v1-parser-states-already-know-structure-conditioned-kv-persistence-for-structured-generation)  
   标签：评分：8.0/10、query:llm
   evidence：面向结构化生成推断的KV持久化优化
10. [Legacy System Modernization with Coding Agents: A Case Study](/202609/03/2608.28972v1-legacy-system-modernization-with-coding-agents-a-case-study)  
   标签：评分：8.0/10、query:agent
   evidence：编码智能体用于遗留系统迁移的工业案例研究

### 速读区论文标签
1. [VISA: Agentic Self-Evolving Data Synthesis for Multimodal Instruction Following](/202609/03/2608.26013v1-visa-agentic-self-evolving-data-synthesis-for-multimodal-instruction-following)  
   标签：评分：8.0/10、query:llm-synth
   evidence：数据合成在指令跟随训练中的应用
2. [Self-OPD: On-Policy Distillation for Flow Matching Models without Teacher](/202609/03/2608.26872v1-self-opd-on-policy-distillation-for-flow-matching-models-without-teacher)  
   标签：评分：8.0/10、query:post-train
   evidence：Self-OPD是无教师在线策略蒸馏方法，源于LLM中OPD的成功，将学生模型自探索转为逐步监督。
3. [SWE-Prime: Fewer Trajectories, Better Performance](/202609/03/2608.27449v1-swe-prime-fewer-trajectories-better-performance)  
   标签：评分：8.0/10、query:post-train
   evidence：面向代码智能体轨迹的多粒度SFT数据选择
4. [Credo: Reusable Declarative Primitives for Agentic Workflows](/202609/03/2608.27790v1-credo-reusable-declarative-primitives-for-agentic-workflows)  
   标签：评分：8.0/10、query:agent
   evidence：智能体工作流与框架设计
5. [SpikeOPD: Stable On-Policy Distillation for Autoregressive Spiking Language Models](/202609/03/2608.27857v1-spikeopd-stable-on-policy-distillation-for-autoregressive-spiking-language-models)  
   标签：评分：8.0/10、query:post-train
   evidence：面向自回归脉冲语言模型的稳定在线策略蒸馏方法
6. [CoCoBench: A Cooperative Coordination Benchmark for Embodied Multi-Agent Task Planning](/202609/03/2608.28266v1-cocobench-a-cooperative-coordination-benchmark-for-embodied-multi-agent-task-planning)  
   标签：评分：7.0/10、query:agent
   evidence：面向具身多智能体协同协作的构造级评测基准CoCoBench
7. [Memory-First Fact-Checking: A Knowledge-Graph-Grounded Multi-Agent System for Misinformation Detection](/202609/03/2608.29617v1-memory-first-fact-checking-a-knowledge-graph-grounded-multi-agent-system-for-misinformation-detection)  
   标签：评分：7.0/10、query:agent
   evidence：结合知识图谱与对抗多智能体推理的事实核查自治系统
8. [Evaluating a 4B open-weights local LLM for agentic DFT workflows: a literature reproducibility audit](/202609/03/2608.29665v1-evaluating-a-4b-open-weights-local-llm-for-agentic-dft-workflows-a-literature-reproducibility-audit)  
   标签：评分：7.0/10、query:agent
   evidence：评测本地LLM执行自主DFT智能体流程，直接对应自主智能体系统研究
9. [Diachronic Hypergraphs for Orchestrated Multi-Agent Multimodal Memory Curation](/202609/03/2608.29678v1-diachronic-hypergraphs-for-orchestrated-multi-agent-multimodal-memory-curation)  
   标签：评分：7.0/10、query:agent
   evidence：面向多智能体编排的超图多模态记忆框架
10. [HiVe: Beyond Static Prompts for Multitask Learning via Hierarchy-based Vertical Mixture-of-Experts](/202609/03/2608.29790v1-hive-beyond-static-prompts-for-multitask-learning-via-hierarchy-based-vertical-mixture-of-experts)  
   标签：评分：7.0/10、query:llm
   evidence：面向大模型参数高效微调的自适应提示层级与垂直专家混合方法
11. [Perceive to Hypothesize, Verify to Ground: An Agentic Reasoning Framework for Open-World Geo-Localization](/202609/03/2608.29880v1-perceive-to-hypothesize-verify-to-ground-an-agentic-reasoning-framework-for-open-world-geo-localization)  
   标签：评分：6.0/10、query:agent
   evidence：面向开放世界地理定位的智能体推理框架，属于Agent框架设计的应用实例
12. [On the Recoverability of Private Information Unlearning in Large Language Models](/202609/03/2608.29943v1-on-the-recoverability-of-private-information-unlearning-in-large-language-models)  
   标签：评分：6.0/10、query:llm
   evidence：构建合成隐私数据集和白盒审计框架，系统评测大模型遗忘效果，与LLM评测基准相关。
13. [E-SENS: Exclusion-Sensitive Penalization for Negative-Constraint Retrieval](/202609/03/2608.30130v1-e-sens-exclusion-sensitive-penalization-for-negative-constraint-retrieval)  
   标签：评分：6.0/10、query:agent
   evidence：面向RAG的否定敏感检索重排，与搜索智能体的文档检索技术相关。
14. [Can LLMs Use Relational Transformer Embeddings?](/202609/03/2609.00457v1-can-llms-use-relational-transformer-embeddings)  
   标签：评分：6.0/10、query:llm
   evidence：通过LoRA监督微调与组式强化学习微调LLM以融合关系嵌入
15. [Do Large Language Models Capture the Diversity in their Training Data?](/202609/03/2609.02275v1-do-large-language-models-capture-the-diversity-in-their-training-data)  
   标签：评分：6.0/10、query:llm
   evidence：用条件熵比较LLM输出与训练数据的多样性，为LLM评测提供信息论视角。


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
