---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I’m currently an assistant professor in the School of Computer Science and Engineering at Guangxi Normal University. Before that, I received my Ph.D. degree from Beihang University(BUAA), under the supervision of Prof. Jianxin Li. 

My research interests include AI4Science, AI4Education, Geometric Deep Learning and Trustworthy AI. Please feel free to send me an email if interested to discuss or work together. 

**[Prospective students]** Our group has positions for Ph.D. students, Master students, and visiting students. If you are interested, please send me an email with your CV and publications (if any). 

# 🔥 News
- *2025.04* &nbsp;🎉 **One** papers are accepted by **CVPR 2025**, and have been selected to be presented as a **highlight**.
- *2025.01* &nbsp;🎉 **Two** papers are accepted by **ICLR 2025**  
- *2025.01* &nbsp;🎉 **One** paper is accepted by **WWW 2025** 
- *2024.12* &nbsp;🎉 **Five** papers are accepted by **AAAI 2025** 
- *2024.10* &nbsp;🎉 **One** paper is accepted by **WSDM 2025**
- *2024.09* &nbsp;🎉 **One** paper is accepted by **NeurIPS 2024**
- *2024.05* &nbsp;🎉 **One** paper is accepted by **ICML 2024**
- *2024.05* &nbsp;🌟 We host a challenge **Characterizing User Behavior in Social Networks: Propagation, Prediction, and Sensemaking** in **IEEE BigData Cup 2024**
- *2024.01* &nbsp;🎉 **One** paper is accepted by **WWW 2024**

# 📝 Publications 
\* denotes equal contribution and \# denotes corresponding author

**2025:**
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">ICLR 2025</span>  <span style="color:red">(Highlight) [Galaxy Walker: Geometry-aware VLMs For Galaxy-scale Understanding](https://arxiv.org/pdf/2503.18578v1). Tianyu Chen, **Xingcheng Fu**, Yisen Gao, Haodong Qian, Yuecen Wei, Kun Yan, Haoyi Zhou, Jianxin Li\#
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">ICLR 2025</span>  [IGL-Bench: Establishing the Comprehensive Benchmark for Imbalanced Graph Learning](https://arxiv.org/pdf/2406.09870). Jiawen Qin\*, Haonan Yuan\*, Qingyun Sun\*, Lyujin Xu, Jiaqi Yuan, Pengfeng Huang, Zhaonan Wang, **Xingcheng Fu**, Hao Peng, Jianxin Li, Philip S. Yu  
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">ICLR 2025</span>  [ST-GCond: Self-supervised and Transferable Graph Dataset Condensation](https://openreview.net/pdf?id=wYWJFLQov9), Jiayi Luo, Qingyun Sun#, Haonan Yuan, **Xingcheng Fu**, Jianxin Li 
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">WWW 2025</span>  [Robust Graph Learning Against Adversarial Evasion Attacks via Prior-Free Diffusion-Based Structure Purification](https://openreview.net/pdf?id=pwdRhjHrEx), Beining Yang, Qingyun Sun#, Cheng Ji, **Xingcheng Fu**, Jianxin Li
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">AAAI 2025</span>  [GraphMoRE: Mitigating Topological Heterogeneity via Mixture of Riemannian Experts](https://arxiv.org/pdf/2412.11085). Zihao Guo, Qingyun Sun#, Haonan Yuan, **Xingcheng Fu**, Min Zhou, Yisen Gao, Jianxin Li
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">AAAI 2025</span>  [DG-Mamba: Robust and Efficient Dynamic Graph Structure Learning with Selective State Space Models](https://arxiv.org/pdf/2412.08160). Haonan Yuan, Qingyun Sun, Zhaonan Wang, **Xingcheng Fu**, Cheng Ji, Yongjian Wang, Bo Jin, Jianxin Li
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">AAAI 2025</span>  [Discrete Curvature Graph Information Bottleneck](https://arxiv.org/pdf/2412.19993). **Xingcheng Fu#**, Jian Wang, Yisen Gao, Qingyun Sun#, Haonan Yuan, Jianxin Li, Xianxian Li
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">AAAI 2025</span>  <span style="color:red">(Oral) [Bi-Directional Multi-Scale Graph Dataset Condensation via Information Bottleneck](https://arxiv.org/pdf/2412.17355). **Xingcheng Fu**, Yisen Gao, Beining Yang, Yuxuan Wu, Haodong Qian, Qingyun Sun, Xianxian Li 
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">AAAI 2025</span>  [Prompt-based Unifying Inference Attack on Graph Neural Networks](https://arxiv.org/pdf/2412.15735). Yuecen Wei, **Xingcheng Fu**, Lingyun Liu, Qingyun Sun, Hao Peng, Chunming Hu
- <span style="background-color:#005BAC; color:white; padding:2px 4px; border-radius:3px;">WSDM 2025</span>  [Graph Size-imbalanced Learning with Energy-guided Structural Smoothing](https://arxiv.org/pdf/2412.17591). Jiawen Qin, Pengfeng Huang, Qingyun Sun, Cheng Ji, **Xingcheng Fu**, Jianxin Li

**2024:**
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">NeurIPS 2024</span>  [GC-Bench: An Open and Unified Benchmark for Graph Condensation](https://arxiv.org/pdf/2407.00615). Qingyun Sun\*, Ziying Chen\*, Beining Yang, Cheng Ji, **Xingcheng Fu**, Sheng Zhou, Hao Peng, Jianxin Li, Philip S. Yu
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">WWW 2024</span>  [Dynamic Graph Information Bottleneck](https://arxiv.org/pdf/2402.06716). Haonan Yuan, Qingyun Sun\#, **Xingcheng Fu**, Cheng Ji, Jianxin Li 
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">ICML 2024</span>  [Hyperbolic Geometric Latent Diffusion Model for Graph Generation](https://arxiv.org/pdf/2405.03188). **Xingcheng Fu**, Yisen Gao, Yuecen Wei, Qingyun Sun, Hao Peng, Jianxin Li, Xianxian Li 
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">AAAI 2024</span>  [ReGCL: Rethinking Message Passing in Graph Contrastive Learning](https://ojs.aaai.org/index.php/AAAI/article/view/28698). Cheng Ji, Zixuan Huang, Qingyun Sun, Hao Peng, **Xingcheng Fu**, Qian Li, Jianxin Li  
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">AAAI 2024</span> [Poincar\'e Differentially Private for Hierarchy-aware Graph Emebedding](https://ojs.aaai.org/index.php/AAAI/article/view/28767). Yuecen Wei, Haonan Yuan, **Xingcheng Fu**, Qingyun Sun, Hao Peng, Xianxian Li, Chunming Hu 

**2023:**
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">NeurIPS 2023</span> [Environment-Aware Dynamic Graph Learning for Out-of-Distribution Generalization](https://openreview.net/pdf?id=n8JWIzYPRz). Haonan Yuan, Qingyun Sun\#, **Xingcheng Fu**, Ziwei Zhang, Cheng Ji, Hao Peng, Jianxin Li   
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">NeurIPS 2023</span> [Does Graph Distillation See Like Vision Dataset Counterpart?](https://arxiv.org/pdf/2310.09192). Beining Yang, Kai Wang, Qingyun Sun, Cheng Ji, **Xingcheng Fu**, Hao Tang, Yang You, Jianxin Li
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">WWW 2023</span> <span style="color:red">(Spotlight Paper)</span> [Hyperbolic Geometric Graph Representation Learning for Hierarchy-imbalance Node Classification](https://arxiv.org/pdf/2304.05059). **Xingcheng Fu**, Yuecen Wei, Qingyun Sun, Haonan Yuan, Jia Wu, Hao Peng, Jianxin Li
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">IEEE TKDE 2023</span> [A Robust and Generalized Framework for Adversarial Graph Embedding](https://arxiv.org/abs/2105.10651). Jianxin Li, **Xingcheng Fu**, Hao Peng, Senzhang Wang, Shijie Zhu, Qingyun Sun, Philip S. Yu, Lifang He
- <span style="background-color:#005BAC; color:white; padding:2px 4px; border-radius:3px;">PR 2023</span> [Higher-Order Memory Guided Temporal Random Walk for Dynamic Heterogeneous Network Embedding](https://arxiv.org/pdf/2310.09192). Cheng Ji, Tao Zhao, Qingyun Sun, **Xingcheng Fu**, Jianxin Li
- <span style="background-color:#005BAC; color:white; padding:2px 4px; border-radius:3px;">WSDM 2023</span> [Unbiased and Efficient Self-Supervised Incremental Contrastive Learning](https://arxiv.org/pdf/2301.12104). Cheng Ji, Jianxin Li, Hao Peng, Jia Wu, **Xingcheng Fu**, Qingyun Sun, Philip S. Yu 
- <span style="background-color:#005BAC; color:white; padding:2px 4px; border-radius:3px;">KAIS 2023</span> [Adaptive Curvature Exploration Geometric Graph Neural Network](https://link.springer.com/article/10.1007/s10115-022-01811-4). **Xingcheng Fu**, Jianxin Li, Jia Wu, Jiawen Qin, Qingyun Sun, Cheng Ji, Senzhang Wang, Hao Peng, Philip S. Yu 
- <span style="background-color:#005BAC; color:white; padding:2px 4px; border-radius:3px;">KAIS 2023</span> [Heterogeneous Graph Neural Network with Semantic-aware Differential Privacy Guarantees](https://link.springer.com/article/10.1007/s10115-023-01895-6). Yuecen Wei, **Xingcheng Fu**, Dongqi Yan, Qingyun Sun, Hao Peng, Jia Wu, Jinyan Wang, Xianxian Li 

**Before 2022:**
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">AAAI 2022</span> [Graph Structure Learning with Variational Information Bottleneck](https://arxiv.org/pdf/2301.12104). Qingyun Sun, Jianxin Li, Hao Peng, Jia Wu, **Xingcheng Fu**, Cheng Ji, Philip S. Yu  
- <span style="background-color:#D20000; color:white; padding:2px 4px; border-radius:3px;">WWW 2022</span> [Curvature Graph Generative Adversarial Networks](https://arxiv.org/pdf/2203.01604). Jianxin Li, **Xingcheng Fu**, Qingyun Sun, Cheng Ji, Jiajun Tan, Jia Wu, Hao Peng  
- <span style="background-color:#005BAC; color:white; padding:2px 4px; border-radius:3px;">CIKM 2022</span> <span style="color:red">(Best Paper Honorable Mention Award)</span> [Position-aware Structure Learning for Graph Topology-imbalance by Relieving Under-reaching and Over-squashing](https://arxiv.org/pdf/2301.12104). Qingyun Sun, Jianxin Li, Haonan Yuan, **Xingcheng Fu**, Hao Peng, Cheng Ji, Qian Li, Philip S. Yu 
- <span style="background-color:#005BAC; color:white; padding:2px 4px; border-radius:3px;">ICDM 2022</span> [Heterogeneous Graph Neural Network for Privacy-Preserving Recommendation](https://arxiv.org/pdf/2210.00538). Yuecen Wei, **Xingcheng Fu**, Qingyun Sun, Hao Peng, Jia Wu, Jinyan Wang, Xianxian Li 
- <span style="background-color:#005BAC; color:white; padding:2px 4px; border-radius:3px;">ICDM 2021</span> <span style="color:red">(Best Paper Candidate)</span> [ACE-HGNN: Adaptive Curvature Exploration Hyperbolic Graph Neural Network](https://arxiv.org/pdf/2211.08168). **Xingcheng Fu**, Jianxin Li, Jia Wu, Qingyun Sun, Cheng Ji, Senzhang Wang, Jiajun Tan, Hao Peng, Philip S. Yu 


<!--- `AAAI 2024` [Emotion Rendering for Conversational Speech Synthesis with Heterogeneous Graph-Based Context Modeling](https://arxiv.org/abs/2312.11947), Rui Liu, Yifan Hu, **Yi Ren**, et al. [![](https://img.shields.io/github/stars/walker-hyf/ECSS?style=social&label=Code+Stars)](https://github.com/walker-hyf/ECSS)
-->
<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->

# 🏆 Honors and Awards
- *2023.12* &nbsp;Excellence Award in Pretrained Model-based Community Detection and Fraudulent Group Mining Competition @ICDM 2023
- *2022.10* &nbsp;CIKM 2022 Best Paper Honorable Mention Award
- *2021.10* &nbsp;ICDM 2021 Best Paper Candidate
- *2021.07* &nbsp;The First Prize at the 7th China "Internet+" Innovation and Entrepreneurship Competition (Beijing)



<!--
# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

# 💬 Invited Talks
- *2025.01* &nbsp; AI TIME, AAAI 2025 Pre-talk ACT-BD session. [\[video\]](https://www.bilibili.com/video/BV1bhr6YuEjL)


# 💻 Service
**Conference Reviewer:**
   - NeurIPS 2023/2024
   - ICLR 2023/2024/2025
   - ICML 2024/2025
   - AAAI 2022/2023/2024/2025
   - IJCAI 2024/2025
   - WWW 2021/2022/2024/2025
   - KDD 2021/2022/2024/2025
   - ICDM 2023
   - DASFFA 2024
   - ICASSP 2024/2025
   - AISTATS 2025 

**Journal Reviewer:**
   - IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)
   - IEEE Transactions on Knowledge and Data Engineering (TKDE)
   - ACM Transactions on Information Systems (TOIS)
   - IEEE Transactions on Neural Networks and Learning Systems (TNNLS)
   - ACM Transactions on the Web (TWEB)
   - IEEE Transactions on Multimedia (TMM)
   - IEEE Transactions on Cybernetics (TCYB)
   - Pattern Recognition (PR)
   - Neural Networks (NN)
   - International Journal of Machine Learning and Cybernetics (JMLC)
   - Journal of Computer Science and Technology (JCST)
   - Journal of Social Computing (JSC)

# 👩‍🎓 Students
- Y. Wei&nbsp;(2021-now, master at Guangxi Normal University → Ph.D. at Beihang University)
- B. Yang&nbsp;(2021-2023, master at Beihang University → Ph.D. at University of Edinburgh)
- S. Wang&nbsp;&nbsp;(2024-now, master at Guangxi Normal University)
- L. Liu&nbsp;(2024-now, master at Guangxi Normal University)
- Y. Gao&nbsp;&nbsp;(2022-now, Intern at Beihang University → master at HKUST)
- H. Qian&nbsp;&nbsp;(2022-now, Intern at Guangxi Normal University → master at Tianjin University)
