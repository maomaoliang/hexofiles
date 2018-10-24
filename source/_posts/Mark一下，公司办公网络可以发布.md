---
title: Mark一下，终于解决了办公网络发布文章的问题

date: 2018-10-23 21:11

comments: true

categories: 技能

tags: 
	- Hexo
---

yo yo yo ,  I have solved the fucking oa-net...marked

<!--more-->

修改的depoly的配置即可. 修改站点配置文件`.config.yml`

原配置：

```code
deploy:
  type: git
  repository: git@github.com:maomaoliang/maomaoliang.github.io.git
  branch: master
```

修改后配置：

```code
deploy:
  type: git
  repository:  https://github.com/maomaoliang/maomaoliang.github.io.git
  branch: master
```

总结一句话：

办公网络不支持：git 协议、ssh 方式 clone repo，需要用 https 协议，并且设置公司 http 代理。

所以,git测试肯定是不会通的。

```code
$ ssh git@github.com
```

**PS：根本不需要设置git代理~**