<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-17
- 运行时间：2026-09-17 22:11:53 UTC
- 运行状态：成功
- 本次总论文数：25
- 精读区：10
- 速读区：15

### 今日简报（AI）
今日精读10篇、速读15篇共25篇，焦点集中在LLM深度剪枝与多轮智能体蒸馏。最值得看的是《Forward-Free LLM Depth Pruning via Weight Redundancy》和《Know When to Stop, Where to Restart》两篇9分工作，前者免前向剪枝降深度，后者用停止/重启策略加速多轮on-policy蒸馏。普通读者可先从这两篇入手，再顺着速读里的Data-free On-policy Distillation和AdaVSkip理解效率优化思路。
- 详情：[/202609/17/README](/202609/17/README)

### 精读区论文标签
1. [Forward-Free LLM Depth Pruning via Weight Redundancy](/202609/17/2609.09883v2-forward-free-llm-depth-pruning-via-weight-redundancy)  
   标签：评分：9.0/10、query:llm
   evidence：无需前向的深度剪枝降低LLM推理成本
2. [Know When to Stop, Where to Restart: Accelerating Multi-Turn Agentic On-Policy Distillation](/202609/17/2609.14636v1-know-when-to-stop-where-to-restart-accelerating-multi-turn-agentic-on-policy-distillation)  
   标签：评分：9.0/10、query:post-train
   evidence：面向智能体的在线策略蒸馏加速
3. [RSIAgent: Autonomous Exploration for Recursive Self-improvement in New Environments](/202609/17/2609.15364v1-rsiagent-autonomous-exploration-for-recursive-self-improvement-in-new-environments)  
   标签：评分：9.0/10、query:agent
   evidence：免训练多智能体自主探索与自我改进框架
4. [Beyond Token-Local Imitation: Reward-Compatible Temporal Credit Assignment for On-Policy Distillation](/202609/17/2609.16937v1-beyond-token-local-imitation-reward-compatible-temporal-credit-assignment-for-on-policy-distillation)  
   标签：评分：9.0/10、query:post-train
   evidence：面向大模型后训练的在线蒸馏时序信用分配
5. [NeMo Data Designer: An Extensible Framework for Multimodal Synthetic Data Generation](/202609/17/2609.17699v1-nemo-data-designer-an-extensible-framework-for-multimodal-synthetic-data-generation)  
   标签：评分：9.0/10、query:llm-synth
   evidence：多模态合成数据生成框架
6. [Toward Self-Adaptive Physical AI: Can LLM Agents Manage Long-Horizon Physical Tasks?](/202609/17/2609.13436v1-toward-self-adaptive-physical-ai-can-llm-agents-manage-long-horizon-physical-tasks)  
   标签：评分：8.0/10、query:agent
   evidence：面向自主长时程任务的多智能体框架
7. [Drift-Constrained Optimization: Only Direction Matters in Fine-Tuning Instruct Models](/202609/17/2609.13680v1-drift-constrained-optimization-only-direction-matters-in-fine-tuning-instruct-models)  
   标签：评分：8.0/10、query:llm
   evidence：带行为漂移约束的指令模型微调
8. [EMR: Self-Evolving Medical Multi-Agent System via Experience Mining and Reuse](/202609/17/2609.15161v1-emr-self-evolving-medical-multi-agent-system-via-experience-mining-and-reuse)  
   标签：评分：8.0/10、query:agent
   evidence：自演化LLM多智能体医疗系统
9. [Spurious Tool Use: When RL Agents Learn the Wrong Reason to Act](/202609/17/2609.16268v1-spurious-tool-use-when-rl-agents-learn-the-wrong-reason-to-act)  
   标签：评分：8.0/10、query:agent
   evidence：LLM智能体交错使用工具，RL学到虚假工具选择策略
10. [AgentGuard: Learning Execution Guardrails from Anomalous Coding-Agent Trajectories](/202609/17/2609.16287v1-agentguard-learning-execution-guardrails-from-anomalous-coding-agent-trajectories)  
   标签：评分：8.0/10、query:agent
   evidence：面向编码智能体的执行护栏

### 速读区论文标签
1. [Data-free On-policy Distillation](/202609/17/2609.14193v1-data-free-on-policy-distillation)  
   标签：评分：8.0/10、query:post-train
   evidence：后训练流程中在线策略蒸馏的数据效率
2. [AdaVSkip: Adaptive Visual Token Skipping Across Layers For Efficient MLLMs Inference](/202609/17/2609.15131v1-adavskip-adaptive-visual-token-skipping-across-layers-for-efficient-mllms-inference)  
   标签：评分：8.0/10、query:llm
   evidence：面向高效多模态大模型推理的自适应视觉token跳层
3. [Towards Scalable RLVR: Multimodal Instruction Following Data Synthesis and Distillation](/202609/17/2609.16059v1-towards-scalable-rlvr-multimodal-instruction-following-data-synthesis-and-distillation)  
   标签：评分：8.0/10、query:llm-synth
   evidence：多模态指令跟随的数据合成与蒸馏流程
4. [Style-Debiased DPO: Updating LLM Knowledge with Factuality-Aware Synthetic Preference Data](/202609/17/2609.16532v1-style-debiased-dpo-updating-llm-knowledge-with-factuality-aware-synthetic-preference-data)  
   标签：评分：8.0/10、query:post-train
   evidence：用事实性感知合成偏好数据做偏好优化以对齐大模型
5. [FlexEE: Self-Speculative and KV-Compatible Early Exiting for Offloading-Aware LLM Inference](/202609/17/2609.17008v1-flexee-self-speculative-and-kv-compatible-early-exiting-for-offloading-aware-llm-inference)  
   标签：评分：8.0/10、query:llm
   evidence：面向大模型推理优化的提前退出
6. [BRACE: Anchored Bellman-Residual Correction for Stale Critics in Asynchronous RL](/202609/17/2609.09783v2-brace-anchored-bellman-residual-correction-for-stale-critics-in-asynchronous-rl)  
   标签：评分：7.0/10、query:post-train
   evidence：面向LLM训练的异步强化学习价值校正
7. [Residual Vector-based Reconstruction as Long-Context Recall Regardless of Context Window Size](/202609/17/2609.12686v1-residual-vector-based-reconstruction-as-long-context-recall-regardless-of-context-window-size)  
   标签：评分：7.0/10、query:llm
   evidence：大模型长上下文高效推理
8. [FLoKD: Adaptive Knowledge Distillation for Federated Low-Rank LLM over Wireless Networks](/202609/17/2609.13580v1-flokd-adaptive-knowledge-distillation-for-federated-low-rank-llm-over-wireless-networks)  
   标签：评分：7.0/10、query:post-train
   evidence：面向大模型压缩的知识蒸馏
9. [An Efficient and Modular Framework for Targeted Harm Mitigation in LLMS](/202609/17/2609.13624v1-an-efficient-and-modular-framework-for-targeted-harm-mitigation-in-llms)  
   标签：评分：7.0/10、query:post-train
   evidence：面向大模型对齐的模块化危害缓解框架
10. [Trustworthy Agentic AI: A Comprehensive Cybersecurity and Systems Survey on Threat Landscapes, Defense Architectures, and Open Challenges](/202609/17/2609.13731v1-trustworthy-agentic-ai-a-comprehensive-cybersecurity-and-systems-survey-on-threat-landscapes-defense-architectures-and-open-challenges)  
   标签：评分：7.0/10、query:agent
   evidence：自主智能体系统与多智能体协作综述
11. [Can LLMs Normalize Databases? A Benchmark and Multi-Agent Framework for Schema Normalization](/202609/17/2609.11141v1-can-llms-normalize-databases-a-benchmark-and-multi-agent-framework-for-schema-normalization)  
   标签：评分：6.0/10、query:agent
   evidence：面向LLM数据库规范化的多智能体框架与基准
12. [LILA: Calibration-Free Structured Pruning of Large Language Models via Latent Spectral Geometry](/202609/17/2609.11163v1-lila-calibration-free-structured-pruning-of-large-language-models-via-latent-spectral-geometry)  
   标签：评分：6.0/10、query:llm
   evidence：免校准结构化剪枝压缩大模型
13. [Debate-to-Skill: Capability-Bound Process Supervision for Industrial Query-to-Agent Annotation](/202609/17/2609.11176v1-debate-to-skill-capability-bound-process-supervision-for-industrial-query-to-agent-annotation)  
   标签：评分：6.0/10、query:agent
   evidence：查询到智能体匹配的标注监督
14. [Beyond Confidence: Stability-Aware Test-Time Adaptation for LLM Reasoning](/202609/17/2609.11393v1-beyond-confidence-stability-aware-test-time-adaptation-for-llm-reasoning)  
   标签：评分：6.0/10、query:post-train
   evidence：作为昂贵后训练轻量替代的测试时自适应以提升大模型推理
15. [RetroThinker: Enabling Retrospective Thinking in Speech LLMs](/202609/17/2609.11864v1-retrothinker-enabling-retrospective-thinking-in-speech-llms)  
   标签：评分：6.0/10、query:post-train
   evidence：多阶段后训练框架使语音大模型动态修正推理


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
