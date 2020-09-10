---
layout: page
title: 搭建个人技术博客
subtitle: 我们在这里使用Git Hub Pages + Jekyll 快速部署个人博客
---

<span style="float: right; "><a href="{{ '/assets/resume.pdf' | prepend: site.baseurl }}"><strong>> 下载这个PDF</strong></a> </span>
<br>

> - GitHub Pages 
>   - 定义: 给所有用户提供一个个人主页
>   - 如何访问个人域名: 用户名.github.io
>   - 如何编写主页:  建立一个用域名为项目名的远程版本仓库,只需要向该远程版本仓库中的master分支提交代码即可(该代码中必须有个文件叫index.html)
> - Jekyll
>   - 定义: 可以将markdown语法自动编译成html语法的一个工具
>   - 安装: 不需要自己安装,在github网站中预安装了
>   - 使用: 不用人为使用,当你请求个人域名的时候github服务器会读取仓库(以个人域名命名的那个远程版本仓库)中的master分支中的代码,如果该代码为markdown代码会自动调用Jekyll将其编译为html代码,并返回客户端

- 建立一个以个人域名为项目名的远程版本仓库
- 访问一个网址(主题网址): http://jekyllthemes.org/ 选择一个主题将其代码复制到我们仓库的master分支
- 以上两步可以合并为一步,在主题仓库中点击fork,点击settings设置仓库名,即可
- 将远程版本库的代码克隆到本地
  - 点击头像,点code,复制链接
  - 在文件打开终端执行克隆: git clone -b master https://github.com/brobboVIi/brobboVIi.github.io.git myBlog
  - 从远程版本库中克隆下来的代码会自动创建本地版本仓库
  - 当从本地版本库推送到远程版本库前,本地版本库的状态必须为clean
- 修改配置文件以及页面内容
- 书写博客