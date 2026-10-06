<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-10-06
- 运行时间：2026-10-06 23:54:39 UTC
- 运行状态：成功
- 本次总论文数：25
- 精读区：10
- 速读区：15

### 今日简报（AI）
2026-10-06 日报共收 25 篇，精读 10 篇、速读 15 篇，两篇 9.0 分精读领跑：聚焦“把教师 token 花在刀刃上”的 on-policy 蒸馏，以及重思多教师能力合并的自蒸馏。  
最值得看的方向是蒸馏/自蒸馏如何更高效地服务多教师能力合并与后训练，速读里还有对齐数据构建、Tropical RL、LLM 多任务后训练的自适应互蒸馏等 8.0 分线索。  
普通读者可先读两篇 9.0 精读建立主线，再按兴趣从 8.0 速读中挑对齐数据或多任务后训练切入。
- 详情：[/202610/06/README](/202610/06/README)

### 精读区论文标签
1. [Spend Teacher Tokens Where They Matter: Success-Referenced On-Policy Distillation](/202610/06/2610.02678v1-spend-teacher-tokens-where-they-matter-success-referenced-on-policy-distillation)  
   标签：评分：9.0/10、query:post-train
   evidence：在线蒸馏，选择性为哪些rollout提供教师监督
2. [Rethinking Self-Distillation for Multi-Teacher Capability Merging](/202610/06/2610.04272v1-rethinking-self-distillation-for-multi-teacher-capability-merging)  
   标签：评分：9.0/10、query:post-train
   evidence：多教师在线蒸馏与监督微调的受控研究
3. [ResOPD: Tail Residualization for Sparse On-Policy Distillation](/202610/06/2610.04882v1-resopd-tail-residualization-for-sparse-on-policy-distillation)  
   标签：评分：9.0/10、query:post-train
   evidence：稀疏在线蒸馏与无偏梯度估计
4. [SearchJev: A Fast and Calibrated System-1 Model for Search Agents](/202610/06/2610.05107v1-searchjev-a-fast-and-calibrated-system-1-model-for-search-agents)  
   标签：评分：9.0/10、query:agent
   evidence：面向搜索智能体决策的快速校准System-1模型
5. [Wikidata Search Traces: A Dataset for Training Knowledge Graph Search Agents](/202610/06/2610.06650v1-wikidata-search-traces-a-dataset-for-training-knowledge-graph-search-agents)  
   标签：评分：9.0/10、query:agent
   evidence：用于训练知识图谱搜索智能体的数据集与接口设计
6. [Programmatic Search Agents: Extending Agentic Search Beyond Query Reformulation](/202610/06/2610.06689v1-programmatic-search-agents-extending-agentic-search-beyond-query-reformulation)  
   标签：评分：9.0/10、query:agent
   evidence：程序化搜索智能体，将智能体式搜索拓展到查询改写之外
7. [TopK-Guided: Adaptive, Budget-Aware Activation Sparsity for Efficient LLM Inference](/202610/06/2610.01763v1-topk-guided-adaptive-budget-aware-activation-sparsity-for-efficient-llm-inference)  
   标签：评分：8.0/10、query:llm
   evidence：面向高效LLM推理的免训练自适应激活稀疏方法
8. [Dynamic Harness Search: Building Multi-Agent Systems Per-Query via Prediction](/202610/06/2610.04137v1-dynamic-harness-search-building-multi-agent-systems-per-query-via-prediction)  
   标签：评分：8.0/10、query:agent
   evidence：通过预测为每个查询动态构建多智能体框架
9. [Small Agents with Semantic Search: Efficient Multilingual Code Localization](/202610/06/2610.05099v1-small-agents-with-semantic-search-efficient-multilingual-code-localization)  
   标签：评分：8.0/10、query:agent
   evidence：面向代码仓库定位智能体的语义检索训练框架
10. [AgentDiscover: Autonomous Discovery with Minimal Search Scaffolding](/202610/06/2610.05334v1-agentdiscover-autonomous-discovery-with-minimal-search-scaffolding)  
   标签：评分：8.0/10、query:agent
   evidence：编码智能体自主规划搜索

### 速读区论文标签
1. [From Normative Frameworks to Alignment Data: Constructing and Evaluating SFT and Preference Data](/202610/06/2609.35201v1-from-normative-frameworks-to-alignment-data-constructing-and-evaluating-sft-and-preference-data)  
   标签：评分：8.0/10、query:post-train
   evidence：构建与评测SFT及偏好数据
2. [Tropical Reinforcement Learning](/202610/06/2610.02478v1-tropical-reinforcement-learning)  
   标签：评分：8.0/10、query:post-train
   evidence：面向LLM后训练的强化学习
3. [Adaptive Mutual Distillation for Balanced Multi-Task Post-Training of Large Language Models](/202610/06/2610.02856v1-adaptive-mutual-distillation-for-balanced-multi-task-post-training-of-large-language-models)  
   标签：评分：8.0/10、query:post-train
   evidence：面向LLM多任务后训练的互蒸馏协作框架
4. [FALCON: A Model and Dataset Agnostic Framework for Synthetic Data Generation for NL2SQL Pairs](/202610/06/2610.03625v1-falcon-a-model-and-dataset-agnostic-framework-for-synthetic-data-generation-for-nl2sql-pairs)  
   标签：评分：8.0/10、query:llm-synth
   evidence：模型与数据集无关的合成NL2SQL数据生成框架
5. [More Value per Key: Asymmetric Sparse Attention for Faster LLM Decoding](/202610/06/2610.04753v1-more-value-per-key-asymmetric-sparse-attention-for-faster-llm-decoding)  
   标签：评分：8.0/10、query:llm
   evidence：解耦键头与值头以加速LLM解码的非对称稀疏注意力
6. [FactorEngram: Factorized N-gram Memory with Basis-Level Gating for Language Models](/202610/06/2609.35578v1-factorengram-factorized-n-gram-memory-with-basis-level-gating-for-language-models)  
   标签：评分：7.0/10、query:llm
   evidence：面向LLM的查找式记忆架构
7. [When Updating Stops Being Learning: Rethinking LLM Self-Evolution via learnable information gain](/202610/06/2609.36535v1-when-updating-stops-being-learning-rethinking-llm-self-evolution-via-learnable-information-gain)  
   标签：评分：7.0/10、query:llm-synth
   evidence：以可学习信息增益衡量LLM用自身生成数据的自演化
8. [Video2Skill: From Streaming Experience to Reusable Embodied Skills](/202610/06/2609.36691v1-video2skill-from-streaming-experience-to-reusable-embodied-skills)  
   标签：评分：7.0/10、query:agent
   evidence：具身智能体从流式经验中发现可复用技能用于规划
9. [ATTUNER: Recomputation-Free KV Cache Reuse via Query-Side Adaptation](/202610/06/2609.36722v1-attuner-recomputation-free-kv-cache-reuse-via-query-side-adaptation)  
   标签：评分：7.0/10、query:llm
   evidence：复用KV缓存以降低大模型推理计算
10. [Calibrate the Decisions That Change the Future: On-Policy Post-Training Quantization for Multimodal Large Language Models](/202610/06/2609.36828v1-calibrate-the-decisions-that-change-the-future-on-policy-post-training-quantization-for-multimodal-large-language-models)  
   标签：评分：7.0/10、query:llm
   evidence：面向多模态大模型高效推理的在线训练后量化校准
11. [Two-Timescale Fine-tuning Provably Learns New Features for Two-Layer ReLU Networks](/202610/06/2609.34667v1-two-timescale-fine-tuning-provably-learns-new-features-for-two-layer-relu-networks)  
   标签：评分：6.0/10、query:llm
   evidence：对预训练网络微调的两时间尺度训练进行理论分析
12. [Reference-Grounded Data Curation for Instruction-Following Thai-English Machine Translation](/202610/06/2609.34770v2-reference-grounded-data-curation-for-instruction-following-thai-english-machine-translation)  
   标签：评分：6.0/10、query:llm-synth
   evidence：面向指令跟随翻译的数据整理与增强
13. [TQTS-Bench: A Multi-Syntax Benchmark for Text-to-Query over Time-Series Databases](/202610/06/2609.34783v1-tqts-bench-a-multi-syntax-benchmark-for-text-to-query-over-time-series-databases)  
   标签：评分：6.0/10、query:llm
   evidence：评估LLM文本到查询能力的基准
14. [Attention-based Hierarchical Variational Information Bottleneck for Robust Multi-Agent Communication under Variable Bandwidth](/202610/06/2609.34860v1-attention-based-hierarchical-variational-information-bottleneck-for-robust-multi-agent-communication-under-variable-bandwidth)  
   标签：评分：6.0/10、query:agent
   evidence：基于变分信息瓶颈的多智能体通信
15. [Research-Native by Construction: Minimal Nodes, Re-verifiable Workflows, and Compounding Memory for Long-Horizon Scientific Agents](/202610/06/2609.35182v1-research-native-by-construction-minimal-nodes-re-verifiable-workflows-and-compounding-memory-for-long-horizon-scientific-agents)  
   标签：评分：6.0/10、query:agent
   evidence：面向长时程科研的智能体框架设计并强制研究纪律


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
