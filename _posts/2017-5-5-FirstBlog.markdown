---
layout:     post
title:      "第一篇博客"
subtitle:   "First Blog"
date:       2017-5-5
author:     "MOA_iOS"
header-img: "img/post-bg-ios9-web.jpg"
catalog:    true
tags:
    - iOS
---

### 第一篇团队博客

该博客挂靠在github上，服务器和域名都是github的，所以是免费的；

#### 写博客

**博客的命名很重要**
博客的命名格式如下：yyyy-mm-dd-title.markdown

**博客的标题使用如下：**

```c
layout:     post
title:      "第一篇博客"
subtitle:   "First Blog"
date:       2017-5-5
author:     "MOA_iOS"
header-img: "img/post-bg-ios9-web.jpg"
catalog:    true
tags: - iOS
```
**基本只要注意几点：**
title就是文章的标题，subtitle可不填，date日期必填，author就是作者。tags就是分类

**写博客使用的语法是Markdown，该语法基本使用如下：**

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

- 文本1
- 文本2
- 文本3

1. 文本1
2. 文本2
3. 文本3

[简书](http://www.jianshu.com)

插入图片有一点区别：

md语法：![](图片链接地址)

博客的插入图片为：<img src="https://MOAiOS.GitHub.io/images/xxxx.png" />，然后需要将xxxx.png放入images文件夹下


**加粗**

代码文本'NSString'

插入代码：

```objective_c
NSLog("hello world!");
```
#### 上传博客

clone 该博客项目到本地，然后将写的博客放入post目录下，提交就OK了，可以用同一个账号提交，也可以用多个
