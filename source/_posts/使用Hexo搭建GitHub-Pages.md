---
title: 使用Hexo搭建GitHub Pages
date: 2018-05-13 19:59:35
tags:
- Hexo
- GitHub Pages
comments: true
categories:
- 环境搭建
- GitHub Pages
 
---
## 预备环境搭建

- [预备环境搭建](https://segmentfault.com/a/1190000008074407 "hexo 环境搭建")

## 主题选择

- [主题更换为NexT](https://blog.csdn.net/Hoshea_chx/article/details/78826689)
- [NexT配置文档](http://theme-next.iissnan.com/)
- 找不到git username问题：通过将git版本升级到最新（windows 2.17.0）解决
- 部署到GitHub Pages仓库master分支（默认分支）的内容为hexo/public
- hexo目录下的内容可手动部署到Pages仓库的hexo分支进行保存

## 写博客

- 命令:hexo new "blog name"
- 文件位置： hexo/source/_posts
- 生成：hexo g
- 本地启动：hexo s
- 部署到GitHub：hexo d
- [参考文档](https://hexo.io/zh-cn/docs/writing.html)

## 删博客
- 删除 source/_posts下文件
- hexo clean
- hexo g
- hexo s
- hexo d


## 常用命令
1. hexo clean ：清理
2. hexo g ：生成
3. hexo d ：部署
4. hexo s ：启动本地server （localhost：4000）
5. `hexo new [layout] <titile> `
```
hexo有三种默认布局：post、page、draft 默认为post
```



