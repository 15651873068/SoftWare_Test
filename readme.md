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

##redmine工具使用

>redmine是一个缺陷跟踪工具，用于记录项目开发过程中的进度以及缺陷情况。
>
>在“我的工作台”栏目中可以查看“指派给我的问题”（项目负责人指派给自己的工作任务）和
>“已报告的问题”（自己在开发过程中发现并在redmine上报的问题）
>
>在“项目”菜单中可以看到自己已添加的项目而且可以新建项目。
>点击一个项目进入可以看到项目概述以及有关的活动和问题，如果新发现了问题可以新建添加问题。
>在项目的甘特图和日历中可以详细记录项目的进度。

