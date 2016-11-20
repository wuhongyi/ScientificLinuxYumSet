<!-- README.md --- 
;; 
;; Description: 
;; Author: Hongyi Wu(吴鸿毅)
;; Email: wuhongyi@qq.com 
;; Created: 六 7月 16 21:16:08 2016 (+0800)
;; Last-Updated: 日 11月 20 21:10:12 2016 (+0800)
;;           By: Hongyi Wu(吴鸿毅)
;;     Update #: 8
;; URL: http://wuhongyi.cn -->

# README

Scientific Linux **yum** 配置文件  
当前目录下有以下文件/文件夹：

- README.md
- sl6
- sl7

系统版本为 6.x则使用 **sl6**，系统版本为7.x则使用 **sl7**。

将文件夹 yum.repos.d 内所有文件复制到 /etc/yum.repos.d 文件夹内

```shell
cd sl[6/7]
cd yum.repos.d
cp   *   /etc/yum.repos.d
# 然后按 y 同意覆盖(提示的每个都需要)
```

然后即可按照教程配置软件。

----

update:

- 20161111 **sl7** add okay.repo  install shc
- 20161120 **sl7** add remi*.repo


<!-- README.md ends here -->
