---
title: 防御性css
date: 2022-09-30 08:41:00
tags: 前端
---

## 一、flex-wrap

flex-wrap是flex布局中的属性，其作用是控制flex容器内元素所占空间超出flex容器空间时是否折行。
flex-wrap属性默认是不折行，容易忽略多元素溢出兜底；为兜底，请设置flex-wrap: wrap;

```css
.list {
    display: flex;
    flex-wrap: wrap;
}
```

## 二、margin间距

margin作用是调整元素的外边距。用于指定元素与周围空间的距离关系。
防止元素与元素之间挤压空间，造成重叠等情况；

```css
.title {
    margin-right: 1rem;
}
```

## 三、长文本处理

当文本长度超出容器时,超出部分以省略显示,使得列表表现一致

```css
.list {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}
```

## 四、防止图像被拉伸或压缩

服务器下发的图片尺寸以及用户自定义上传的图片，显示在页面时，不可能百分百与容器尺寸贴合，不可避免的会遇到图片的放缩处理。

```css
.card__thumb {
    object-fit: cover;
}
```