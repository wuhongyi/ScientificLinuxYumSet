<!-- README.md --- 
;; 
;; Description: 
;; Author: Hongyi Wu(吴鸿毅)
;; Email: wuhongyi@qq.com 
;; Created: 六 7月 16 21:16:08 2016 (+0800)
;; Last-Updated: 二 9月 27 13:48:49 2016 (+0800)
;;           By: Hongyi Wu(吴鸿毅)
;;     Update #: 3
;; URL: http://wuhongyi.github.io -->

# README

Scientific Linux **yum** 配置文件  
当前目录下有以下文件/文件夹：

- README.md
- sl6
- sl7

系统版本为 6.x则使用 **sl6**，系统版本为7.x则使用 **sl7**。

将文件夹 yum.repos.d 内所有文件复制到 /etc/yum.repos.d 文件夹内

```shell
cd sl6/7
cd yum.repos.d
cp -f  *   /etc/yum.repos.d
```

然后即可按照教程配置软件。


<!-- README.md ends here -->
