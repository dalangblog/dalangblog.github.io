# [DA Lang Blog](https://dalangblog.github.io)

Here is the **`English`** version of **`README.md`** .

If you want to browse the **`Chinese README.md`** , please 👇

- [中文](https://github.com/dalangblog/dalangblog.github.io/blob/main/_doc/README.zh.md) 

> Standing on the shoulders of giants

Welcome to my blog👦. 

The tutorial for building the blog was modified from [Hux](https://github.com/Huxpro/huxpro.github.io) 

![](https://github.com/dalangblog/dalangblog.github.io/blob/main/img/avatar.jpg?raw=true)

## [User Manual 👉](https://github.com/dalangblog/dalangblog.github.io/blob/main/_doc/Manuals.en.md)

### Getting Started

**`Beginner's Guide`** ：Anyone can successfully build their own blog according to this tutorial, even if they are new to Github.

- You can fork my blog directly, or download the code locally, modify it and upload it to Github

- Then change the operation in order to match the individuality of each person.

- The priority is to modify the _config.yml and CNAME files in the root directory.

```shell
# _config.yml
title: DA Lang						# Blog site title
SEOTitle: DA Lang | 博客             # Title displayed on browser tab
header-img: img/post-home.jpg		# Images displayed on the home page of the blog
email: xxxxxx@gmail.com				# email
description: "咸鱼一条！" 			 # Home page description, can also be omitted

# Please refer to the detailed user manual for more details.
```

- Customize the domain name, if you do not have a domain name, please delete leave blank.

```shell
# CNAME
dalangblog.ga
```

- Finally write a test post Hello World!
- All posts are stored in the _post folder. So after writing your blog, please upload it to this folder.
- Create a new .txt suffix file and copy the following content, save it and exit.
- The file name format for blog posts is 'YYYY-MM-DD' + 'post name', so please rename the txt file to conform to the above rule.
- It is recommended to replace spaces in the file name with '-'
- Example: 2021-04-29-HelloWorld.md

```shell
# Test post: Copy the following content.
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

# Please refer to the detailed user manual for more details.
```



**Interesting to know more? Checkout the [full user manual](_doc/Manual.md) ！**

- [zh  中文文档](https://github.com/dalangblog/dalangblog.github.io/blob/main/_doc/Manuals.zh.md)
- [en  English Documents](https://github.com/dalangblog/dalangblog.github.io/blob/main/_doc/Manuals.en.md)

## [image-dalangblog](https://github.com/dalangblog/image-dalangblog)

The location of the images in my blog posts

## Acknowledgments

* [huxpro](https://github.com/Huxpro/huxpro.github.io) 's blog theme

## License

Apache License 2.0.
Copyright (c) 2015-present Huxpro

Hux Blog is derived from [Clean Blog Jekyll Theme (MIT License)](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/blob/master/LICENSE)
Copyright (c) 2013-2021 Start Bootstrap LLC
