title: "个人网站迁移至 Github Pages"
date: 2015-03-27 14:46:28
tags: 
- Hexo
- 个人网站
- 博客

---

个人网站迁移这件事想了很久，搁了如此久之后，在看到 [Hexo](http://hexo.io) 之时终于付诸实施。[Hexo](http://hexo.io) 实在是太棒了！

## 迁移的原因
之前的个人网站是使用 Wordpress 搭建，碰到很多问题：

1. [wordpress.com](http://wordpress.com) 在国内是无法访问的，而很多插件的静态资源是在 [wordpress.com](http://wordpress.com) 下的，这直接导致整个网站的速度和可用性非常差
2. 虽然 Wordpress 通过插件也可以支持 Markdown，但总觉得不是那么性感
3. 不想部署一套系统，即便手头有充足的服务器资源

## 可能的选项

1. [Typecho](http://typecho.org/) 是个不错的选择，她足够简介，又原生支持 Markdown，可仍需下载、部署、维护
2. [Github Page](https://pages.github.com/) + [Hexo](http://hexo.io) = Perfect! Github Page 免费托管速度也不错，Hexo 性感强力，合体之后足够美，足够 Geek！

## Hexo 吸引我的地方

1. 简单强大的命令
    - `hexo init`: 创建文章
    - `hexo server`: 本地托管预览
    - `hexo deploy`: 一键部署（至 Github / Heroku / etc.）
    - `hexo generate`: 输出静态 HTML，随便拿去撸
2. 众多插件
3. 丰富漂亮的模版
4. 贴心的小功能
    - 开启 `post_asset_folder` 为每篇文章创建一个静态资源文件夹，文章中可以极方便的引入
    - `scripts` 文件夹下的脚本会被自动引入和执行，这可以非常容易的扩展 Hexo
    - 动态引入自定义的 Javascript / CSS 文件
    - 海量内置标签、函数、变量

## 原来的博文去哪儿了？

以前的博文在现在看来实在是 too young too simple, sometimes naive，还是不要在拿出来自黑了，统统 clip 到 Evernote 备份罢了。
