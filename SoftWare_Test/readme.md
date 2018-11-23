# GitHub简易使用

## 将本地仓库与git关联并提交本地文件

> 首先初始化一个空的本地仓库,命令行为：git init
> 然后将新文件（a01.c）添加到git中，命令行为：git add    a01.c
> 
>将文件提交到git仓库,引号中为提交说明：git commit -m "submit a01.c"
> 
>关联本地仓库与远程仓库：git remote add orgin https://github.com/15651873068/SoftWare_Test.git
>
>将代码push到远程仓库：git push -u origin master

##合并文件到远程仓库

>先将远程仓库中的内容克隆到本地：git clone https://github.com/15651873068/SoftWare_Test.git
>
>将远程改动与本地合并：git fetch orgin master
>
>查看远程和本地两个master分支的差异：git log -p master..orgin/master
>
>将远程master分支合并到本地master分支：git merge orgin/master
>
>重新提交：git push -u orgin master

>
> github访问网址：https://github.com/15651873068/SoftWare_Test.git
>
# redmine简易使用

## 安装配置redmine

> 直接下载安装包安装即可，安装过程中将账号设置为nuaa，密码设为teaching2018
> 
>安装成功后，工具访问网址为：http://47.106.238.35：80，其中47.106.238.35为服务器地址  
> 
>关于工具的使用，目前还不是很熟悉。

