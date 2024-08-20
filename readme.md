# AIKnow

该项目用于AI知识学习记录、AI方向面试八股文整理、AI知识库搭建、常用工具库

## Knowledge

### 机器学习、深度学习基础

#### 传统方法 与 经典模型

支持向量机、聚类、随机森林、马尔科夫链

MLP

CNN

ResNet

RNN

LSTM

#### 优化器

#### 机器视觉方向 CV

hello，world: 手写数字识别

图像分类

目标检测

语义切割

#### 自然语言处理 NLP



#### 搜广推模型







### LLM基础

scaling law 大力出奇迹，模型越大效果越好

Transformer

框架 、原理、手搓Transfomer

#### 经典模型

Bert、GPT、T5、Llama、

开源、闭源LLM对比：

GPT4、Kimi、Yi、sparkAi、

Llama、Qwen、chatGLM、

### 大模型训练

#### 模型预训练

InstructGPT

GPT：预训练-微调-RLHF

#### 模型微调 Finetune

PEFT（LoRA、P-tuning等）

#### 训练调参经验

#### 分布式并行 （实操需GPUs条件）

参数服务器（PS架构 多GPU并行训练）、ZeRO系列（切片的数据并行）、Megatron-LM（张量并行）、Pathways、GPipe（流水线并行）、

PP模型并行（TP张量并行、流水线并行）、DP数据并行

通信域

通信量、显存分析、

#### 模型评估

评估指标、SOTA模型指标了解

#### 模型部署



### 大模型应用

#### Prompt 工程

#### RAG

向量数据库

文本检索

向量检索

多路召回

重排序



#### Agent

组成：LLM + 记忆 + 规划 + 工具

任务分解(两种)：CoT （Chain of Thinking） and ToT （Tree of Thinking） 

自我反思：

thought1 - act1 - observation1 - thought2 - act2 - observation2 - ......



### 视觉、视频理解

双流网络

### 多模态方向

ViT、CLIP、VAE、MAE、MoCo（CV 自监督学习）、Swin Transformer、ViLT视觉文本多模态

### 自动驾驶方向

#### 端到端模型 E2E model

#### 规划决策模型 Planning



DeepFake、GAN



### 图神经网络 GNN

### 强化学习

AlphaFold

## Code

用于存放相关代码实现

## Utils

用于存放一些好用的处理程序

## 读论文、论文写作

[跟李沐学AI的个人空间-跟李沐学AI个人主页-哔哩哔哩视频 (bilibili.com)](https://space.bilibili.com/1567748478/channel/collectiondetail?sid=32744)

跟李沐学AI课程【推荐】

1.如何读论文

2.如何找研究想法

3.如何判断研究工作的加载 

4.研究新意度Novelty

研究的艺术系列

（一）跟读者建立联系

（二）明白问题的重要性

（三）讲好故事、论点

（四）理由、论据和担保

大模型时代下科研的四个思路（预训练模型是不可能的！）