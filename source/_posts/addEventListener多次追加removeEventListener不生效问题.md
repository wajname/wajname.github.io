---
title: addEventListener多次追加removeEventListener不生效问题
date: 2022-05-22 14:06:37
tags:
---
### addEventListener用于追加事件，但是当我们多次调用该方法时，会导致多次触发的情况：

```js
var btn = document.getElementById('handBtn')   
refreshFun()

function refreshFun(){  
    btn.addEventListener('click',function(){
        alert('1')  
    })
}
```
### 这时候我们需要用到removeEventListener来移除上一次绑定追加的事件

```js
function refreshFun(){
    btn.removeEventListener('click',function(){
        alert('1')
    })
    btn.addEventListener('click',function(){
        alert('1')
    })
}
```

