# 目录结构

gitbook 目录结构如下：

```
.
├── book.json
├── README.md
├── SUMMARY.md
├── Glossary.md
├── chapter-1/
|   ├── README.md
|   └── something.md
└── chapter-2/
    ├── README.md
    └── something.md
```

## book.json


存放配置信息，在下一章中所讲的配置信息都是在这个文件里定义的，关于该文件的配置可以看[配置](./configuration.md) 这个章节。

## README.md

`README.md`主要是存放关于本书信息的配置，默认对应的文件是`README.md`，也可以通过[修改配置](./configuration.md#readme)重新定义该文件的对应值，如果该文件不存在，则使用[初始化](./common-commands.md#初始化目录文件)时候会自动创建

## SUMMARY.md

`SUMMARY.md`主要存放 GitBook 的文件目录信息，左侧的目录就是根据这个文件来生成的，默认对应的文件是 `SUMMARY.md`，也可以通过[修改配置](./configuration.md#summary)重新定义该文件的对应值,
如果该文件不存在，则使用[初始化](./common-commands.md#初始化目录文件)时候会自动创建
它通过 `Markdown` 中的列表语法来表示文件的父子关系，下面是一个简单的示例：

> 使用`* [目录名称](文件相对路径)`来表示目录，使用`--------`，分割为不同的区块，使用`tab`缩进来表示不同的目录层级

```
* [Introduction](README.md)
* [学习日记](study/study.md)
    * [gitbook](study/gitbook/introduction.md)
        * [环境配置](study/gitbook/environment-configuration.md)
        * [常用命令](study/gitbook/common-commands.md)
        * [目录结构](study/gitbook/directory-structure.md)
        * [配置](study/gitbook/configuration.md)
        * [基本使用](study/gitbook/basic-use.md)
        * [插件介绍](study/gitbook/plug-in.md)
        * [文档分享](study/gitbook/documents-sharing.md)
----------
* [工作文档](diary/diary.md)
    * [2018年](diary/2018/2018-summary.md)
        * [08月](diary/2018/08.md)
        * [09月](diary/2018/09.md)

```

结果如下：

![目录层级结构](./img/directory-structure1.png)


## Glossary.md

词汇表文件，默认对应的文件是 `GLOSSARY.md`, 也可以通过[修改配置](./configuration.md#glossary)重新定义该文件的对应值该文件主要存储词汇信息，如果在其他页面中出现了该文件中的词汇，
鼠标放到词汇上会给出词汇示意，可以将鼠标移到下面两个词汇上看下效果。

Git    Markdown




