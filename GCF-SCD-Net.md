# Dual-T ask Semantic Change Detection for Remote Sensing Images Using the Generative Change Field Module

- 主要思想 

提出了一种双任务语义变化检测网络（GCF-SCD-Net），通过使用生成变化域（GCF）模块来定位和分割变化区域。同时，由于不平衡标签的影响，提出了一个可分离的损失函数来缓解过拟合问题。

使用二进制变化检测分支来指导两个语义分割网络预测像素的类别

第一个利用生成变化场方法来指导两个分支网络实现双任务语义变化检测

可分离损失函数
