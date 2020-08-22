---
title: markdown语法
date: 2020-08-21 16:02:54 
author: 赤橙Ryota
cover: false
categories: 笔记
tags:
  - Typora
  - Markdown
---

# markdown语法

## 1.代码块

```shell
代码块语法: ctrl shift K
​```加上语言类型```
```

```javascript
function foo() {
    var a = 10
    console.log(a)
}
```

```shell
部分代码: ctrl shift ``
`代码内容`
```

``var a = 10``

`var a = 20`



## 2.标题

```shell
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

`ctrl 0`到`ctrl 4`:普通文本、一级到四级标题



## 3.字体

```shell
//加粗 ctrl B
**加粗内容**

//斜体 ctrl I
*斜体内容*

//加粗斜体
***加粗斜体内容***

//删除线 shift alt 5
~~删除线内容~~

//下划线 ctrl U
<u>下划线内容</u>

//代码高亮
==代码高亮内容==
```

**加粗内容**

*斜体内容*

***加粗斜体内容***

~~删除线内容~~

<u>下划线内容</u>

==代码高亮内容==



## 4.引用

```shell
// 引用语法
>作者:某某某
>>作者:某某某
>>>作者:某某某
```

>作者:某某某
>
>>作者:某某某
>>
>>>作者:某某某  



## 5.分割线

```shell
// 分割线1
--- 、___
***
```



---



***



## 6.图片

```shell
// 在线图片/本地图片 ctrl shift I
![图片名称](图片路径)
![我的图片](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1597578639923&di=bf1a410b9aa501c6db4e869903fe8a1d&imgtype=0&src=http%3A%2F%2Fc.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2F0824ab18972bd407ff38f2b378899e510eb30984.jpg)
```

![我的图片](MarkDown入门级语法.assets/timg)



## 7.超链接

```shell
// 超链接语法 ctrl K
[链接名](链接地址)
[bilibili](https://www.bilibili.com/)
<https://www.bilibili.com/>
```

[bilibili](https://www.bilibili.com/)

<https://www.bilibili.com/>



## 8.列表

```shell
// 无序列表 -、+、*
- 列表一
- 列表二
- 列表三

// 有序列表 1.
1. 列表一
2. 列表二
3. 列表三

// 列表嵌套
* 一级列表
  * 二级列表
  	* 三级列表
```

- 列表一
- 列表二
- 列表三



1. 列表一
2. 列表二
3. 列表三



* 一级列表
  * 二级列表
    * 三级列表



## 9.注释

```shell
待解释[^1]
[^1]: 1就是1
```

待解释[^1]

[^1]: 1就是1



## 10.表格

```shell
// 第一行自带加粗效果，
// 第二行分割标题和内容，添加冒号代表对齐方式
// ctrl T插入表格
| 姓名 | 性别 | 年龄 |
|:----|:----:|----:|
| 张三 | 男 | 18 |
| 李四 | 男 | 28 |
```

| 姓名 | 性别 | 年龄 |
| :--- | :--: | ---: |
| 张三 |  男  |   18 |
| 李四 |  男  |   28 |