---
layout: post
title: "setup blog based on github"
date: 2014-09-05 00:37:17 +0800
comments: true

# 搭建基于github的博客

---

[搭建基于github的博客](http://blog.devtang.com/blog/2012/02/10/setup-blog-based-on-github)

[更多主题](https://github.com/imathis/octopress/wiki/3rd-Party-Octopress-Themes)

### 简易操作手册

* rake new_post[your-blog-name]，生成source/_posts/YYYY-MM-DD-your-blog-name.markdown文件。
	
* 编辑生成的markdown文件。
	
* rake generate，将markdown转换为html，存储路径为public/blog/YYYY/MM/DD/your-blog-name/index.html。
	
* rake deploy，发布博客。

	* 将html推送至远程master分支。
	* 先generate，再deploy。
	* deploy前的所有操作都是在source分支进行。

* 同步source分支

	* git add -A & git commit -m 'commit to souce branch' & git push origin source。





