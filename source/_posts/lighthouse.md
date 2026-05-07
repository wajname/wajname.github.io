---
title: 前端性能检测工具 -- lighthouse
date: 2022-05-24 16:14:27
tags: 前端
---
### 1.在Chrome DevTools中使用
        打开开发者工具，选择 Generate report，即可生成分析报告。可选择分析内容、设备类型。
![Lighthouse 面板](/images/lighthouse-tab.png "Lighthouse 面板")
<!--more-->
### 2.主要监控指标
        LightHouse主要采用了六个和用户体验直接相关的指标进行了展示：
        First Contentful Paint：首次内容渲染时间

Speed Index：速度指数

Largest Contentful Paint：最大内容渲染时间

　　Time to Interactive：可交互时间

　　Total Blocking Time：累计阻塞时长

　　Cumulative Layout Shift：累计布局偏移
### 3.问题与建议
        根据问题严重程度可以对网站进行相应的优化调整
### 4.优化调整实践
+ 图片压缩
+ 配置HTML的Viewport meta标签
+ 图像添加alt属性等（无障碍设计）
+ 避免DOM过大
+ 外部链接添加rel="noopener"等

