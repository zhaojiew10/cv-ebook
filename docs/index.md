---
title: "精通计算机视觉：从像素到生成式视觉"
---

# 精通计算机视觉：从像素到生成式视觉

一本依据完整课程字幕编写的中文计算机视觉电子书。全书将 **360 个课时**按知识主题整合为 **6 个部分、35 章**，并以 **39 幅课程原帧与 SVG 图例**辅助理解，从数字图像与卷积基础出发，逐步进入经典 CNN、目标检测、图像分割、生成模型、Vision Transformer 与大规模视觉检索。

[开始阅读：第 1 章](chapters/ch01.md)

> 本书以课程的中英文字幕为主要依据，保留理论推导、架构对比和代码讲解中的实质内容，删除口语重复并按知识逻辑重新组织。本书不附原视频和数据集，实践内容以操作流程与关键代码说明呈现。

## 推荐阅读方式

- **系统学习**：按第 1—35 章顺序阅读，建立从像素到现代视觉模型的完整知识路径。
- **视觉工程主线**：先读第 1—9 章，再学习第 16—25 章的目标检测与图像分割。
- **生成模型与 ViT 主线**：复习第 5—8 章后，直接阅读第 26—32 章。
- **视觉检索主线**：掌握 CNN 基础后，阅读第 33—35 章的嵌入、FAISS 与 CLIP。
- **快速查阅**：通过完整目录或章节标题定位术语；每章末尾的小结适合复习。

## 完整目录

## 第一部分 · 图像处理与计算机视觉基础

从语义鸿沟和经典视觉流程出发，掌握数字图像、几何与光度变换、卷积滤波及其实践。

- [第 1 章 计算机视觉：语义鸿沟、技术演进与通用流程](chapters/ch01.md)
- [第 2 章 数字图像：像素、矩阵、色彩空间与位深](chapters/ch02.md)
- [第 3 章 图像预处理：几何变换与光度调整](chapters/ch03.md)
- [第 4 章 卷积滤波与人脸识别预处理](chapters/ch04.md)

## 第二部分 · 深度学习与 CNN

沿神经网络、反向传播、卷积与池化建立理论基础，再用 PyTorch 完成 CNN 训练闭环。

- [第 5 章 从感知机到深度神经网络](chapters/ch05.md)
- [第 6 章 损失函数、反向传播与优化器](chapters/ch06.md)
- [第 7 章 卷积神经网络：从全连接到局部特征学习](chapters/ch07.md)
- [第 8 章 ReLU、池化与完整 CNN 架构](chapters/ch08.md)
- [第 9 章 PyTorch 实战：数据、模型、训练与评估](chapters/ch09.md)

## 第三部分 · 高级 CNN 与模型优化

比较经典骨干网络，掌握迁移学习、微调、训练诊断、数据增强和正则化。

- [第 10 章 经典 CNN 架构：LeNet、AlexNet 与 VGG](chapters/ch10.md)
- [第 11 章 ResNet、Inception、DenseNet 与 EfficientNet](chapters/ch11.md)
- [第 12 章 迁移学习与特征提取](chapters/ch12.md)
- [第 13 章 微调、分层学习率与持续学习](chapters/ch13.md)
- [第 14 章 训练诊断与性能改进工作流](chapters/ch14.md)
- [第 15 章 数据增强与正则化](chapters/ch15.md)

## 第四部分 · 目标检测

从检测指标和后处理出发，比较两阶段、单阶段与 Transformer 端到端检测器。

- [第 16 章 目标检测基础：输出、IoU、mAP 与 NMS](chapters/ch16.md)
- [第 17 章 两阶段检测器：R-CNN、Fast R-CNN 与 Faster R-CNN](chapters/ch17.md)
- [第 18 章 单阶段检测与 YOLO](chapters/ch18.md)
- [第 19 章 SSD：多尺度特征与默认框](chapters/ch19.md)
- [第 20 章 DETR：Transformer 检测流水线与二分匹配](chapters/ch20.md)

## 第五部分 · 图像分割

从像素级分类到实例掩码，理解 FCN、U-Net、Mask R-CNN 和可提示分割基础模型。

- [第 21 章 图像分割基础：语义、实例与像素级损失](chapters/ch21.md)
- [第 22 章 FCN 与编码器—解码器架构](chapters/ch22.md)
- [第 23 章 U-Net：跳跃连接、特征拼接与场景选择](chapters/ch23.md)
- [第 24 章 Mask R-CNN：实例分割、ROI Align 与多任务损失](chapters/ch24.md)
- [第 25 章 SAM：提示分割、整体架构与 SAM2／SAM3](chapters/ch25.md)

## 第六部分 · 生成模型、ViT 与视觉检索

覆盖自编码器、GAN、Vision Transformer、视觉嵌入、近似最近邻检索和 CLIP。

- [第 26 章 自编码器与潜在空间](chapters/ch26.md)
- [第 27 章 变分自编码器：概率建模、重参数化与损失](chapters/ch27.md)
- [第 28 章 GAN 与 DCGAN：对抗训练和稳定实现](chapters/ch28.md)
- [第 29 章 WGAN、StyleGAN 与 CycleGAN](chapters/ch29.md)
- [第 30 章 Vision Transformer：范式、架构与全局建模](chapters/ch30.md)
- [第 31 章 从图像块到 Token：自注意力与 ViT 编码器](chapters/ch31.md)
- [第 32 章 ViT 变体：ELA-ViT、HgVT、DeiT 与 Swin](chapters/ch32.md)
- [第 33 章 视觉嵌入与相似度学习](chapters/ch33.md)
- [第 34 章 大规模图像检索：FAISS、IVF、PQ 与 HNSW](chapters/ch34.md)
- [第 35 章 CLIP、多模态搜索与视觉嵌入应用](chapters/ch35.md)
