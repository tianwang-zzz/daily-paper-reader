---
title: "An EEG-fMRI Jointly Constrained Digital Twin Brain and Its Application in Alzheime's Disease"
title_zh: 一种由 EEG-fMRI 联合约束的数字孪生脑及其在阿尔茨海默病中的应用
authors: "Yue, X., Guo, D., Xu, Y., Chen, Y., Zhang, R., Luo, Y., Wang, F., Zeng, X., Guo, Y., Yao, D."
date: 2026-04-14
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.10.717365v1.full.pdf"
tags: ["query:mci-ad"]
score: 10.0
evidence: EEG-fMRI联合约束的数字孪生脑用于阿尔茨海默病建模
tldr: 本研究针对现有数字孪生脑（DTB）模型仅依赖单一模态fMRI数据、难以模拟多时空尺度动力学的局限，提出了一种由EEG和fMRI共同约束的两阶段数字孪生脑（TS-DTB）建模框架。该模型在健康人群和阿尔茨海默病（AD）患者中均验证了其捕捉个体化多尺度特征的能力，揭示了AD认知下降与兴奋-抑制（E-I）失衡的机制联系，并通过模拟rTMS治疗展示了其在个性化数字医疗中的潜力。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-001.webp\", \"caption\": \"\", \"page\": 4, \"index\": 1, \"width\": 3964, \"height\": 3343}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-002.webp\", \"caption\": \"\", \"page\": 5, \"index\": 2, \"width\": 3843, \"height\": 3124}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-003.webp\", \"caption\": \"\", \"page\": 6, \"index\": 3, \"width\": 4500, \"height\": 2654}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-004.webp\", \"caption\": \"\", \"page\": 8, \"index\": 4, \"width\": 4228, \"height\": 4562}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-005.webp\", \"caption\": \"\", \"page\": 9, \"index\": 5, \"width\": 4500, \"height\": 3690}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-006.webp\", \"caption\": \"\", \"page\": 10, \"index\": 6, \"width\": 4267, \"height\": 3970}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-007.webp\", \"caption\": \"\", \"page\": 11, \"index\": 7, \"width\": 4383, \"height\": 3866}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-008.webp\", \"caption\": \"\", \"page\": 13, \"index\": 8, \"width\": 4385, \"height\": 3690}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-009.webp\", \"caption\": \"\", \"page\": 25, \"index\": 9, \"width\": 4500, \"height\": 3238}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-010.webp\", \"caption\": \"\", \"page\": 26, \"index\": 10, \"width\": 4500, \"height\": 2637}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-011.webp\", \"caption\": \"\", \"page\": 27, \"index\": 11, \"width\": 4500, \"height\": 2443}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-10-717365-v1/fig-012.webp\", \"caption\": \"\", \"page\": 28, \"index\": 12, \"width\": 4273, \"height\": 2260}]"
motivation: 现有的数字孪生脑模型多基于单一模态的fMRI数据，限制了其在多时空尺度上模拟大脑动态的能力。
method: 提出了一种两阶段建模框架（TS-DTB），通过整合高时间分辨率的EEG和高空间分辨率的fMRI数据来共同约束模型参数。
result: 该模型成功复现了AD患者认知障碍的光谱-时间特征，并将其归因于大脑的兴奋-抑制失衡。
conclusion: TS-DTB模型深化了对大脑机制的理解，并为阿尔茨海默病等疾病的个性化数字疗法提供了有力工具。
---

## 摘要
目前的数字孪生脑（DTB）模型通常使用单模态功能磁共振成像（fMRI）数据进行优化，这限制了它们在多个时空尺度上模拟大脑动力学的能力。在此，我们通过开发一种由 fMRI 和脑电图（EEG）数据联合约束的两阶段数字孪生脑（TS-DTB）建模框架，填补了这一空白。在健康青年和阿尔茨海默病（AD）队列中的验证表明，TS-DTB 模型能够同时捕捉多尺度大脑动力学的个体特异性特征。特别是，AD 患者的 TS-DTB 模型成功重现了认知能力下降的时频特征，并从机制上将这些缺陷与兴奋-抑制（E-I）失衡联系起来。通过模拟对重复经颅磁刺激（rTMS）的反应，我们进一步揭示了 AD 患者的认知恢复可以通过突触重构和背景抑制实现的 E-I 重新平衡来驱动。总的来说，这些发现强调了 TS-DTB 在促进对大脑机制理解以及为个性化数字疗法提供参考方面的潜力。

## Abstract
Current digital twin brain (DTB) models are typically optimized using single-modality functional magnetic resonance imaging (fMRI) data, which restricts their ability to simulate brain dynamics across multiple spatiotemporal scales. Here, we bridged this gap by developing a two-stage DTB (TS-DTB) modeling framework jointly constrained by fMRI and electroencephalography (EEG) data. Validation in both the healthy young and Alzheimer's disease (AD) cohorts demonstrated that the TS-DTB model simultaneously captures subject-specific features of multi-scale brain dynamics. In particular, the TS-DTB models of AD patients successfully recapitulated spectral-temporal signatures of cognitive decline, mechanistically linking these deficits to excitation-inhibition (E-I) imbalances. By simulating responses to repetitive transcranial magnetic stimulation (rTMS), we further revealed that cognitive recovery in AD patients can be driven by E-I rebalancing via synaptic reconfiguration and background suppression. Overall, these findings underscore the potential of the TS-DTB to advance the mechanistic understanding of the brain and inform personalized digital therapeutics.