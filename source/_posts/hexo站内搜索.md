layout: post

title: "hexo站内搜索"

date: 2018-10-13 22:45:23

categories: 技能

tags:
    - hexo
---

### 参考资料
[hexo站内搜索教程](https://www.ezlippi.com/blog/2017/02/hexo-search.html) 
[hexo站内搜索教程](https://15045120.github.io)
[作者亲自教程](http://www.hahack.com/codes/local-search-engine-for-hexo/)
[next主题官网](http://theme-next.iissnan.com/)
[next最新下载](https://github.com/theme-next/hexo-theme-next/releases)

### 安装 hexo-generator-search
```code
    $ npm install hexo-generator-search --save
```

### 安装 hexo-generator-searchdb
```code
	$ npm install hexo-generator-searchdb --save
```
### 站点配置文件配置启用搜索
编辑 站点配置文件，新增以下内容到任意位置：

```code
	search:
	  path: search.xml
	  field: post
	  format: html
	  limit: 10000
```

### 主题配置文件配置添加搜索按钮
```code
local_search:
  enable: true
  # if auto, trigger search by changing input
  # if manual, trigger search by pressing enter key or search button
  trigger: auto
  # show top n results per article, show all results by setting to -1
  top_n_per_article: 1
  # unescape html strings to the readable one
  unescape: false
 ```

就是这么简单！

<!--more-->

