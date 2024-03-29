# A Deep Siamese Postclassification Fusion Network for Semantic Change Detection
 
- 出发点

许多现有的方法都存在错误分类错误的积累。现有的方法没有充分利用时间相关性。

- 主要思想

PCFN分别由用于土地覆盖图（LCM）的孪生分类网络（SCN）和用于后分类SCD的软融合网络（SFN）组成。在PCFN中，SCN被设计为通过处理联合特征来有效地整合两幅图像之间的时间相关性，从而进一步提高分类性能。然后，构建SFN，通过自动软融合来确定变化并识别特定的变化类型。SFN融合SCN生成的多时相LCM特征，然后在网络训练期间将其自适应地映射到决策空间进行软融合，并预测最终的语义变化图。

- 介绍

传统的二值变化检测仅进行变化区域的检测，而忽略了检测目标的语义，但实际生活中，检测语义至关重要。

[paper1](https://www.sciencedirect.com/science/article/pii/S0924271606001122)
- 相关工作总结

传统二值变化检测：

早期融合：U-Net++_MSOF、DDCNN和FC-EF

晚期融合：

语义变化检测方法：

实验部分：

second数据集划分比例2：1
