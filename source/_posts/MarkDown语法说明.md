---
title: MarkDown语法示例
date: 2022-04-22 14:01:27
tags: 前端
---

这篇博客主要用于展示 Markdown 的各种语法以及其在当前主题下的实际渲染效果。

## 1. 图片 (Images)

图片展示如下：

**语法：**
```markdown
![取色器](/images/color-picker.png "取色器")
```

**效果：**

![取色器对比度](/images/color-picker.png "取色器对比度")

---

## 2. 标题 (Headings)

**语法：**
```markdown
# 标题模块 Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

Heading level 1
===============

Heading level 2
---------------
```

**效果：**
# 标题模块 Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

Heading level 1
===============

Heading level 2
---------------

---

## 3. 段落与换行 (Paragraphs & Line Breaks)

**语法：**
```markdown
这里是段落

段落2.0

This is the first line.  
And this is the second line.
```

**效果：**
这里是段落

段落2.0

This is the first line.  
And this is the second line.

---

## 4. 文字着重显示 (Emphasis)

**语法：**
```markdown
*斜体*  _斜体2_

**加粗** __粗体__

***斜体并且加粗***
```

**效果：**
*斜体*  _斜体2_

**加粗** __粗体__

***斜体并且加粗***

---

## 5. 引用 (Blockquotes)

**语法：**
```markdown
> 高亮显示
>
> 段落高亮
> > 嵌套
```

**效果：**
> 高亮显示
>
> 段落高亮
> > 嵌套

---

## 6. 列表 (Lists)

**语法：**
```markdown
1. 11111
2. 22222
3. 4444
   1. 4.1
   2. 4.2
4. 55555

+ 11111111
+ 2222222
  + 2.1
  + 2.2
+ 33333

- ssss
- ssss
- ssss
```

**效果：**
1. 11111
2. 22222
3. 4444
   1. 4.1
   2. 4.2
4. 55555

+ 11111111
+ 2222222
  + 2.1
  + 2.2
+ 33333

- ssss
- ssss
- ssss

---

## 7. 代码块 (Code Blocks)

**语法：**
````markdown
    <html>
        <head>
        <title>Test</title>
    </head>

```html
<html>
    <head>
    <title>Test</title>
</head>
```

`function (str) { var aaa = str }`

``Use `code` in your Markdown file.``
````

**效果：**
    <html>
        <head>
        <title>Test</title>
    </head>

```html
<html>
    <head>
    <title>Test</title>
</head>
```

`function (str) { var aaa = str }`

``Use `code` in your Markdown file.``

---

## 8. 分隔线 (Horizontal Rules)

**语法：**
```markdown
---

***
```

**效果：**
---

***

---

## 9. 链接 (Links)

**语法：**
```markdown
[点击跳转到百度](https://www.baidu.com "百度")

<https://www.baidu.com>  
<email@163.com>

### <span id="heading-ids">锚点</span>
[跳转到锚点](#heading-ids)
```

**效果：**
[点击跳转到百度](https://www.baidu.com "百度")

<https://www.baidu.com>  
<email@163.com>

### <span id="heading-ids">锚点</span>
[跳转到锚点](#heading-ids)

---

## 10. 扩展语法 (Extended Syntax)

**语法：**
```markdown
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

**效果：**
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

\* 如果没有反斜杠，这将是无序列表中的项目符号.
