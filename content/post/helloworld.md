---
title: "Helloworld"
date: 2018-09-13T11:41:48+08:00
draft: false
---

#### hugo

`hugo`是一个静态站点生成器。简单、易用、高效。

#### 安装

下载地址：https://github.com/gohugoio/hugo/releases

下载得到：hugo_0.48_Windows-64bit.zip

解压缩文件，并将解压缩后的目录路径配置到系统环境变量中。

验证配置是否有效，打开`cmd`执行：

```
$ hugo version
```

#### 使用

创建一个静态站点

```
$ hugo new site mysite
```

进入站点目录

```
$ cd mysite
```

新建一篇文章

```
$ hugo new post/helloworld.md
```

执行完后，会在`content/post`目录中生成对应的文件。

