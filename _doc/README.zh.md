# [大郎的博客](https://dalangblog.github.io)

这里是 **`中文版`** 的 **`README.md`**。

如果要浏览 **`English README.md`** ，请返回此项目的主页查看 👇！

- [English](https://github.com/dalangblog/dalangblog.github.io)

> 站在巨人的肩膀上

欢迎来到我的博客👦。

建立博客的教程是由[Hux](https://github.com/Huxpro/huxpro.github.io)修改的。

![](https://github.com/dalangblog/dalangblog.github.io/blob/main/img/avatar.jpg?raw=true)

## 用户手册 👉

### 入门

**`新手指南`** ：任何人都可以根据本教程成功建立自己的博客，即使他们是Github的新手。

- 你可以直接fork我的博客，或者在本地下载代码，修改后上传至Github。

- 然后修改配置，以符合每个人的个性。
- 首先修改根目录下的_config.yml和CNAME文件。

```shell
# _config.yml
title: DA Lang						# 博客网站标题
SEOTitle: DA Lang | 博客             # 浏览器标签上显示的标题
header-img: img/post-home.jpg		# 博客首页显示的图片
email: xxxxxx@gmail.com				# 邮箱
description: "咸鱼一条！" 			 # 主页描述，也可以省略

# 更多细节请参考详细的用户手册。

```

- 自定义域名，如果你没有域名，请删除留空。

```shell
# CNAME
dalangblog.ga
```

- 最后写一个测试帖子 HelloWorld。
- 所有的帖子都存储在_post文件夹中。所以在写完你的博客文章后，请把它上传到这个文件夹。
- 创建一个新的.txt后缀文件并复制以下内容，保存后退出。
- 博客文章的文件名格式是 "YYY-MM-DD "+"文章名"，所以请重新命名txt文件以符合上述规则。
- 建议用“-”替换文件名中的空格。
- 例如：2021-04-29-HelloWorld.md。

```shell
# 测试帖子：复制以下内容
---
layout:     post
title:      Hello World ！
subtitle:   你好，世界 ！
date:       2021-04-29
author:     DA Lang
header-img: img/post-20210429-HelloWorld.jpg
catalog: true
tags:
    - 测试
---

**HelloWorld**

测试 `Markdown` 的页面

> 你好，世界 ！🌏

# 请参考详细的用户手册了解更多细节。
```



**有兴趣了解更多？请查看[完整的用户手册](Manuals.en.md) ！**

- [zh  中文文档](https://github.com/dalangblog/dalangblog.github.io/blob/main/_doc/Manuals.zh.md)
- [en  English Documents](https://github.com/dalangblog/dalangblog.github.io/blob/main/_doc/Manuals.en.md)

## [image-dalangblog](https://github.com/dalangblog/image-dalangblog)

我的博客文章中图片存放的位置。

## 致谢

- [huxpro](https://github.com/Huxpro/huxpro.github.io) 的博客主题

## License

Apache License 2.0.
Copyright (c) 2015-present Huxpro

Hux Blog is derived from [Clean Blog Jekyll Theme (MIT License)](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/blob/master/LICENSE)
Copyright (c) 2013-2021 Start Bootstrap LLC
