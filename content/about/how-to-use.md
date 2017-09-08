+++
title = "怎样写博客"
date = "2017-05-19T21:49:20+02:00"
menu = "main"
disable_comments = true
+++

##markdown语法
<http://www.cnblogs.com/liugang-vip/p/6337580.html>

<!--more-->
##每个博客文章头部都有一下信息：
```
+++
title = "这表博客的名字"
date = "博客时间，格式:2015-10-02T21:49:20+02:00"
tags = ["golang", "programming", "theme", "hugo"]
categories = ["programming"]
menu = ""
banner = "banners/placeholder.png"
+++
```

##标签
```
+++
tags: 里边可以填多个标签
tags = ["golang", "programming", "theme", "hugo"]
+++
```

##分类
```
+++
categories = ["programming"]
+++
```

##加到menu
```
+++
menu = "main"
+++
```

##给博客加标题图片

```
+++
banner = "http://www.eeboard.com/bbs/data/attachment/forum/201510/23/091243rs8e3p6zas369o0t.jpg"
+++
```

##调试
```
hugo server --theme=hugo-icarus-theme --buildDrafts
```

##生成web
```
hugo --theme=hugo-icarus-theme --baseUrl="http://lilangrui.github.io/"
```