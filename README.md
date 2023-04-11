# 深度学习论文精读

本文档取自李沐 https://github.com/mli/paper-reading/blob/main/README.md ，其中以NLP领域文章为主，10年内深度学习里有影响力文章（必读文章），或者近期比较有意思的文章。

更多关于李沐的相关消息，关注bilibili:https://space.bilibili.com/1567748478?spm_id_from=333.337.0.0

## 所有论文

包括已经录制完成和之后将要介绍的论文。选取的原则是10年内深度学习里有影响力文章（必读文章），或者近期比较有意思的文章。当然这十年里重要的工作太多了，不可能一一过一遍。在选取的时候我会偏向一些之前 [直播课](https://c.d2l.ai/zh-v2/) 中没讲到过的。 欢迎大家在 [讨论区](https://github.com/mli/paper-reading/discussions) 里提供建（点）议（歌）。

（这里引用采用的是 semanticscholar，是因为它提供 [API](https://api.semanticscholar.org/api-docs/graph#operation/get_graph_get_paper) 可以自动获取，不用手动更新。）


### 自然语言处理 - Transformer

年份 | 名字                                                         | 简介                 | 引用 |
| ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
 2017 | [Transformer](https://arxiv.org/abs/1706.03762) | 继MLP、CNN、RNN后的第四大类架构                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F204e3073870fae3d05bcbc2f6a8e263d9b72e776%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Attention-is-All-you-Need-Vaswani-Shazeer/204e3073870fae3d05bcbc2f6a8e263d9b72e776)  |
 2018 | [GPT](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf) | 使用 Transformer 解码器来做预训练               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fcd18800a0fe0b668a1cc19f2ec95b5003d0a5035%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Improving-Language-Understanding-by-Generative-Radford-Narasimhan/cd18800a0fe0b668a1cc19f2ec95b5003d0a5035)  |
 2018 | [BERT](https://arxiv.org/abs/1810.04805) | Transformer一统NLP的开始                  |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdf2b0e26d0599ce3e70df8a9da02e51594e0e992%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/BERT%3A-Pre-training-of-Deep-Bidirectional-for-Devlin-Chang/df2b0e26d0599ce3e70df8a9da02e51594e0e992)  |
 2019 | [GPT-2](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)  |  更大的 GPT 模型，朝着zero-shot learning迈了一大步             |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9405cc0d6169988371b2755e573cc28650d14dfe%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Language-Models-are-Unsupervised-Multitask-Learners-Radford-Wu/9405cc0d6169988371b2755e573cc28650d14dfe)  |
 2020 |  [GPT-3](https://arxiv.org/abs/2005.14165) | 100倍更大的 GPT-2，few-shot learning效果显著                  |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6b85b63579a916f705a8e10a49bd8d849d91b1fc%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Language-Models-are-Few-Shot-Learners-Brown-Mann/6b85b63579a916f705a8e10a49bd8d849d91b1fc)  |


### 图神经网络

| 年份 | 名字                                                         | 简介                 | 引用 |
| ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
|  2021 | [图神经网络介绍](https://distill.pub/2021/gnn-intro/) | GNN的可视化介绍                  |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2c0e0440882a42be752268d0b64243243d752a74%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/A-Gentle-Introduction-to-Graph-Neural-Networks-S%C3%A1nchez-Lengeling-Reif/2c0e0440882a42be752268d0b64243243d752a74)  |

### 优化算法

| 年份 | 名字                                                         | 简介                 | 引用 |
| ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| 2014 | [Adam](https://arxiv.org/abs/1412.6980) | 深度学习里最常用的优化算法之一                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa6cb366736791bcccc5c8639de5a8f9636bf87e8%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Adam%3A-A-Method-for-Stochastic-Optimization-Kingma-Ba/a6cb366736791bcccc5c8639de5a8f9636bf87e8)  |
| 2016 |  [为什么超大的模型泛化性不错](https://arxiv.org/abs/1611.03530)   |               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F54ddb00fa691728944fd8becea90a373d21597cf%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Understanding-deep-learning-requires-rethinking-Zhang-Bengio/54ddb00fa691728944fd8becea90a373d21597cf)  |
| 2017 | [为什么Momentum有效](https://distill.pub/2017/momentum/) | Distill的可视化介绍            |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3e8ccf9d3d843c9855c5d76ab66d3e775384da72%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Why-Momentum-Really-Works-Goh/3e8ccf9d3d843c9855c5d76ab66d3e775384da72)  |

