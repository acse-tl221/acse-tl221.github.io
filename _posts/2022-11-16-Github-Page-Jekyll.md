---
layout: post
title:  "Github Page jekyll踩坑记录"
date:   2022-11-16 02:40:00 +0800
categories: jekyll
---
### Github Page教程
#### 1.官方教程
https://docs.github.com/en/pages
#### 2.添加分类目录
https://acse-tl221.github.io

### 踩坑Issue
#### Issue 1: bundle exec jekyll serve时报错bundler: failed to load command: jekyll
解决方式：[https://stackoverflow.com/questions/69890412/bundler-failed-to-load-command-jekyll][issue1]
<br/>先执行命令
`bundle add webrick`

[issue1]: https://stackoverflow.com/questions/69890412/bundler-failed-to-load-command-jekyll