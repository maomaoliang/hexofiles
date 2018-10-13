layout: post

title: "hexo站内搜索"

date: 2018-10-13 22:45:23

categories: skills

tags:
    - hexo
---

### 参考资料
[hexo站内搜索教程](https://www.ezlippi.com/blog/2017/02/hexo-search.html) 
[hexo站内搜索教程](https://15045120.github.io)
[作者亲自教程](http://www.hahack.com/codes/local-search-engine-for-hexo/)

### 安装 hexo-generator-search
```code
    $ npm install hexo-generator-search --save
```

### 安装 hexo-generator-searchdb
```code
	$ npm install hexo-generator-searchdb --save
```
### 启用搜索
编辑 站点配置文件，新增以下内容到任意位置：

```code
	search:
	  path: search.xml
	  field: post
	  format: html
	  limit: 10000
```

就是这么简单！

<!--more-->

