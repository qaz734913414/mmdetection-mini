# mmdetection-mini
mmdetection的mini版本，主要包括一阶段目标检测器，结构和
mmdetection完全一致，系统通过从头构建整个框架来数学所有细节

## 1 介绍

   完全基于mmdetection框架结构,简称mmdet最简学习版，**基于最简实现，第一原则就是简洁，不会加入一些乱七八糟的功能，一步一步构建一阶段目标检测器**。主要目的为在从0构建整个框架的基础上，掌握整个目标检测实现细节。 

   由于只有一张显卡，故不支持分布式训练，而**本项目目的是学习,希望通过从0构建每一行代码，来熟悉每个部分，而且自己写的框架，后续我新增一些新特性也非常容易**。更新可能是快时慢。在掌握每个细节后才会增加新代码，欢迎有兴趣的朋友共同学习，也欢迎提出意见。

## 2 提交日志
[文档链接](./docs/changelog.md)

## 3 已实现模型仓库
[文档链接](./docs/model_zoo.md)


## 4 进行中模型
- [x] retinanet
- [x] yolov3
- [x] darknet-yolov3
- [x] darknet-yolov4
- [x] darknet-tiny_yolov3
- [x] darknet-tiny_yolov4


## 5 安装说明
[文档链接](./docs/install.md)


## 6 统一数据集
   由于coco训练集图片太多了，跑到论文效果需要非常多时间，而本框架目的主要目的是快速验证
思想和算法(代码和mmdetection一致，应该没有错误)，故对主要以voc为主：
- coco
- voc2012和voc2007
- wider face


## 7 笔记(持续更新)
https://www.zybuluo.com/huanghaian/note/1740535