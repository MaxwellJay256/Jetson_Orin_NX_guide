# Jetson Orin NX guide

亚博智能 Jetson Orin NX 课程资料文档个人汉化

原文档地址：[YahboomTechnology/Jetson_Orin_NX - GitHub](https://github.com/YahboomTechnology/Jetson_Orin_NX)

产品详情页：[Jetson Orin NX 详情 - 亚博](https://www.yahboom.com/tbdetails?id=550)

官方中文课程资料：[Jetson Orin NX - 亚博](https://www.yahboom.com/study/Jetson-Orin-NX)

#### 为什么读我而不是官方文档？

1. 官方中文文档需要提取码。如果开发套件并非一手购买则无法获取。
2. 本仓库的文档在汉化的同时对照官方中文文档改正了语病，并且加入了[「盘古之白」](https://xiaoquankong.ai/zh/posts/chinese-document-typesetting-specification-spacing-of-pangu/)。
3. 文档使用 Markdown 格式保存，你可以用自己喜欢的方式阅读，包括 Typora、导出 PDF 等。
4. 我之所以翻译这套文档，是因为我也在用它。我会根据自己的理解和实际经验，改进文档的表达，使其更易懂。

## 目录

### 第 1 章 快速上手

[1.1. 学习路线](1%20快速上手/1.1%20学习路线.md)

[1.2. 快速上手教程](1%20快速上手/1.2%20快速上手教程.md)

### 第 2 章 基础教程

2.1 Jetson Orin NX 介绍

2.2 SDKmanager 烧写系统

2.3 固态盒子烧写系统

2.4 备份 NVMe 系统

2.5 已烧写 SSD 重写系统

2.6 NVMe 系统扩容

### 第 3 章 系统设置

[3.1 Jetson Orin NX 启动](3%20系统设置/3.1%20Jetson%20Orin%20NX%20启动.md)

3.2 Jetson Orin NX 系统及桌面介绍

3.3 网络配置

3.4 SSH 远程登录 / 文件传输

3.5 VNC 远程桌面配置

3.6 Jtop 工具安装及使用

### 第 4 章 GPIO 硬件控制

[4.1 GPIO 库的 API 用法](4%20GPIO%20硬件控制/4.1%20GPIO%20库的%20API%20用法.md)

[4.2 硬件库配置](4%20GPIO%20硬件控制/4.2%20硬件库配置.md)

4.3 引脚读取功能

4.4 引脚电平输出控制

4.5 控制 LED

4.6 Jetson Orin NX 与外部设备串口通信

4.7 Jetson Orin NX I2C 通信

### 第 5 章 AI 视觉进阶教程

5.1 摄像头测试

5.2 Jupyter Lab 和 Jetcam 安装

*5.3 安装 TensorFlow

*5.4 安装 Torch 和 TorchVision

*5.5 jetson-inference 环境搭建

5.6 Hello AI World

5.7 图像分类推理

5.8 训练图像分类模型

5.9 目标检测推理

5.10 训练目标检测模型

5.11 语义分割

5.12 动作识别

5.13 姿态估计

5.14 背景去除

5.15 单眼深度估计

*5.16 DeepStream 环境搭建

5.17 汽车识别

5.18 姿态检测

5.19 yolo5 简介

*5.20 yolo5 环境搭建

5.21 yolo5 的实时检测

5.22 yolo5 + TensorRT 加速

5.23 yolo5 + TensorRT 加速 + DeepStream（打开摄像头）

*5.24 MediaPipe 环境搭建

5.25 MediaPipe 开发

### 第 6 章 ROS1 进阶教程

#### ROS1 基础教程

[6.1 ROS 简介](./6%20ROS1%20进阶教程/6.1%20ROS%20简介.md)

6.2 项目文件结构

6.3 常用命令与工具

6.4 发布者

6.5 订阅者

6.6 自定义话题消息与使用

6.7 客户端

6.8 服务端

6.9 自定义消息与使用

6.10 TF 发布与监听

#### ROS1 视觉图像处理

6.11 AR 视觉

6.12 AR 二维码

6.13 ROS + OpenCV 基础

6.14 ROS + OpenCV 应用

6.15 MediaPipe 开发

### 第 7 章 ROS2 进阶教程

### 第 8 章 离线 AI 大模型开发

## License

This repository is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
Details in the [LICENSE](LICENSE) file.
