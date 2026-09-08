<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-08
- 运行时间：2026-09-08 23:23:04 UTC
- 运行状态：成功
- 本次总论文数：25
- 精读区：10
- 速读区：15

### 今日简报（AI）
今日精读10篇、速读15篇，共25篇AI论文，焦点落在知识图谱问答与模型注意力机制。  
最值得看的两篇9分工作：KGVoyager用智能体导航攻克知识图谱问答，另一篇让语言模型自主控制自身注意力。  
建议优先深读这两篇9分论文，再顺带浏览速读中三篇8分工作如关键点路由与分层一致性蒸馏。
- 详情：[/202609/08/README](/202609/08/README)

### 精读区论文标签
1. [KGVoyager: Knowledge Graph Agnostic Question Answering via Agentic Navigation](/202609/08/2609.01780v1-kgvoyager-knowledge-graph-agnostic-question-answering-via-agentic-navigation)  
   标签：评分：9.0/10、query:agent
   evidence：提出KGVoyager智能体架构，使用搜索探索执行工具完成图谱导航，是对智能体框架设计的直接贡献
2. [Language Models Can Control Their Own Attention](/202609/08/2609.02737v1-language-models-can-control-their-own-attention)  
   标签：评分：9.0/10、query:llm
   evidence：提出声明式注意力协议控制注意力范围以减少KV缓存读取，直接面向大语言模型推理优化。
3. [MaxKernel: Agentic Kernel Generation for TPUs](/202609/08/2609.04523v1-maxkernel-agentic-kernel-generation-for-tpus)  
   标签：评分：9.0/10、query:agent
   evidence：多智能体LLM系统生成TPU内核并结合编译器反馈优化，是强相关的编码智能体研究
4. [Persistent Teacher Anchoring for Tool-Using Agents](/202609/08/2609.04773v1-persistent-teacher-anchoring-for-tool-using-agents)  
   标签：评分：9.0/10、query:post-train
   evidence：提出持久教师锚定方法以稳定工具使用智能体的在线策略知识蒸馏
5. [ACE: Adaptive Calibration-Free Expert Skipping for MoE-based LLMs](/202609/08/2609.05228v1-ace-adaptive-calibration-free-expert-skipping-for-moe-based-llms)  
   标签：评分：9.0/10、query:llm
   evidence：针对MoE大模型推理效率的免训练自适应专家跳过方法
6. [Beyond Context Windows: Persistent Discovery Context for Data-Centric Agents](/202609/08/2609.02129v1-beyond-context-windows-persistent-discovery-context-for-data-centric-agents)  
   标签：评分：8.0/10、query:agent
   evidence：数据智能体的持久发现记忆层，复用历史检索结果以提升自主智能体发现能力
7. [DoPR: Reusable Compressed Document Prefixes for Efficient LLM Reranking](/202609/08/2609.03311v1-dopr-reusable-compressed-document-prefixes-for-efficient-llm-reranking)  
   标签：评分：8.0/10、query:llm
   evidence：利用可复用压缩文档前缀与离线在线解耦实现高效LLM重排序
8. [Value-Preserving Architectures for Agentic AI Systems](/202609/08/2609.03920v1-value-preserving-architectures-for-agentic-ai-systems)  
   标签：评分：8.0/10、query:agent
   evidence：智能体AI系统与多智能体架构设计的价值保持研究
9. [Representational alignment yields generalizable safety in language models](/202609/08/2609.04022v1-representational-alignment-yields-generalizable-safety-in-language-models)  
   标签：评分：8.0/10、query:post-train
   evidence：提出基于原型理论与表征对齐的语言模型安全对齐方法。
10. [DCFA: Dual-view Causal-inspired Attribution for Failure Reasoning in LLM-based Multi-agent Systems](/202609/08/2609.04749v1-dcfa-dual-view-causal-inspired-attribution-for-failure-reasoning-in-llm-based-multi-agent-systems)  
   标签：评分：8.0/10、query:agent
   evidence：针对LLM多智能体系统的失败归因与因果推理，切中智能体系统主题

### 速读区论文标签
1. [CPR for LLMs: Critical-Point Routing against Catastrophic Forgetting in Domain Adaptation](/202609/08/2608.30158v1-cpr-for-llms-critical-point-routing-against-catastrophic-forgetting-in-domain-adaptation)  
   标签：评分：8.0/10、query:post-train
   evidence：针对监督微调中灾难性遗忘问题，提出词元级关键点路由与SFT专家调用方案。
2. [Stratified Consistency Distillation for Natural Language Formalization](/202609/08/2608.30258v1-stratified-consistency-distillation-for-natural-language-formalization)  
   标签：评分：8.0/10、query:llm-synth
   evidence：用前沿大模型生成多条逻辑翻译并基于一致性筛选伪标签，是LLM合成数据方法
3. [Efficient Test-Time Adaptation through Human-AI Interaction](/202609/08/2609.04141v1-efficient-test-time-adaptation-through-human-ai-interaction)  
   标签：评分：8.0/10、query:agent
   evidence：研究AI智能体如何通过迭代人机交互实现个性化测试时自适应，符合通用智能体研究方向
4. [Knowledge Acquisition During Pre-training? Large Language Models Learn Better With Auxiliary Views](/202609/08/2609.04180v1-knowledge-acquisition-during-pre-training-large-language-models-learn-better-with-auxiliary-views)  
   标签：评分：8.0/10、query:llm
   evidence：通过受控预训练实验证明辅助知识视角能促进大模型知识习得，为如何有效训练大模型提供实证依据。
5. [LentEx: Generalizable Latent Entity Extraction via Synthetic Data and Instruction-Tuned LLMs](/202609/08/2609.04511v1-lentex-generalizable-latent-entity-extraction-via-synthetic-data-and-instruction-tuned-llms)  
   标签：评分：8.0/10、query:llm-synth
   evidence：模板合成数据配合指令微调应用于潜在实体抽取，符合数据合成用于指令微调的应用场景
6. [A Cost-Aware Agentic Architecture for NL-to-SQL over Nested Enterprise Schemas, with a New Benchmark](/202609/08/2609.04641v1-a-cost-aware-agentic-architecture-for-nl-to-sql-over-nested-enterprise-schemas-with-a-new-benchmark)  
   标签：评分：8.0/10、query:agent
   evidence：提出成本感知的单次生成智能体架构，面向嵌套企业模式的NL2SQL，并配套新基准与语义深度评分。
7. [SQL-Zero: Self-Evolving Text-to-SQL](/202609/08/2609.04697v1-sql-zero-self-evolving-text-to-sql)  
   标签：评分：8.0/10、query:llm-synth
   evidence：用自生成的SQL数据和GRPO进行自训练
8. [Refuse without Refusal: A Structural Analysis of Safety-Tuning Responses for Reducing False Refusals in Language Models](/202609/08/2609.04714v1-refuse-without-refusal-a-structural-analysis-of-safety-tuning-responses-for-reducing-false-refusals-in-language-models)  
   标签：评分：8.0/10、query:post-train
   evidence：通过对安全微调回复做结构分析来降低虚假拒答，服务于大模型与人类偏好对齐
9. [Quit While You're Ahead: Quit for Efficient Candidate Generation in Machine Translation Reranking](/202609/08/2609.00588v2-quit-while-youre-ahead-quit-for-efficient-candidate-generation-in-machine-translation-reranking)  
   标签：评分：7.0/10、query:llm
   evidence：面向NMT重排序的候选生成早停策略，降低推理延迟
10. [It Takes Two to Match: Co-Evolving Generative Retriever with Reinforcement Learning](/202609/08/2609.00638v1-it-takes-two-to-match-co-evolving-generative-retriever-with-reinforcement-learning)  
   标签：评分：7.0/10、query:agent
   evidence：训练生成式LLM在查询端与条目端构造检索表示，是搜索智能体的使能方法
11. [Prompt-Robust Language Models: Which Training Strategies Work?](/202609/08/2609.01217v1-prompt-robust-language-models-which-training-strategies-work)  
   标签：评分：7.0/10、query:llm
   evidence：面向提示鲁棒性的微调训练策略对比研究
12. [Benchmarking Language Models for Statistical Problem Formulation](/202609/08/2609.01982v1-benchmarking-language-models-for-statistical-problem-formulation)  
   标签：评分：7.0/10、query:llm
   evidence：提出StatFormBench评测基准，用于评估大模型统计问题表述能力
13. [NE-R1: Enhancing Named Entity Recognition Model via Reinforcement Learning](/202609/08/2609.02366v1-ne-r1-enhancing-named-entity-recognition-model-via-reinforcement-learning)  
   标签：评分：7.0/10、query:post-train
   evidence：采用多任务指令微调初始化加端到端强化学习优化，训练按需检索的命名实体识别模型，属于LLM强化后训练方法。
14. [KanAdapter: A Kolmogorov-Arnold Network-based Plug-and-Play Module for Efficient Fine-tuning of Foundation Speech Models](/202609/08/2609.05281v1-kanadapter-a-kolmogorov-arnold-network-based-plug-and-play-module-for-efficient-fine-tuning-of-foundation-speech-models)  
   标签：评分：6.0/10、query:llm
   evidence：面向语音基础模型的KAN参数高效微调模块，适配器方法可迁移到LLM高效微调
15. [Trust-Aware Adaptive Disclosure for Inference Privacy Preservation in Multi-Agent Networks](/202609/08/2609.05340v1-trust-aware-adaptive-disclosure-for-inference-privacy-preservation-in-multi-agent-networks)  
   标签：评分：6.0/10、query:agent
   evidence：研究多智能体网络中带潜在目标的一致性隐私保护与推断攻击防御


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
