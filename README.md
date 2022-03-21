# Migration Generator

Hyperf data reverse migration tool, currently only supports MySQL database, hyperf2 Version 2

Hyperf数据反向迁移工具，目前仅支持Mysql数据库,Hyperf2.2版本

##  How to install
##  如何安装


```
composer require dreamyi12/reverse-migration 
```

## How to use
## 如何使用

```shell
//迁移全部数据库表
php bin/hyperf.php gen:reverse-migration 

//迁移单张表
php bin/hyperf.php gen:reverse-migration -table=XXXXXX

//迁移文件生成路径可以由-path 指定
```

欢迎有问题随时提问
