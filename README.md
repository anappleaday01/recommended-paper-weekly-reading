# 每周推荐论文精读 (Recommended-Paper-Weekly-Reading)

本仓库整理了每周的推荐论文精读，旨在为自己记录阅读推荐相关论文。

您可以通过本仓库：
- **跟踪阅读进度**：使用 `状态` 列标记每篇论文的阅读情况。
- **记录和沉淀思考**：为每篇论文创建独立的笔记文件，并链接到主列表。
- **快速概览**：清晰地查看各个子领域的核心论文和贡献。

## 目录
- [202511](#202511)


## 如何使用
1. **Fork 本仓库**到您自己的 Git账号。
2. **Clone 仓库**到本地。
3. 当您开始阅读一篇论文时，在 `README.md` 中将其**状态**从 `⬜️ 未读` 修改为 `⏳ 在读`。
4. 在 `notes/` 文件夹下，复制 `template.md` 并重命名为 `[编号]-[关键词].md` (例如 `001-dqn.md`)，开始记录您的笔记。
5. 完成阅读和笔记后，将**状态**修改为 `✅ 已读`。
6. `commit` 和 `push` 您的更改。

---

## 202511

## a. 论文周报[1117] (2篇)

|  #  | 论文标题 (Title)                                                                                                                                                                                                                | 作者 & 年份                  |            发表期刊/会议-评级            |  状态   |                    我的笔记                    |
| :-: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------- | :------------------------------: | :---: | :----------------------------------------: |
|  1  | [MoTAS: MoE-Guided Feature Selection from TTS-Augmented Speech for Enhanced Multimodal Alzheimer's Early Screening](https://arxiv.org/abs/2511.04541)<br/> 论文核心：利用TTS和ASR增强来增加数据量，并使用混合专家( MoE )机制来改进多模态特征选择，共同增强模型泛化性      | Yongqi Shao,2025         | 2025**ACM Multimedia**-**CCF-A** | ✅ 已读  |    [笔记](notes/2511/1-week/001-MoTas.md)    |
|  2  | [Emoface: AI-assisted diagnostic model for differentiating major depressive disorder and bipolar disorder via facial biomarkers](https://arxiv.org/abs/2511.04237)<br/> 论文核心：基于ResNet-18分析患者面部运动特征，利用Grad-CAM进行可视化，区分MDD和BD | Jiahui Yu，2025           |  **npj Mental Health Research**  | ✅ 已读  |   [笔记](notes/2511/1-week/002-Emoface.md)   |
|  3  | [Discourse-Aware Scientific Paper Recommendation via QA-Style Summarization and Multi-Level Contrastive Learning](https://arxiv.org/abs/2511.03330)   <br/> 论文核心：OMRC-MR——语篇感知的科学论文推荐框架                                     | Shenghua Wang, 2025      |                                  | ✅ 已读  |   [笔记](notes/2511/1-week/003-OMRC-MR.md)   |
|  4  | [Generative Sequential Recommendation via Hierarchical Behavior Modeling](https://arxiv.org/abs/2511.03155) <br/>  论文核心：MMCoD——跨模态对比去噪的多模态推荐框架                                                                              | Zhefan Wang,2025         |                                  | ✅ 已读  |    [笔记](notes/2511/1-week/004-MMCoD.md)    |
|  5  | [No-Human in the Loop: Agentic Evaluation at Scale for Recommendation](https://arxiv.org/abs/2511.03051) <br/> 论文核心：ScalingEval——无人工参与的互补物品推荐LLM评估框架                                                                        | Tao Zhang, 2025          |                                  | ✅ 已读  | [笔记](notes/2511/1-week/005-ScalingEval.md) |
|  6  | [KGBridge: Knowledge-Guided Prompt Learning for Non-overlapping Cross-Domain Recommendation](https://arxiv.org/abs/2511.02181) <br/> 论文核心：KGBridge——知识引导提示学习的非重叠跨域推荐框架                                                      | Yuhan Wang, 2025         |                                  | ✅ 已读  |  [笔记](notes/2511/1-week/006-KGBridge.md)   |
|  7  | [Enhancing Multimodal Recommendations with Vision-Language Models and Information-Aware Fusion](https://arxiv.org/abs/2511.02113) <br/> 论文核心：VIRAL——视觉-语言信息感知的多模态推荐框架                                                       | Hai-Dang Kieu, 2025      |                                  | ✅ 已读  |    [笔记](notes/2511/1-week/007-VIRAL.md)    |
|  8  | [Solving Cold Start in News Recommendations: a RippleNet-based System for Large Scale Media Outlet](https://arxiv.org/abs/2511.02052) <br/>   论文核心：基于RippleNet的新闻推荐冷启动解决方案                                                  | Karol Radziszewski, 2025 |                                  | ✅ 已读  |  [笔记](notes/2511/1-week/008-RippleNet.md)  |
|  9  | [A Soft-partitioned Semi-supervised Collaborative Transfer Learning Approach for Multi-Domain Recommendation](https://arxiv.org/abs/2511.01404) <br/>   论文核心：IDIOMoE——解决LLM推荐知识纠缠的混合专家模型                                    | Xiaoyu Liu, 2025         |                                  | ⬜️ 未读 |   [笔记](notes/2511/1-week/009-IDIOMoE.md)   |
| 10  | [Structurally Refined Graph Transformer for Multimodal Recommendation](https://arxiv.org/abs/2511.00584) <br/> 论文核心：推荐系统中新颖物品的安全探索框架（Safe OPG + DEPSUE）                                                                     | Ke Shi, 2025             |                                  | ⬜️ 未读 |  [笔记](notes/2511/1-week/010-Safe-OPG.md)   |


## d. 论文周报[1006-1012] (11篇)

| # | 论文标题 (Title)                                                                                                                                                                                                                                   | 作者 & 年份                 |   状态    |                       我的笔记                       |
|:-:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------|:-------:|:------------------------------------------------:|
| 1 | [Do We Really Need SFT? Prompt-as-Policy over Knowledge Graphs for Cold-start Next POI Recommendation](https://arxiv.org/abs/2510.08012)<br/> 论文核心：Prompt-as-Policy——知识图谱驱动的冷启动POI推荐框架        | Jinze Wang,2025         |  ✅ 已读   | [笔记](notes/2510/1-week/001-Prompt-as-Policy.md)  |
| 2 | [MMM: Quantum-Chemical Molecular Representation Learning for Combinatorial Drug Recommendation](https://arxiv.org/abs/2510.07910)<br/> 论文核心：MMM框架——量子化学分子表示学习用于组合药物推荐                      | Chongmyung Kwon,2025    |  ✅ 已读   |        [笔记](notes/2510/1-week/002-MMM.md)        |
| 3 | [PLUM: Adapting Pre-trained Language Models for Industrial-scale Generative Recommendations](https://arxiv.org/abs/2510.07784)   <br/> 论文核心：PLUM——适配预训练LLM的工业级生成式推荐框架                        | Ruining He, 2025        |  ✅ 已读   |       [笔记](notes/2510/1-week/003-PLUM.md)        |
| 4 | [Retentive Relevance: Capturing Long-Term User Value in Recommendation Systems](https://arxiv.org/abs/2510.07621) <br/>  论文核心：Retentive Relevance（RR）——推荐系统的长期用户价值指标                          | Saeideh Bakhshi,2025    |  ✅ 已读   |        [笔记](notes/2510/1-week/004-RR.md)         |
| 5 | [LLM-Powered Nuanced Video Attribute Annotation for Enhanced Recommendations](https://arxiv.org/abs/2510.06657) <br/> 论文核心：LLM驱动的视频属性标注增强推荐系统                                                 | Boyuan Long, 2025       |  ✅ 已读   | [笔记](notes/2510/1-week/005-LLM-as-annotators.md) |
| 6 | [Reproducibility Study of "XRec: Large Language Models for Explainable Recommendation"](https://arxiv.org/abs/2510.06275) <br/> 论文核心：XRec框架的可复现性研究（LLM驱动可解释推荐）                              | Ranjan Mishra, 2025     |  ✅ 已读   |       [笔记](notes/2510/1-week/006-XRec.md)        |
| 7 | [Constraint-Aware Route Recommendation from Natural Language via Hierarchical LLM](https://arxiv.org/abs/2510.06078) <br/> 论文核心：RouteLLM——自然语言驱动的约束感知路线推荐框架                                  | Tao Zhe, 2025           |  ✅ 已读   |     [笔记](notes/2510/1-week/007-RouteLLM.md)      |
| 8 | [AgentDR: Dynamic Recommendation with Implicit Item-Item Relations via LLM-based Agents](https://arxiv.org/abs/2510.05598) <br/>   论文核心：AgentDR——LLM代理驱动的隐式物品关系推荐框架                           | Mingdai Yang, 2025      |  ✅ 已读   |      [笔记](notes/2510/1-week/008-AgentDR.md)      |
| 9 | [Catalog-Native LLM: Speaking Item-ID Dialect with Less Entanglement for Recommendation](https://arxiv.org/abs/2510.05125) <br/>   论文核心：IDIOMoE——解决LLM推荐知识纠缠的混合专家模型                           | Reza Shirkavand, 2025   |  ✅ 已读   |      [笔记](notes/2510/1-week/009-IDIOMoE.md)      |
| 10 | [Safely Exploring Novel Actions in Recommender Systems via Deployment-Efficient Policy Learning](https://arxiv.org/abs/2510.07635) <br/> 论文核心：推荐系统中新颖物品的安全探索框架（Safe OPG + DEPSUE）          | Haruka Kiyohara, 2025   |  ✅ 已读   |     [笔记](notes/2510/1-week/010-Safe-OPG.md)      |
| 11 | [Limitations of Current Evaluation Practices for Conversational Recommender Systems](https://arxiv.org/abs/2510.05624) <br/> 论文核心：CRSs评估的局限性与用户模拟的潜力                                         | Nolwenn Bernard, 2025   |  ✅ 已读   |     [笔记](notes/2510/1-week/011-CRSs.md)          |


## 202509

## a. 论文周报[0922-0928] (12篇)

| # | 论文标题 (Title)                                                                                                                                                                                | 作者 & 年份                      |  状态   |                       我的笔记                        |
|:-:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------|:-----:|:-------------------------------------------------:|
| 1 | [Interactive Recommendation Agent with Active User Commands](https://arxiv.org/abs/2509.21317) <br/>论文核心：RecBot——支持主动用户命令的交互式推荐代理                                                          | Jiakai Tang,<br /> 2025      | ✅ 已读  |       [笔记](notes/2509/4-week/001-RecBot.md)       |
| 2 | [IntSR: An Integrated Generative Framework for Search and Recommendation](https://arxiv.org/abs/2509.21179)  <br/>论文核心：IntSR——搜索与推荐的集成生成框架                                                   | Huimin Yan,<br /> 2025       | ✅ 已读  |       [笔记](notes/2509/4-week/002-IntSR.md)        |
| 3 | [RecIS: Sparse to Dense, A Unified Training Framework for Recommendation Models](https://arxiv.org/abs/2509.20883) <br/>论文核心：RecIS——PyTorch稀疏-稠密统一推荐训练框架                                     | Hua Zong,  <br />2025        | ✅ 已读  |       [笔记](notes/2509/4-week/003-RecIS.md)        |
| 4 | [USB-Rec: An Effective Framework for Improving Conversational Recommendation Capability of Large Language Model](https://arxiv.org/abs/2509.20381) <br/> 论文核心：USB-Rec——LLM对话推荐的训练-推理一体化框架   | Jianyu Wen,2025              | ✅ 已读  |      [笔记](notes/2509/4-week/004-USB-Rec.md)       |
| 5 | [Multimodal Representation-disentangled Information Bottleneck for Multimodal Recommendation](https://arxiv.org/abs/2509.20225) <br/>论文核心：MRdIB——多模态推荐的解纠缠信息瓶颈框架                           | Hu i Wang, 2025              | ✅ 已读  |       [笔记](notes/2509/4-week/005-MRdIB.md)        |
| 6 | [Multimodal-enhanced Federated Recommendation: A Group-wise Fusion Approach](https://arxiv.org/abs/2509.19955) <br/>论文核心：GFMFR——多模态增强的联邦推荐框架                                                 | Chunxu Zhang, 2025           | ✅ 已读  |       [笔记](notes/2509/4-week/006-GFMFR.md)        |
| 7 | [MusiCRS: Benchmarking Audio-Centric Conversational Recommendation](https://arxiv.org/abs/2509.19469) <br/>论文核心：MusiCRS——音频中心对话推荐基准                                                           | Rohan Surana, 2025           | ✅ 已读  |      [笔记](notes/2509/4-week/007-MusiCRS.md)       |
| 8 | [Single-Branch Network Architectures to Close the Modality Gap in Multimodal Recommendation](https://arxiv.org/abs/2509.18807) <br/>论文核心：SiBraR——单分支多模态推荐框架（缩小模态差距）                      | Christian Ganhör, <br />2025 | ✅ 已读  |       [笔记](notes/2509/4-week/008-SiBraR.md)       |
| 9 | [Rejuvenating Cross-Entropy Loss in Knowledge Distillation for Recommender Systems](https://arxiv.org/abs/2509.20989)<br/>论文核心：RCE-KD——振兴推荐系统KD中的CE损失                                         | Zhangchi Zhu, 2025           | ✅ 已读 |       [笔记](notes/2509/4-week/009-RCE-KD.md)       |
| 10 | [Robust Denoising Neural Reranker for Recommender Systems](https://arxiv.org/abs/2509.18736)<br/>论文核心：DNR——去噪神经重排序器（多阶段推荐优化）                                                             | Wenyu Mao,  2025             | ✅ 已读 | [笔记](notes/2509/4-week/010-DNR.md) |
| 11 | [Shilling Recommender Systems by Generating Side-feature-aware Fake User Profiles](https://arxiv.org/abs/2509.17918) <br/> 论文核心：D3Rec——动态漂移感知的多模态推荐框架                                      | Yuanrong Wang,  2025         | ✅ 已读 |   [笔记](notes/2509/4-week/011-D3Rec.md)    |
| 12 | [Adaptive User Interest Modeling via Conditioned Denoising Diffusion For Click-Through Rate Prediction](https://arxiv.org/abs/2509.19876) <br/> 论文核心：CDP——用于CTR预测的条件扩散净化用户兴趣建模框架        | Qihang Zhao, 2025            | ✅ 已读 |        [笔记](notes/2509/4-week/012-CDP.md)        |
