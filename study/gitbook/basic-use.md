# 如何发布


## 共同步骤

+ [初始化目录结构](./common-commands.md#初始化目录文件)

> 如果目录已经初始化，可以不进行本步骤

> 使用该命令时候，如果没有`SUMMARY.md`文件，会自动自动创建，生成时候会按照文件`book.json`中 `structure.readme`
创建一级目录结构，默认`structure.readme`对应的文件为`README.md`,如果`README.md`文件不存在也会创建

> 如果有`SUMMARY.md`文件，会按照`SUMMARY.md`文件中的目录结构自动生成没有创建的文件

```
gitbook init

```

+ [下载插件](./common-commands.md#插件下载)

如果插件已经下载，可以不进行本步骤

```
gitbook install
```


## 静态文件生成


+ [生成静态文件](./common-commands.md#生成静态网页)

本步骤会默认生成`_book`文件夹，该文件夹中有生成的`html`文件

```
gitbook build
```

## 本地预览

+ [本地预览](./common-commands.md#生成静态网页并运行服务器)

本步骤会生成静态网页，并运行服务器

```
gitbook serve
```
![预览结果](./img/use1.png)

> 默认端口号为4000,可以直接访问[http://localhost:4000](http://localhost:4000),进行预览

> 如果要启动另一部电子书服务的话， 就需要同时修改web端口和监控进程端口， 类似这样:


```

 gitbook serve --lsporot 25778 --port 4001

```

