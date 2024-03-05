# Multimodal_Causal-Inference

这个仓库用于整理多模态&因果推理相关论文及研究资料。



因果推理加多模态做得比较多的组或者作者：
[NTU MReaL Lab](https://mreallab.github.io/index.html)
[SYSU HCP Lab](https://www.sysu-hcp.net/)
[Elias Bareinboim](https://causalai.net/)



0.GPO-Learning the Best Pooling Strategy for Visual Semantic Embedding
[CODE](https://github.com/woodfrog/vse_infty)
[PAPER](https://arxiv.org/abs/2011.04305) 
这个是一篇讲池化策略的文章，这个方法其实还可以加上反事实框架进行优化。

1.[2023] Cross-Modal Causal Relational Reasoning for Event-Level Visual Question Answering
[CODE]()
[PAPER](https://arxiv.org/abs/2207.12647)
跨模态因果干预实现鲁棒可信的事件级问答推理，提出了一个由**语言语义关系引导的语言后门因果干预模块**，以减弱语言偏误并挖掘语言模态内部的因果关系。

2.[2021 CVPR] DeVLBert: Learning Deconfounded Visio-Linguistic Representations
[CODE](https://github.com/shengyuzhang/DeVLBert)
[PAPER](https://arxiv.org/abs/2008.06884)
在**预训练**领域使用因果进行去偏，主要是通过调整BERT的结构来实现去偏。值得借鉴的是提出了**多模态的混淆字典构建方法**。

3.[2022] Causal Reasoning Meets Visual Representation Learning: A Prospective Study
[PAPER](https://arxiv.org/abs/2204.12037)
因果推理和视觉表征学习的综述，主要是专注于视觉表征，总结了最近几年因果在各大数据集和模型中的应用和论文。

4.[2020]Deconfounded Image Captioning: A Causal Retrospect
[PAPER](https://arxiv.org/abs/2003.03923)
没代码，但是从预训练集入手去偏的，比较详细的讲了**如何选择混杂因子Z**和选择的理由，值得参考。

5.[2021 CVPR]Counterfactual VQA: A Cause-Effect Look at Language Bias
[PAPER](https://arxiv.org/abs/2006.04315)
[CODE](https://github.com/yuleiniu/cfvqa)
从比较独特的角度去利用因果推理，作者表示接受预训练所带来的偏差，并从QA环节来去除偏差，在推理部分应用了反事实。

6.[2020 CVPR] Two Causal Principles for Improving Visual Dialog
[PAPER](https://arxiv.org/abs/1911.10496)
[CODE](https://github.com/simpleshinobu/visdial-principles)
跟跨模态检索相关性不大的一篇文章，但是作者提供了一个如何在复杂任务(Ex. VQA为简单任务，VisDial为复杂任务)的情形下建立任务的SCM并引入两条因果原则。

7.[2020 CVPR] Visual Commonsense R-CNN
[PAPER](https://arxiv.org/abs/2002.12204)
[CODE](https://github.com/Wangt-CN/VC-R-CNN)
通过因果去发现视觉常识，不预设因果关系，而是去发现因果关系。并且在实现部分有非常详细的**代码**和步骤支撑，可以详细研究试验部分。