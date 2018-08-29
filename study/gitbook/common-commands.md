# 常用命令


## [初始化目录文件](#初始化目录文件)

> 使用该命令时候，如果没有`SUMMARY.md`文件，会自动自动创建，生成时候会按照文件`book.json`中 `structure.readme`
创建一级目录结构，默认`structure.readme`对应的文件为`README.md`,如果`README.md`文件不存在也会创建

> 如果有`SUMMARY.md`文件，会按照`SUMMARY.md`文件中的目录结构自动生成没有创建的文件


```
    gitbook init
```

## 列出gitbook所有的命令

```
    gitbook help

```

## 输出gitbook-cli的帮助信息

```
    gitbook --help
```


## 生成静态网页

```
    gitbook build
```

## 成时指定gitbook的版本, 本地没有会先下载


```
    gitbook build --gitbook=2.0.1
```

## 指定log的级别

```
    gitbook build --log=debug
```

## 更新到gitbook的最新版本

```
    gitbook builid --debug
```

## 生成静态网页并运行服务器


```
    gitbook serve
```

## 列出本地所有的gitbook版本


```
    gitbook ls
```

## 列出远程可用的gitbook版本


```
    gitbook ls-remote
```
## 安装对应的gitbook版本


```
    gitbook fetch 标签/版本号
```

## 更新到gitbook的最新版本

```
    gitbook update
```

## 卸载对应的gitbook版本

```
    gitbook uninstall 2.0.1
```

## 插件下载

```
    gitbook install

```


