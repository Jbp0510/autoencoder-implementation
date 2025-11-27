# autoencoder-implementation
A complete implementation of autoencoders with MNIST dataset
# 自编码器实现

## 项目描述
本项目使用TensorFlow/Keras实现基础自编码器，在MNIST手写数字数据集上进行图像压缩和重构实验，展示了无监督学习的核心概念。

## 实验目标
- 实现自编码器的编码-解码结构
- 学习数据压缩和特征提取
- 可视化图像重构效果
- 理解无监督学习的应用场景

## 实验结果
根据实验运行结果：
- **最终训练损失**: 0.0942
- **最终验证损失**: 0.0928  
- **模型结构**: 784 → 32 → 784 (压缩率约24:1)
- **数据集**: MNIST (60,000训练 + 10,000测试样本)

## 文件结构
