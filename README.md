# duiba-about
给公司首页的资讯制作带后台的文章发布功能，使用hexo博客系统，hexo-admin插件，在apollo主题上修改而来。  
Demo: [about.lolijam.com](http://about.lolijam.com)

### 由来
应产品的要求，需要改造公司的官网的资讯模块，原来的资讯是只引用了新闻的链接，以及部分简介，点击之后是直接跳转到相应的目的页面去的，官网上并没有保留文章。
另外为了方便，当时的设计只用了一张静态页面，由前端手动更新文章，在发布时更新新闻。

### 分析
这样做会有两个缺点：
1. 只有外链没有文章，会降低SEO的优先级，难以提升官网的访问量。
2. 每次都由前端手动修改发布，效率低、易出错。

针对这两个缺点，我使用Hexo的博客引擎搭配apollo主题，重新制作了官网的资讯栏目。

### 优化改进
优化的点有：
1. 文章页面由hexo生成，托管在兑吧的静态服务器上，在官网可以直接查看文章内容。
2. 使用markdown，方便编辑文章。
3. 通过标签配置文章来源，保留外链。
4. 配置了后台页面，可以在线添加、编辑文章，提供热更新功能，实时发布生效。

![](http://ociavg9dh.bkt.clouddn.com/54ED2BD8-3A6B-44C2-9FA2-1FC80D581A9A.png)
![](http://ociavg9dh.bkt.clouddn.com/F9A09EB5-65CD-454A-B1B3-640E36578271.png)
![](http://ociavg9dh.bkt.clouddn.com/F3C0C98F-4C70-49E6-8AC5-93DB2B5344E5.png)
