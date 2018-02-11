# hexo-theme-polarbear

## INFO

Self-use Hexo theme with MathJax support.

Thanks for frostfan's work! This theme was based on https://github.com/frostfan/hexo-theme-polarbear

> A light theme bases on Even, designed by Giuem.

[在线预览 Demo](https://blog.huzicheng.com)

## 安装使用（Installation）

```
$ npm install hexo-renderer-scss --save
$ npm install Hexo-renderer-pandoc --save

$ git clone git@github.com:Tigeraus/hexo-theme-polarbear.git themes/polarbear
```

修改（Change） polarbear/config.yml `theme: polarbear`

```
# 在归档页面显示所有文章 （Show all articles on archive page.）
# 需要安装(Need to install) hexo-generator-archive 插件支持
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## LaTeX 支持

本主题采用Hexo-renderer-pandoc作为渲染器, 可以直接使用 `$$` 和 `$` 写行间和行内公式. 但是记住, 不要在本主题里使用Hexo.io提出的一些特殊的写法. 同时, 因为post开头的等号序列会影响pandoc-markdown的表格展示. 建议你使用标准表格而不是pandoc定制过的表格.

## 版权说明

本主题中版权说明改成了  Creative Commons Attribution-ShareAlike 4.0 International License. 如果你认为需要修改这一点的话, 请到 languages 对应信息里修改(记得修改所有语言对应版).

## 感谢 (Thanks)

Hexo-renderer-pandoc author: [wzpan](https://github.com/wzpan)

Theme Polarbear author: [frostfan](https://github.com/frostfan)

Theme Even author: [ahonn](http://www.ahonn.me/)

Theme style designed by: [Giuem](https://www.giuem.com)
