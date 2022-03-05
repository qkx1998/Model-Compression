# Model-Compression
模型压缩demo（剪枝、量化、知识蒸馏）


模型压缩的动机：我们希望有一个规模较小的模型，能达到和大模型一样或相当的结果。<br/>
<br/>
主要有以下一些方向：<br/>
1 加速网络设计：分组卷积，分解卷积，神经网络搜索<br/>
2 Winograd,模型裁剪与稀疏化：FFT/Winograd，模型剪枝，核的稀疏化<br/>
3 量化加速：二值权重网络，二值神经网络，同或网络，三值权重网络，量化神经网络<br/>
4 知识蒸馏