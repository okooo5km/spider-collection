# blogo

[blogo](/blogo/blogo)是一个针对hexo静态博客的工具，可以统计博主每月发博文的数量，也可以爬取博客中所有图片。

## 依赖库

- requests
- urllib
- matplotlib
- pyquery
- hashlib

上面所需库均可以pip安装。

## 使用方法

./blogo 子命令 hexo博客归档地址 CSS选择器

- 子命令：count 和 pic，count用于得到指定博客中每个月份博文数，pic用于爬取博文中的图片
- hexo博客归档地址：比如http://www.litreily.top/archives/
- CSS选择器：用于选择文章列表中文章标题对应的<a>标签

## 举例：

- ./blogo count http://www.litreily.top/archives/ '.post-archive .listing li a'
- ./blogo pic http://www.smslit.top/archives/ '#posts article .post-title-link'

## 思路

[爬虫实践之hexo博客分析](https://www.smslit.top/2018/06/25/spider-practice-hexo-blogo/)
