<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-02
- 运行时间：2026-09-03 00:04:57 UTC
- 运行状态：成功
- 本次总论文数：37
- 精读区：22
- 速读区：15

### 今日简报（AI）
今日扫描37篇论文，精读22篇，重点关注Agent与检索方向的高分工作。最值得看的是《ProRetrieval》用程序合成编排混合检索，以及《What Makes Good Agentic Data》提出ACE视角审视Agent数据生成，两者均获9分。建议普通读者优先精读这两篇，速读报告中另有三篇8分工作涉及多语言测试与跨语言表征可作延伸。
- 详情：[/202609/02/README](/202609/02/README)

### 精读区论文标签
1. [ProRetrieval: Learning to Orchestrate Hybrid Search via Executable Program Synthesis](/202609/02/2608.27017v1-proretrieval-learning-to-orchestrate-hybrid-search-via-executable-program-synthesis)  
   标签：评分：9.0/10、query:agent
   evidence：将语言模型变为检索编排智能体，执行混合搜索
2. [What Makes Good Agentic Data? An ACE Lens on Data Generation for LLM Agents](/202609/02/2608.27260v1-what-makes-good-agentic-data-an-ace-lens-on-data-generation-for-llm-agents)  
   标签：评分：9.0/10、query:llm-synth
   evidence：LLM智能体数据生成的ACE结构化框架，属于智能体训练用合成数据方法
3. [Resource Constraints and Performance in Agentic AI Systems](/202609/02/2608.27886v1-resource-constraints-and-performance-in-agentic-ai-systems)  
   标签：评分：9.0/10、query:agent
   evidence：在资源约束下对完整自主智能体系统进行对比评测
4. [Deriving Scaling Laws for OpenEuroLLM Models: Learning Rate, Batch Size and Loss](/202609/02/2608.28308v1-deriving-scaling-laws-for-openeurollm-models-learning-rate-batch-size-and-loss)  
   标签：评分：9.0/10、query:llm
   evidence：研究大模型预训练学习率和批大小的缩放规律与训练策略。
5. [Super Library Agent: Joint Generation and Maintenance of Multiple Applications Beyond the Single Codebase](/202609/02/2608.29310v1-super-library-agent-joint-generation-and-maintenance-of-multiple-applications-beyond-the-single-codebase)  
   标签：评分：9.0/10、query:agent
   evidence：LLM编程智能体联合生成与维护多个代码库并维护共享库，直接对应代码智能体研究
6. [Agent Zero Memory: Provenance-Aware Long-Term Memory for LLM Agents](/202609/02/2608.29606v1-agent-zero-memory-provenance-aware-long-term-memory-for-llm-agents)  
   标签：评分：9.0/10、query:agent
   evidence：面向LLM智能体的长期记忆系统设计，属于Agent架构与框架设计
7. [ACTD: Anchor-Based Cross-Tokenizer Distillation with Residual Regularization](/202609/02/2608.29662v1-actd-anchor-based-cross-tokenizer-distillation-with-residual-regularization)  
   标签：评分：9.0/10、query:post-train
   evidence：提出跨分词器知识蒸馏方法，将大模型推理能力迁移到轻量学生模型，符合LLM知识蒸馏压缩需求。
8. [Higher-Dimensional Rotary Position Embedding](/202609/02/2608.29715v1-higher-dimensional-rotary-position-embedding)  
   标签：评分：9.0/10、query:llm
   evidence：提出高维旋转位置编码作为Transformer架构改进，属于大语言模型架构设计相关研究
9. [Small Language Models as Judges for Rubric-Based Reinforcement Learning](/202609/02/2608.30005v1-small-language-models-as-judges-for-rubric-based-reinforcement-learning)  
   标签：评分：9.0/10、query:post-train
   evidence：用小型LM作准则式RL的评分评审，直接面向奖励模型构造与评测
10. [Agents in the Large: Perception-Centered Architecture for Persistent Agents](/202609/02/2608.30478v1-agents-in-the-large-perception-centered-architecture-for-persistent-agents)  
   标签：评分：9.0/10、query:agent
   evidence：为持久化AI智能体提出的概念性架构框架，属于Agent框架设计
11. [Evaluating and Improving LLM Self-Modeling](/202609/02/2608.30980v1-evaluating-and-improving-llm-self-modeling)  
   标签：评分：9.0/10、query:llm
   evidence：提出评估大模型自我建模能力的全新基准，符合大模型评测基准需求。
12. [Stick to What You Know: A Study of Knowledge-Aligned Supervised Fine-Tuning](/202609/02/2608.30987v1-stick-to-what-you-know-a-study-of-knowledge-aligned-supervised-fine-tuning)  
   标签：评分：9.0/10、query:post-train
   evidence：直接研究大语言模型监督微调，提出约束训练目标到基座模型参数化知识的知识对齐SFT方法。
13. [REAL-Q: E2E LLM Quantization via Dynamic Gradient Descent](/202609/02/2609.00049v1-real-q-e2e-llm-quantization-via-dynamic-gradient-descent)  
   标签：评分：9.0/10、query:llm
   evidence：后训练量化提升LLM部署效率，属于大模型推理优化方法
14. [Online Self-Weighted Fine-Tuning](/202609/02/2609.00734v1-online-self-weighted-fine-tuning)  
   标签：评分：9.0/10、query:post-train
   evidence：针对监督微调与强化学习的结合，提出在线自加权微调方法以动态调节每条轨迹的损失权重
15. [ContextPipe: Database-Inspired Context Assembly for Long-Horizon Agents](/202609/02/2609.00749v1-contextpipe-database-inspired-context-assembly-for-long-horizon-agents)  
   标签：评分：9.0/10、query:agent
   evidence：面向长时程LLM智能体的上下文组装框架
16. [Agent-Enhanced Heterogeneous Graph RAG for Academic Question Answering](/202609/02/2609.00761v1-agent-enhanced-heterogeneous-graph-rag-for-academic-question-answering)  
   标签：评分：9.0/10、query:agent
   evidence：显式的检索Agent将RAG流程阶段转化为智能体决策，属于搜索智能体研究
17. [HarnessEvolve: Learning from Reference Trajectories for Reliable Agent Self-Evolution](/202609/02/2609.00829v1-harnessevolve-learning-from-reference-trajectories-for-reliable-agent-self-evolution)  
   标签：评分：9.0/10、query:agent
   evidence：智能体自进化框架，从参考轨迹学习以稳定优化提示、技能、工具与执行逻辑
18. [CoBRA: Learning Tool-Use Boundaries via Counterfactual Margins](/202609/02/2609.00967v1-cobra-learning-tool-use-boundaries-via-counterfactual-margins)  
   标签：评分：9.0/10、query:agent
   evidence：面向智能体工具调用决策的反事实边界学习框架
19. [AgentFactory: Towards Automated Agentic System Design and Optimization](/202609/02/2609.01045v1-agentfactory-towards-automated-agentic-system-design-and-optimization)  
   标签：评分：9.0/10、query:agent
   evidence：提出AgentFactory自动化设计优化智能体系统，直接对应智能体框架设计需求
20. [From Rollouts to Recipes: Self-Contained Post-Training for LLMs](/202609/02/2609.01422v1-from-rollouts-to-recipes-self-contained-post-training-for-llms)  
   标签：评分：9.0/10、query:post-train
   evidence：按rollout行为路由至GRPO与自蒸馏的LLM后训练方法
21. [Efficiently Estimating Optimal Hyperparameter Scaling Laws through Power-Law Entropy Search](/202609/02/2609.01431v1-efficiently-estimating-optimal-hyperparameter-scaling-laws-through-power-law-entropy-search)  
   标签：评分：9.0/10、query:llm
   evidence：提出高效估计大模型训练最优超参数缩放规律的方法，降低调参成本。
22. [Scaling Near-Optimal SFT-RL Annotation Budget Allocation from Small to Large LLMs](/202609/02/2609.01573v1-scaling-near-optimal-sft-rl-annotation-budget-allocation-from-small-to-large-llms)  
   标签：评分：9.0/10、query:post-train
   evidence：研究LLM后训练中SFT与RL的标注预算分配比较与跨规模迁移

### 速读区论文标签
1. [XREPOTEST: Benchmarking Multilingual Repository-Level Unit Test Generation for Large Language Models](/202609/02/2608.25939v1-xrepotest-benchmarking-multilingual-repository-level-unit-test-generation-for-large-language-models)  
   标签：评分：8.0/10、query:llm
   evidence：面向LLM的多语言仓库级单元测试生成评测基准
2. [Cross-lingual Representation Learning via Centroid Intervention Fusion](/202609/02/2608.26357v1-cross-lingual-representation-learning-via-centroid-intervention-fusion)  
   标签：评分：8.0/10、query:llm
   evidence：通过推理时修改大模型隐状态提升跨语言迁移，属于大模型推理相关方法
3. [AI Control Scientist: LLM-driven Agentic System for Automated Control Design](/202609/02/2608.26780v1-ai-control-scientist-llm-driven-agentic-system-for-automated-control-design)  
   标签：评分：8.0/10、query:agent
   evidence：LLM驱动的多智能体系统用于自动化控制设计。
4. [GraphMemix: Query-Aware Evidence Forests for Long-Term Multimodal Agent Memory](/202609/02/2608.26983v1-graphmemix-query-aware-evidence-forests-for-long-term-multimodal-agent-memory)  
   标签：评分：8.0/10、query:agent
   evidence：面向多模态智能体的查询感知图记忆框架
5. [ASIL: Replacing Screenshot-and-Click with Structured State and Semantic Actions](/202609/02/2608.26991v1-asil-replacing-screenshot-and-click-with-structured-state-and-semantic-actions)  
   标签：评分：8.0/10、query:agent
   evidence：面向代码代理的智能体-软件交互层，提供结构化状态和语义操作
6. [When Memory Takes Gradients: Collaborative Vector Memory for Agentic Recommender Systems](/202609/02/2608.26895v1-when-memory-takes-gradients-collaborative-vector-memory-for-agentic-recommender-systems)  
   标签：评分：7.0/10、query:agent
   evidence：针对基于大模型的智能体推荐系统设计协作式向量记忆模块，直接涉及智能体框架中的记忆与决策设计
7. [CoCoBench: A Cooperative Coordination Benchmark for Embodied Multi-Agent Task Planning](/202609/02/2608.28266v1-cocobench-a-cooperative-coordination-benchmark-for-embodied-multi-agent-task-planning)  
   标签：评分：7.0/10、query:agent
   evidence：面向具身多智能体任务规划的协作协调基准，提供细粒度诊断
8. [AGENT-O: A Semantic Agent Card Framework for Interoperable and Governed Healthcare AI Agents](/202609/02/2608.28345v1-agent-o-a-semantic-agent-card-framework-for-interoperable-and-governed-healthcare-ai-agents)  
   标签：评分：7.0/10、query:agent
   evidence：提出语义Agent Card本体框架，直接对应智能体框架设计与表示规范主题。
9. [Agent2UCB: Agentic System for Generative Engine Optimization](/202609/02/2608.29063v1-agent2ucb-agentic-system-for-generative-engine-optimization)  
   标签：评分：7.0/10、query:agent
   evidence：自主优化内容可见度的智能体GEO系统，基于bandit策略选择
10. [JudgePanel: A Compact Judge with Panel Deliberation via Adaptive Multi-Reward Reinforcement Learning](/202609/02/2608.29168v1-judgepanel-a-compact-judge-with-panel-deliberation-via-adaptive-multi-reward-reinforcement-learning)  
   标签：评分：7.0/10、query:post-train
   evidence：用多智能体审议轨迹与自适应多奖励强化学习对LLM裁判进行后训练，提升其判断质量。
11. [Co-Evolving Structured Knowledge and Reasoning in Language Models](/202609/02/2608.26386v1-co-evolving-structured-knowledge-and-reasoning-in-language-models)  
   标签：评分：6.0/10、query:llm
   evidence：利用QA奖励联合训练知识库构建与推理，属于语言模型训练方法
12. [STAR : Sentence Translation Alignment Rate for Document-to-Document Machine Translation](/202609/02/2608.27161v1-star--sentence-translation-alignment-rate-for-document-to-document-machine-translation)  
   标签：评分：6.0/10、query:post-train
   evidence：面向文档级机器翻译的偏好优化方法，可迁移至LLM对齐后训练
13. [When Tokenizers Fail: Byte-Level Chunking for Zero-Shot Transfer to Low-Resource Languages](/202609/02/2608.27658v1-when-tokenizers-fail-byte-level-chunking-for-zero-shot-transfer-to-low-resource-languages)  
   标签：评分：6.0/10、query:llm
   evidence：提出字节级分块与适配层次网络，关注语言模型分词架构与低资源训练问题
14. [BIRD-History: A Benchmark for History-Driven Text-to-SQL with Fine-Grained Knowledge Annotations](/202609/02/2608.29345v1-bird-history-a-benchmark-for-history-driven-text-to-sql-with-fine-grained-knowledge-annotations)  
   标签：评分：6.0/10、query:llm
   evidence：为LLM文本转SQL系统构建历史驱动查询评测基准并提供细粒度知识标注。
15. [CoCoA: Context-Conditional Cultural Alignment for Large Language Models](/202609/02/2608.29492v1-cocoa-context-conditional-cultural-alignment-for-large-language-models)  
   标签：评分：6.0/10、query:post-train
   evidence：基于双上下文对比训练的文化对齐方法，属于LLM对齐技术范畴


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
