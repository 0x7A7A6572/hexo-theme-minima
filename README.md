# Modify
 基于[Minima-v2.0](https://github.com/adisaktijrs/hexo-theme-minima) 改动，演示页面:[点击跳转](https://zzerx.cn).
 
 添加：
  - sidebar 侧边工具栏
  - content_inner 内容侧栏显示
  - 文章标签显示
  - 备案显示

 修改：
  - 字体样式（不使用字体）
  - 一些页面排版
  - 一些标签改为h5推荐标签

_config.yml 加入这些配置：
```yml
#左边侧栏
sidebar: 
  enable: true
  theme_switch: true
  to_top: true
  emil: true
  conversation_link: # 会话连接 https://....
  community: 
    github:          #  https://....
    bilibili:        #  https://....
    pixiv:           #  https://....
    
#content-inner
content_inner:
   enable: true
   avatar: /images/favicon.png
   name: zzerX
   motto: "✨Everything that drowns me makes me wanna fly."

#github热力图
github_heatmap:
  enable: false
  user: "0x7A7A6572"
  hexcolor: 03adfc

#tag显示配置
post_tag:
   enable: true
   style: "defult" # defult or simble(only display color)
   bind_color:
     tagname1: 0fdc00
     lua: 0fdc00
     java: dc0f00
     js: 0FA0CE
     linux: dc550f
     h5: 00bedc

```
<div style='display: none'>
### 现在的页面

![pc](./source/images/minima_x_pc.png);

![mobile](./source/images/minima_x_mobile.png);
</div>


    


# Minima
An undoubtedly simple and lightweight dark/light mode theme for Hexo.

![Minima preview, device image by Freepik](https://adisaktijrs.github.io/2020/10/11/Hexo-Minima-Theme-v1-0-Officially-Released/minima.jpg)

- See the demo [here](https://adisaktijrs.github.io/minima)
- See the quick start instruction and documentation [here](https://adisaktijrs.github.io/2020/10/11/Hexo-Minima-Theme-v1-0-Officially-Released/)

## About Minima
Minima is an undoubtedly simple and lightweight dark/light mode theme for Hexo. I created this from scratch using [Skeleton CSS](http://getskeleton.com/) boilerplate. It only uses CSS and Vanilla JS, without using unnecessary third-party 'render-blocking' libraries.

### Simplicity
Simplicity is a must! When I decided to move to Hexo for my personal blogging platform, the main reason was to find a simple and clean design, no fancy looks, unnecessary images and colors either. I'd like to have a blog that focuses on the content of my posts rather than turning readers attention to a 'cluttered' user interface. I found lots of beautiful themes on the Hexo themes page, but finally I decided to make my own.

### Lightweight
This 'lightweight' means the theme uses as few design stuff as possible. Fewer JavaScript and CSS files. Minima only uses Skeleton for the CSS-boilerplate and [nanobar.js](https://nanobar.jacoborus.codes/) for the top loading bar. The following is the 'gross' performance of my blog with the Minima theme:

![](https://adisaktijrs.github.io/2020/10/11/Hexo-Minima-Theme-v1-0-Officially-Released/Screenshot.png)

### Customization
Minima uses vanilla JavaScript, vanilla CSS, and [EJS](https://ejs.co/). So it will be very easy for everyone to edit and customize the theme.

## Features
- Pass the core of [Hexo Theme Unit Test](https://github.com/hexojs/hexo-theme-unit-test)
- Fully responsive design
- Support post, page, tags, archives, and pagination
- SEO: post meta description and images (appears in Facebook/Twitter shared-link)
- [Customizable] icon Dark/light mode instant switch 🌑/☀️
- [Customizable] theme color
- Code highlighting with [Prism.js](https://prismjs.com/)
- [Disqus](https://disqus.com/) for post comments
- Show comments section button for faster posts loading

## Documentation
See the quick start instruction and [documentation here](https://adisaktijrs.github.io/2020/10/11/Hexo-Minima-Theme-v1-0-Officially-Released/#Documentation)

## Development
Everyone is welcome to contribute! Go ahead, fork and make pull request 😁

## Credit
Big thanks to [@pduchnovsky](https://github.com/pduchnovsky) and [yukimuon](https://github.com/yukimuon) to help me making this theme even better!

## Licence
Minima is released under [MIT License](https://github.com/adisaktijrs/hexo-theme-minima/blob/master/LICENSE). Copyright © 2020 Adi Sakti Jrs
