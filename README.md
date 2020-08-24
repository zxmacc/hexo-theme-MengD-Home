<h1 align="center"><a href="https://github.com/lete114/hexo-theme-MengD" target="_blank">MengD.(点)</a></h1>

<img src="https://cdn.jsdelivr.net/gh/lete114/CDN2/img/zaxiang/HomePage.png" alt="Chic theme">


## 介绍
一个简单的Hexo个人主页设计，能够清晰明了的展现你

Demo：[Lete乐特主页](https://lete114.top)


## 安装

```powershell
git clone https://github.com/lete114/hexo-theme-MengD.git MengD
```

## 配置

### 关于Hexo

在hexo的配置文件里修改主题`theme: MengD`

现在你需要注意hexo根目录下的`source/_posts/hello-world.md`你不能删除它

我们贴心的为你写好了防止爬虫抓取`hello-world.md`生成的页面，如果你想自己修改的话，你可以到`themes\MengD\source`下的`robots.txt`自定义

``` txt
# 允许所有用户代理的浏览器爬虫进行访问（爬取数据）
User-agent: *

# 不允许访问的内容
Disallow: /archives/
Disallow: //
Disallow: /2020/
Disallow: /2021/
Disallow: /css/
```

### 主题

``` yml
# language 语言
language: zh-CN

# name 名称
name: Lete乐特

# 自定义页脚字体颜色
footer_color: '#000 '
footer_a_color: '#000'
# 鼠标移动到超链接上显示的颜色
a_hover: '#e58a8a'
# 自定义名称颜色
name_color: '#80bdab'
#自定义描述字体颜色
desc_color: '#000'

# 自定义背景
# bg_img: url(https://cdn.jsdelivr.net/gh/lete114/CDN2/img/wei_er_li_te/3.jpg)
# bg_img: '#fff'
# bg_img: 'white'
bg_img: '#fff'
# 开站年份
Copyright: 2020

#关键字
keywords: Lete乐特,Java,JavaWeb,Java常用框架,Spring,SpringBoot,SpringMVC,MyBatis,数据库,MySQL,C#,.NET,开发工具,Git,GitHub,Gitee,(My)Eclipse,IDEA, Hexo,Linux,Maven,前端基础知识,HTML,CSS,JavaScript,jQuery,Ajax,Bootstrap,工具&#x2F;资源,教程,分享,推荐,娱乐,摄影,C#,CMD,Developer,Programmer,Coder


# favicon 图标
favicon: /img/favicon.ico

# avatar 头像
avatar: /img/avatar.png

# site description 网站描述
description: 我相信我可以，但我一直在路上，所以我有无限的可能！！

# 个人描述
desc: 我相信我可以，但我一直在路上，所以我有无限的可能！！<br>人生只有一次，大胆的生活，怎么舒服怎么来！！

# 自定义css js
# - https://xxx.com/css/css.css
# - https://xxx.com/js/js.js
# - css/css.css
# - js/js.js
css:
  - https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free/css/all.min.css
#js:
#  - js/js.js

# 自定义图标
iconfont: https://cdn.jsdelivr.net/gh/sviptzk/StaticFile_HEXO@master/butterfly/css/iconfont.min.css
# 图标大小
font_size: 1.6em
# Icon 图标
links:
  iconfont icon-youxiang: mailto:lete@lete114.top
  iconfont icon-github3: https://github.com/lete114
  iconfont icon-csdn: https://me.csdn.net/Lott0419
  iconfont icon-zhihu: https://www.zhihu.com/people/lete114

ICP:
  enable: false
  icon: https://cdn.jsdelivr.net/gh/lete114/lete114.github.io/img/icp.png
  url: 
  text: 
```

