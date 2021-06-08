---
layout:     post
title:      使用Typora工具优雅的输出博客文章
subtitle:   一款优秀的Markdown文本编辑器
date:       2021-05-29
author:     DA Lang
header-img: img/post-20210529-Typora.jpg
catalog: true
tags:
    - 软件
    - Markdown
    - Typora
---

# 1 Typora工具

![post-Typora-000](https://cdn.jsdelivr.net/gh/dalangblog/image-dalangblog@main/20210529/post-Typora-000.jpg)

先上官网地址，👉 [Typora](https://typora.io/) 官网

一个基于 Markdown 语言的文本编辑器，支持实时预览的 Markdown 文本编辑器。**OS X**、**Windows**、**Linux** 

三个平台的版本目前均`免费`，支持导出`HTML`，`PDF`，`Word`，`图片`等多种格式。它极简的设计理念让我感觉到不可思议，实在是太好用了！

> 斑：我愿称之为最强😂

![post-Typora-001](https://cdn.jsdelivr.net/gh/dalangblog/image-dalangblog@main/20210529/post-Typora-001.jpg)

## 1.1 我的博客编写规范

#### 1.1.0 博客前缀

```shell
# 博客的开头的格式说明
---						# --- + 回车
layout:     post				#
title:      使用Typora工具优雅的输出博客文章	# 标题
subtitle:   一款优秀的Markdown文本编辑器		# 小标题
date:       2021-05-29				# 创建日期
author:     DA Lang				# 作者
header-img: img/post-20210529-Typora.jpg	# 文章开头顶部显示的图片
catalog: true					# 默认即可
tags:						# 标签
    - 软件
    - XXX
    - ...
# 直接拷贝
layout:     post
title:      使用Typora工具优雅的输出博客文章
subtitle:   一款优秀的Markdown文本编辑器
date:       2021-05-29
author:     DA Lang
header-img: img/post-20210529-Typora.jpg
catalog: true
tags:
    - 软件
    - Markdown
    - Typora
```

#### 1.1.1 文章内序号格式

![post-Typora-002](https://cdn.jsdelivr.net/gh/dalangblog/image-dalangblog@main/20210529/post-Typora-002.jpg)

#### 1.1.2 地址，图片超链接

```shell
Ctrl + K
[百度搜索](www.baidu.com)
<https://www.baidu.com>
```

[百度搜索](www.baidu.com)
<https://www.baidu.com>

#### 1.1.3 插入图片

```shell
Ctrl + shift + i
![post-Typora-000](https://cdn.jsdelivr.net/gh/dalangblog/image-dalangblog@main/20210529/post-Typora-000.jpg)
```

![post-Typora-000](https://cdn.jsdelivr.net/gh/dalangblog/image-dalangblog@main/20210529/post-Typora-000.jpg)

#### 1.1.4 文章内跳转

```shell
[跳转表格](# 1.1.13 表格)	# Ctrl + 点击
				# Ctrl + J
```

~~博客中无效 [跳转表格](# 1.1.13 表格)~~

Github中可以生效（可用来写README.md）

> **在浏览器中用网址打开无法使用跳转功能，可在Typora中生效**

#### 1.1.5 代码块

```shell
​``` + shell/python/C++等语言
```

#### 1.1.6 引用

```shell
> 这是一条引用
```

> 这是一条引用

#### 1.1.7 高亮效果

````shell
`X`，``XX``效果一样
````

`高亮效果` ``高亮效果``

#### 1.1.8 分级标题

```shell
# + 空格 + 标题内容	# 几个'#'，就几级标题
Ctrl + 1\2\3\...	# 数字为几，就几级标题
```

#### 1.1.9 黑⚪序号

```shell
-/+/* 空格	# 第一次输入任意一个'-'，或'+',或'*'加空格为实心黑●
		# 第二次输入任意一个'-'，或'+',或'*'加空格则为空心⚪
		# 第三次输入任意一个'-'，或'+',或'*'加空格则为实心黑方块■
```

- - -

#### 1.1.10 字体格式

```shell
*斜体* , _斜体_	# Ctrl + I
**粗体**	# Ctrl + B
***加粗斜体***	# Ctrl + B + Ctrl + I
~~删除线~~	# Alt + Shift + 5 	
<u>下划线</u>	# Ctrl + U
***分割线 , ---	# Ctrl + 
```

*斜体* , _斜体_
**粗体**
***加粗斜体***
~~删除线~~
<u>下划线</u>

***

#### 1.1.11 任务列表

```shell
点击‘菜单’选择‘任务列表’
吃饭
睡觉
打豆豆
```

- [x] 吃饭

- [ ] 睡觉

- [ ] 打豆豆 

#### 1.1.12 标注

```shell
概念A[^1]
[^1]:解释语
```

概念A[^1]

[^1]:解释语

#### 1.1.13 表格

```shell
|姓名|年龄|性别|学校| + 回车
```

| 姓名 | 年龄 | 性别 | 学校 |
| ---- | ---- | ---- | ---- |
|      |      |      |      |

#### 1.1.14 HTML标签

由于Markdown中CSS样式是全局，所以无法利用CSS样式作局部设置。好在Markdown也兼容支持HTML标签，如此想实现什么都可以插入HTML标签实现

```shell
# 首先找到CSS定义的样式，例如图片的CSS样式如下👇，对照修改即可
}.post-container img {
	display:block;
	max-width:100%;
	height:auto;
	margin:1.5em auto 1.6em auto
}
# 直接插入图片，图片默认会居中显示且上下会增加间距
![](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)
# html标签，设置为左对齐，取消增加的间距
<img alt="知识共享许可协议" style="display:inline;margin:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
```

![](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

<img alt="知识共享许可协议" style="display:inline;margin:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />

# 2 突如其来的结尾

看到这里的你,已经知道大部分常用的Markdown的写作规范,开始编写属于你的第一篇`.md文件`吧!

# 致谢

- [Typora](https://typora.io/) 官网
- `打字机的图片:` 该图片由 [Free-Photos](https://pixabay.com/zh/photos/typewriter-book-notes-paper-801921/) 在 [Pixabay](https://pixabay.com/zh/) 上发布

---

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
<img alt="知识共享许可协议" style="display:inline;margin:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">知识共享署名-相同方式共享 4.0 国际许可协议</a>进行许可。
