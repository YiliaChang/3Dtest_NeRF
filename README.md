# 3D重建之NeRF
阅读论文《[NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934)》，思考并回答以下问题：

## 一、基础概念与术语解释
1. NeRF所解决的核心问题是什么？

2. NeRF是如何进行场景表达与实现的？网络的输入、输出分别是什么？

3. 简述新视角渲染合成的大致流程。

## 二、论文阅读与方法原理
1. NeRF是如何实现多视角一致性的？（至少两点）

2. 分析作者提出 Positional encoding 和 Hierarchical volume sampling 的原因与目的。与传统方法相比，它们的优势在哪里？

3. 分析论文Table 2的消融实验，你认为作者为什么要这么设计？这样设计的好处和目的是什么？

   从作者设计的这些实验中，你能分析得到什么结论？

   你认为是否还可以设计更多的消融实验进行算法验证，如果有，请简要说明你的设计。

## 三、代码复现与实现细节
运行NeRF的PyTorch实现版本：https://github.com/yenchenlin/nerf-pytorch
1. 根据README.md进行环境配置；

    提示：若涉及包版本过旧、包之间版本不兼容或与服务器CUDA不兼容等问题，可自行进行升降级处理，最终能够成功运行即可。

2. 根据README.md下载示例数据 lego；

3. 在 lego 上训练，给出运行结果；

4. NeRF是否需要使用相机位姿？如果不需要，请解释原因；如果需要，请指出代码中是如何使用的，其作用是什么。

# TODO
请将以上问题的答案与实验结果打包成相关文件，发送至邮箱：jinyi.chang@bupt.edu.cn
