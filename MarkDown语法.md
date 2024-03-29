# 基本语法(个别语法有道云可用)
## 一、引用代码段
段落上下方使用3个反单引号对，有道云里只要上下数量相同就会被转义
```
源代码
###
这里用#替代`，反单引号就是Esc键下边那个。
###
```
## 二、多级标题
# 1可以理解为该篇文章的标题
## 2可以理解为该篇文章里的某一章标题
### 3可以理解为该章里的某一节标题
#### 4注意空格隔开
##### 5
###### 6
####### 7
```
源代码
# 1可以理解为该篇文章的标题
## 2可以理解为该篇文章里的某一章标题
### 3可以理解为该章里的某一节标题
#### 4注意空格隔开
##### 5
###### 6
####### 7
```
## 三、字符格式
*斜体*
**加粗**
~~划掉~~
++下划线++
==高亮==
```
源代码
*斜体*
**加粗**
~~划掉~~
++下划线++(有道云可用)
==高亮==(有道云可用)
```
## 四、图表
title1|title2|title3|居左|居中|局右
---|---|---|:--|:--:|--:
row1col1||row1col3|左|中|右
|||||
row3col1|row3col2|row3col3|||
```
源代码
title1|title2|title3|居左|居中|局右
---|---|---|:--|:--:|--:
row1col1||row1col3|左|中|右
|||||
row3col1|row3col2|row3col3|||
```
## 五、分割线
分割线,3个及以上的-或*
---
----
***
****

>引用，啥时候用呢？

>>>多级引用,一直加">"就行了。
```
源代码
分割线,3个及以上的-或*
---
----
***
****

>引用，啥时候用呢？

>>>多级引用,一直加">"就行了。
```
## 六、序列
无序序列，*\-\+任意，注意空格隔开。
* 1
- 2
+ 3
有序序列
1. 一级
   1. 二级
   2. 二级
2. 一级
   1. 二级
      1. 三级
         1. 四级
```
源代码
无序序列，*\-\+任意，注意空格隔开。
* 1
- 2
+ 3
有序序列
1. 一级
   1. 二级
   2. 二级
2. 一级
   1. 二级
      1. 三级
         1. 四级
```
## 七、流程图(有道云可用)
graph TB 从上到下
graph BT 从下到上
graph LR 从左到右
graph RL 从右到左
```
graph TD
A-->B
A-->C
```
```
源代码
###这里用#替代反单引号`哈
graph TD
A-->B
A-->C
###
```
## 八、插入图片
![image](http://note.youdao.com/favicon.ico)
```
源代码
![image](http://note.youdao.com/favicon.ico)
![图片下方的图注](图片地址)
```
## 九、插入链接
[link](http://note.youdao.com/)
```
源代码
[link](http://note.youdao.com/)
[链接名](链接地址)
```
Wiki也有MarkDown Edit，不过有道云预览更快。
