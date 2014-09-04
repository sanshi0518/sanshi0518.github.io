---
layout: post
title: "setup blog based on github"
date: 2014-09-05 00:37:17 +0800
comments: true

# 搭建基于github的博客

---

[搭建基于github的博客](http://blog.devtang.com/blog/2012/02/10/setup-blog-based-on-github)

[更多主题](https://github.com/imathis/octopress/wiki/3rd-Party-Octopress-Themes)

### 新建博客

- rake new_post[your-blog-name]，生成source/_posts/YYYY-MM-DD-your-blog-name.markdown文件。
- 编辑生成的markdown文件。
- rake generate，将markdown转换为html，存储路径为public/blog/YYYY/MM/DD/your-blog-name/index.html。
- rake preview，访问本地4000端口进行预览，实时刷新最新内容。
- rake deploy，发布博客。




