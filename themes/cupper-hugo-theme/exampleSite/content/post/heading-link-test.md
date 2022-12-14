---
title: "Linux 大作业"
date: 2022-11-28T20:04:19-06:00
tags: []
---
{{< expandable label="一、如何使用github提交代码" level="2" >}}

# 1.git的安装
## (1)先在openeuler安装github仓库,然后查看git的版本
{{< cmd >}}
sudo yum -y install git
git version
{{</ cmd >}}

## (2)进行github 公钥的验证这一步网上也有步骤，
{{< cmd >}}

验证是否连接上github
ssh git@github.com

开始配置仓库，新建文档
mkdir L

{{</ cmd >}}


## (3)先设置本地仓库，然后配置github上的远程仓库


{{< cmd >}}

配置本地仓库
git init

shortname是自己起的仓库名，url是GitHub地址
git remote add shortname url

{{</ cmd >}}

## (4)git 步骤提交到远程仓库


{{< cmd >}}

提交到缓冲区
git add .

写提交说明 
git commit -m "xxxx"

提交
gitpush
{{</ cmd >}}


## (5)如何插入图片
### 1
首先找到和config.yaml的目录下的static
![](/images/2.png)
### 2
使用相对路径插入
{{< cmd >}}
![](/images/xx.png)
{{</ cmd >}}


# 最后提交成功
![](/images/1.png)

{{< /expandable >}}





# 参考的一些视频和网页
## 1 [知乎hugo的搭建](https://zhuanlan.zhihu.com/p/494616883)
## 2 [B站的如何创建hugo博客](https://www.bilibili.com/read/cv19113170/)
## 3 [b站视频](https://www.bilibili.com/video/BV1m4411c7ia?p=1&vd_source=e7eeda787d49396f294bb619db9b3d3c)
## 4 [hugo插入图片](https://blog.csdn.net/qq_38340601/article/details/108900666)

