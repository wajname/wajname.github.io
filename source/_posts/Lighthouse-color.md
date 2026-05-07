---
title: Lighthouse 颜色对比度审查
date: 2022-05-26 14:46:32
tags: 前端 无障碍审核
---
### 在Lighthouse有关无障碍审查时，会将背景色与前景色对比度不足的文本标记出来：
![Lighthouse 报错](/images/lighthouse-error.png "Lighthouse 报错")
### Lighthouse 使用[WCAG 2.1 的成功标准 1.4.3](https://www.w3.org/TR/WCAG21/#contrast-minimum)来评估文本的颜色对比度：
+ 18 pt 或 14 pt 加粗的文本需要的对比度为 3:1。
+ 所有其他文本需要的的对比度为 4.5:1。
### 在Chrome DevTools 的颜色选取器中可以查看并调整颜色对比度：
1. 右键单击（在Mac上按住Command键单击）要检查的元素，然后选择 Inspect（检查）。  
2. 在 Elements（元素）窗格的 Styles（样式）选项卡中，找到 color 值。
3. 单击值旁边的颜色缩略图。

![取色器对比度](/images/color-picker.png "取色器对比度")