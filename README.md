# 时政工作知识库

## 创作想法
前期参加了浦语InternLM第一期的实战营，想通过一次比赛巩固一些知识点，和尝试一些课程以外的应用

## 模型使用Internlm2-chat-1_8b
地址：[https://www.modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-chat-1_8b/](https://www.modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-chat-1_8b/)

## 数据集
来自OpenDataLab网站的党务问答数据集
地址：[https://opendatalab.com/政杰/PartyAffairsResponse](https://opendatalab.com/政杰/PartyAffairsResponse)

## 主要操作
通过是Xtuner对Internlm2-chat-1_8b使用数据集进行了微调，在微调完后的模型上使用langchain加载比赛的数据集以及一些自己收集的一些史料文档进行了知识库的建立后完成。展示采用的是gradio进行

## 演示视频地址
[https://www.bilibili.com/video/BV1tm411o7tw](https://www.bilibili.com/video/BV1tm411o7tw)
