![DEMO](demo.png)

原主题：https://github.com/zker-themes/hexo-theme-lightime

## 安装 Install

```bash
git clone -b master https://github.com/F0r3at/Lights themes/Lights
```

## 特色 Features

- 单栏，简洁。 / One column , Simple.
- 集成Gitment和Disqus评论系统。使用InstantClick实现无刷新浏览，更快更流畅。 / Disqus&Gitment comment-system. And used InstantClick speeds up.
- 支持Service Worker，但和InstantClick冲突，按需选择。 / Supports Service Worker, but conflicts with InstantClick. PLZ select on demand.
- 代码高亮。 / Highlight code.
- 文章页内分享功能。 / Sharing component in article.
- 支持归档页，分类、标签页。 / Archive page, Categories page, Tags page.
- i18n国际化。 / i18n.
- 去掉了MoreRead功能
- 修改了部分字体

**之前学了一下，发现自己并不是前端的料，各位大佬可以继续开发~**

## 配置 Config
```yaml
menu: #TITLE: link
  About: about/
  Archives: archives/

profile_link: about/ #profile avatar-img link
avatar: /images/avatar.png #Please also prepare a HDer picture and add suffix@2x put in the same directory.

gitment:
 username: 
 repo: 
 id: 
 secret: 

disqus_shortname: 

google_analytics: UA-XXXXXXXX-Y

twitter: 

hitokoto: false #Output a Chinese sentence to description
instantclick: true #open INSTANTCLICK
service_worker: false #open SERVICE WORKER

js: #CDN
  instantclick: //cdnjs.loli.net/ajax/libs/instantclick/3.0.1/instantclick.min.js
  hitokoto: //v1.hitokoto.cn/?encode=js&select=%23hitokoto
  service_worker: /sw.js
  gitment: /js/gitment.browser.js

css: #CDN
  gitment: 
```

**[DEMO](http://getshe11.com/)**
