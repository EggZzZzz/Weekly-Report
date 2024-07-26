# Weekly-Report
## 7.26
1. 在上周，我学习了**Diffusion Model（扩散模型）**，理解了其基本概念和数学原理。主要是通过两个传播算法生成图像。在前向过程，通过对一张干净的图像逐步添加高斯噪声，经过足够多的T步之后得到了一张完全被高斯噪声覆盖的图像。在反向过程中，通过预测前一步到当前步的噪声，再利用当前图像减去预测出来得到的噪声，得到前一步的图像。逐步去噪，就能得到原始图像x0.在反向过程，主要使用到的是贝叶斯公式。  
2. 另外还阅读了**FRI-Net Floorplan Reconstruction via Room-wise Implicit Representation**该论文。该论文提出的FRI-Net主要通过三个模块：Pre-processing、Room-wise Encoder和Room-wise Decoder对输入的3D点云图进行平面图重建。  
3. 正在尝试跑通Holodeck这个project，但是遇到了一些困难。他需要用到gpt-4-1106-preview这个大模型，需要用到一个openai_api_key，另一个project好像也要用到这个key，我没有这个key。  
