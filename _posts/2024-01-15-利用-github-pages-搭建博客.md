---
layout: post
date: 2024-01-15T15:52:31+0800
title: 利用github pages搭建博客
tag: tag2
---

1. 创建与github用户名同名的仓库: your-github-user-name.github.io

    ![create github repo](/assets/images/create-github-repo.png)

2. 准备工作

    - 安装ruby

        > sudo pacman -S ruby

    - 安装rubygems

        > sudo pacman -S rubygems

    - 安装gcc和make  

        > sudo pacman -S gcc make
    
3. 配置jekyll
    > gem install jekyll bundler  
    > jekyll new blog  
    > cd blog  
    > bundler add json: 不添加可能启动失败  
    > bundler exec jekyll serve --livereload: 启动测试，livereload可以热加载，方便调试  

4. 上传blog到your-github-user-name.github.io仓库

5. 访问your-github-user-name.github.io
