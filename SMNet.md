# SMNet: Symmetric Multi-T ask Network for Semantic Change Detection in Remote Sensing Images Based on CNN and T ransformer

- 主要思想

提出了一种基于CNN和Transformer的方法

首先，为了从双时遥感图像中提取局部和全局信息，建立了由PR（卷积块）和TB（transformer块）组成的混合PRTB骨干，该骨干提取不同的层次特征。然后，使用一种新的多内容融合模块（MCFM）来增强通过减去提取的相应层次特征而获得的变化相关特征。主要由三部分组成：多尺度特征提取编码器、多内容融合增强和多任务预测解码器。

- 实验部分：

Bi-SRNet中训的结果并不是很高

second: 

miou:71.95 sek：20.29 score:35.79

landsat:

miou:85.65 sek：51.14 score:61.49 

我们进一步将每个数据集以7:1:2的比例随机划分为训练集、验证集和测试集。为了更好地利用GPU进行训练，我们将图像补丁的大小统一调整为256×256
