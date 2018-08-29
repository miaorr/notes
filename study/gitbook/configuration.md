# 配置


## title

设置书本的标题

```
"title" : "Gitbook Use"
```
## author

作者的相关信息

```
"author" : "miaor"
```

## description

本书的简单描述

```
"description" : "记录Gitbook的配置和一些插件的使用"

```

## language

Gitbook使用的语言, 版本2.6.4中可选的语言如下：

```
en, ar, bn, cs, de, en, es, fa, fi, fr, he, it, ja, ko, no, pl, pt, ro, ru, sv, uk, vi, zh-hans, zh-tw

```

配置使用简体中文

```
"language" : "zh-hans",
```

## gitbook

指定使用的gitbook版本

```
"gitbook" : "3.2.2",
"gitbook" : ">=3.0.0"

```

## root

指定存放 GitBook 文件（除了 book.json）的根目录

```

"root": "."

```

## links

在左侧导航栏添加链接信息
```
"links" : {
    "sidebar" : {
        "Home" : "http://zhangjikai.com"
    }
}
```

## styles

自定义页面样式， 默认情况下各generator对应的css文件

```
"styles": {
    "website": "styles/website.css",
    "ebook": "styles/ebook.css",
    "pdf": "styles/pdf.css",
    "mobi": "styles/mobi.css",
    "epub": "styles/epub.css"
}
```

例如使`<h1> <h2>`标签有下边框， 可以在`website.css`中设置

```
h1 , h2{
    border-bottom: 1px solid #EFEAEA;
}
```

## structure

指定 Readme、Summary、Glossary 和 Languages 对应的文件名，下面是这几个文件对应变量以及默认值

|变量| 	含义和默认值|
|---|---|----|
|structure.readme| 	Readme file name (默认：README.md)|
|structure.summary| 	Summary file name (默认：SUMMARY.md)|
|structure.glossary| 	Glossary file name (默认：GLOSSARY.md)|
|structure.languages| 	Languages file name (默认：LANGS.md)|

### readme

本书的说明文档

```
"structure": {
    "readme": "README.md",
}
```
### summary

本书的目录文档

```
"structure": {
    "summary": "SUMMARY.md",
}
```

### glossary

本书的词汇说明文档

```
"structure": {
    "glossary": "Glossary.md",
}
```

### languages

本书的语言文档

```
"structure": {
    "languages": "LANGS.md",
}
```


## plugins

配置使用的插件，具体参照[插件介绍](./plug-in.md)

```
"plugins": [
    "disqus"
]
```


## pluginsConfig

配置插件的属性
```
"pluginsConfig": {
    "fontsettings": {
        "theme": "sepia",
        "family": "serif",
        "size":  1
    }
}

```
