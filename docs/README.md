<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-10
- 运行时间：2026-08-10 22:05:01 UTC
- 运行状态：成功
- 本次总论文数：29
- 精读区：14
- 速读区：15

### 今日简报（AI）
今日精读14篇、速读15篇，共梳理29篇论文，重点关注图引导搜索与策略滞后优化两大方向。  
最值得看的是《G-ReAct》的结构-状态协同进化搜索，以及《Reusing Rollouts》的前缀归一化策略优化，分别对复杂推理与LLM强化学习效率提升有明确启发。  
顺带关注速读中的KV Cache压缩、罕见病医疗辅助与推理调度能耗研究，适合作为下一步扩展阅读。
- 详情：[/202608/10/README](/202608/10/README)

### 精读区论文标签
1. [G-ReAct: Graph-Guided Deep Search via Structure-State Co-Evolution](/202608/10/2608.01324v1-g-react-graph-guided-deep-search-via-structure-state-co-evolution)  
   标签：评分：9.0/10、query:agent
   evidence：面向LLM智能体的图引导深度搜索框架
2. [Reusing Rollouts under Policy Lag: Prefix-Normalized Policy Optimization for LLM Reinforcement Learning](/202608/10/2608.01418v1-reusing-rollouts-under-policy-lag-prefix-normalized-policy-optimization-for-llm-reinforcement-learning)  
   标签：评分：9.0/10、query:post-train
   evidence：用于LLM后训练的强化学习方法，复用rollout
3. [Training Small LLMs as Spatial Multi-Agent Policies](/202608/10/2608.01425v1-training-small-llms-as-spatial-multi-agent-policies)  
   标签：评分：9.0/10、query:agent
   evidence：将小规模LLM训练为空间多智能体策略，是多智能体系统核心研究
4. [Look Ahead Before You Distill: Future Trajectory Validation of Teacher Guidance for Agentic On-Policy Distillation](/202608/10/2608.01953v2-look-ahead-before-you-distill-future-trajectory-validation-of-teacher-guidance-for-agentic-on-policy-distillation)  
   标签：评分：9.0/10、query:post-train
   evidence：面向智能体任务的在线蒸馏方法
5. [Evaluating LLMs in Database Scenarios: A Lifecycle Benchmark for Assessing Their Potential in Core Database Tasks](/202608/10/2608.03794v1-evaluating-llms-in-database-scenarios-a-lifecycle-benchmark-for-assessing-their-potential-in-core-database-tasks)  
   标签：评分：9.0/10、query:llm
   evidence：面向数据库任务的LLM生命周期评测基准
6. [Training-Free Hashing-Based Attention via Binary Principal Components](/202608/10/2608.04405v1-training-free-hashing-based-attention-via-binary-principal-components)  
   标签：评分：9.0/10、query:llm
   evidence：面向长上下文LLM推理的无训练哈希稀疏注意力
7. [MemoryCPT: An End-to-End Agent Memory Framework for Cost-Performance Trade-off](/202608/10/2608.04843v1-memorycpt-an-end-to-end-agent-memory-framework-for-cost-performance-trade-off)  
   标签：评分：9.0/10、query:agent
   evidence：面向长程LLM智能体的端到端内存框架
8. [PRISM: Priority-aware Rubric Internalization via Structured Multimodal Data Synthesis](/202608/10/2608.05249v2-prism-priority-aware-rubric-internalization-via-structured-multimodal-data-synthesis)  
   标签：评分：9.0/10、query:llm-synth
   evidence：面向指令微调的结构化多模态数据合成框架
9. [ADIAS: Automated Design of Interactive Agentic Systems](/202608/10/2608.06410v1-adias-automated-design-of-interactive-agentic-systems)  
   标签：评分：9.0/10、query:agent
   evidence：自动化智能体设计，以持久问题状态指导迭代修订
10. [The Optimizer Is the Agent: Reasoning-Driven Search across Prompts, Programs, and ML Workflows](/202608/10/2608.06714v1-the-optimizer-is-the-agent-reasoning-driven-search-across-prompts-programs-and-ml-workflows)  
   标签：评分：9.0/10、query:agent
   evidence：面向提示、程序与ML工作流的统一智能体框架，用于推理驱动优化
11. [ReQuant: Fixed-Grid Discrete Refinement for Post-Training Quantization](/202608/10/2608.07019v1-requant-fixed-grid-discrete-refinement-for-post-training-quantization)  
   标签：评分：9.0/10、query:llm
   evidence：针对大语言模型后训练量化，降低推理显存与计算开销
12. [RoRA: Role-Oriented Regional Allocation for Visual Token Pruning in MLLMs](/202608/10/2608.07088v1-rora-role-oriented-regional-allocation-for-visual-token-pruning-in-mllms)  
   标签：评分：9.0/10、query:llm
   evidence：通过视觉token剪枝降低多模态大模型的预填充与KV缓存开销
13. [Agent Memory Distillation: Empowering Small LLM Agents with Hierarchical Teacher Memory](/202608/10/2608.07169v1-agent-memory-distillation-empowering-small-llm-agents-with-hierarchical-teacher-memory)  
   标签：评分：9.0/10、query:agent
   evidence：面向小型LLM代理的代理记忆蒸馏
14. [Fisher-R1: Training LLM Agents for Reliable Hypothesis Testing](/202608/10/2608.07437v1-fisher-r1-training-llm-agents-for-reliable-hypothesis-testing)  
   标签：评分：9.0/10、query:agent
   evidence：训练LLM智能体进行可靠的科学假设检验

### 速读区论文标签
1. [Practical Online KV Cache Compaction for LLM Agents: An Empirical Study](/202608/10/2608.00902v1-practical-online-kv-cache-compaction-for-llm-agents-an-empirical-study)  
   标签：评分：8.0/10、query:llm
   evidence：面向LLM智能体的在线KV缓存压缩，实现高效推理
2. [MedUPS: Towards Diagnostic Assistance in Uncommon Medical Cases with Large Language Models](/202608/10/2608.01012v1-medups-towards-diagnostic-assistance-in-uncommon-medical-cases-with-large-language-models)  
   标签：评分：8.0/10、query:post-train
   evidence：提出监督中间临床决策的LLM对齐框架
3. [Smoothing the Ramp, Not the Peak: Scheduling-Induced Power Dynamics of LLM Inference and Their Grid-Scale Consequences](/202608/10/2608.01250v1-smoothing-the-ramp-not-the-peak-scheduling-induced-power-dynamics-of-llm-inference-and-their-grid-scale-consequences)  
   标签：评分：8.0/10、query:llm
   evidence：分析大语言模型推理调度对功耗动态与电网的影响
4. [Prompt-Induced Waste in Large Reasoning Models: A Preregistered Two-Harness Benchmark of Coding Agents](/202608/10/2608.01347v1-prompt-induced-waste-in-large-reasoning-models-a-preregistered-two-harness-benchmark-of-coding-agents)  
   标签：评分：8.0/10、query:agent
   evidence：关于编码智能体提示词引发推理成本浪费的基准研究
5. [Long-Horizon Embodied Decision-Making via Multimodal Memory Compression](/202608/10/2608.01456v1-long-horizon-embodied-decision-making-via-multimodal-memory-compression)  
   标签：评分：8.0/10、query:agent
   evidence：面向自主具身决策智能体的基准
6. [Beyond Routing Saturation: A Long-Horizon Class-Incremental Perspective on Expert Routing in Multimodal Continual Instruction Tuning](/202608/10/2608.01437v1-beyond-routing-saturation-a-long-horizon-class-incremental-perspective-on-expert-routing-in-multimodal-continual-instruction-tuning)  
   标签：评分：7.0/10、query:llm
   evidence：针对多模态持续指令微调引入长视界专家路由评测基准FLEX
7. [LAB-Tab: LLM-Augmented Bayesian Network Adaptation for Few-Shot Tabular Generation](/202608/10/2608.01879v1-lab-tab-llm-augmented-bayesian-network-adaptation-for-few-shot-tabular-generation)  
   标签：评分：7.0/10、query:llm-synth
   evidence：利用LLM增强贝叶斯网络自适应以生成少量样本表格数据
8. [Training-Free versus Training-Based Intent Classification in LLMs: Accuracy, Robustness, and Failure Modes](/202608/10/2608.02415v1-training-free-versus-training-based-intent-classification-in-llms-accuracy-robustness-and-failure-modes)  
   标签：评分：7.0/10、query:llm
   evidence：面向领域专用LLM路由的意图分类方法系统对比
9. [PAMT: Process-Aligned Reinforcement Learning for Multi-Domain Machine Translation](/202608/10/2608.03077v1-pamt-process-aligned-reinforcement-learning-for-multi-domain-machine-translation)  
   标签：评分：7.0/10、query:post-train
   evidence：面向LLM后训练的过程对齐强化学习
10. [Attacking and Defending Multi-Agent Collaborative Filtering Systems Through Connectivity](/202608/10/2608.03272v1-attacking-and-defending-multi-agent-collaborative-filtering-systems-through-connectivity)  
   标签：评分：7.0/10、query:agent
   evidence：针对由自主LLM驱动的多智能体协同过滤系统的攻击与防御分析
11. [Who Belongs in the Eval Set? A Capability-Taxonomy-Driven Pipeline for Curating Regression Eval Sets in Agent-Extensibility Platforms](/202608/10/2608.01004v1-who-belongs-in-the-eval-set-a-capability-taxonomy-driven-pipeline-for-curating-regression-eval-sets-in-agent-extensibility-platforms)  
   标签：评分：6.0/10、query:agent
   evidence：面向智能体扩展平台的回归评测集筛选，基于能力分类学
12. [SG-Layout: Structured Scene Graph-Guided Layout Generation with LLMs](/202608/10/2608.01106v1-sg-layout-structured-scene-graph-guided-layout-generation-with-llms)  
   标签：评分：6.0/10、query:llm
   evidence：采用含LoRA适配器的两阶段指令微调框架，针对布局生成任务微调LLM
13. [ACE-GraphRAG: Agentic Context Engineering for Hierarchical GraphRAG](/202608/10/2608.01269v2-ace-graphrag-agentic-context-engineering-for-hierarchical-graphrag)  
   标签：评分：6.0/10、query:agent
   evidence：为检索增强生成框架设计智能体式上下文策略层
14. [Interpreting Black-Box Large Language Models with Sentence-Level Energy Landscapes](/202608/10/2608.02879v1-interpreting-black-box-large-language-models-with-sentence-level-energy-landscapes)  
   标签：评分：6.0/10、query:llm
   evidence：使用能量模型代理对黑盒LLM进行句子级归因解释
15. [Predicting Multilingual Classification and Translation Performance of LLMs with Cross-Lingual Alignment $\unicode{x2013}$ Is English Enough?](/202608/10/2608.03446v1-predicting-multilingual-classification-and-translation-performance-of-llms-with-cross-lingual-alignment-unicodex2013-is-english-enough)  
   标签：评分：6.0/10、query:llm
   evidence：对比27种跨语言对齐分数以预测LLM下游性能


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
