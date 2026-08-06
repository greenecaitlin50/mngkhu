摩鑫官网【Q-——333307——】摩鑫官网【 辋芷《888yx●vip》 】
摩鑫官网【Q-——333307——】摩鑫官网【 辋芷《888yx●vip》 】

 从0到1搭建个人技术博客：GitHub Pages + Hexo 保姆级教程

> 还在羡慕别人漂亮的个人网站？别急，今天手把手教你用GitHub Pages和Hexo，免费搭建一个属于自己的技术博客。无需服务器，无需域名，甚至不需要懂后端，跟着做，半小时就能上线。

 为什么选择 GitHub Pages + Hexo？

很多开发者问我：写作平台那么多，为什么非要自己折腾？我的答案很简单——完全掌控。

- 免服务器费用：GitHub Pages 免费托管静态网页
- 极致加载速度：静态页面无需数据库，CDN加速后秒开
- Markdown友好：本地写作，Git管理，专注内容本身
- 主题生态丰富：几百款Hexo主题任选，总有适合你的审美

 搭建步骤：三步走，零基础也能搞定

 第一步：准备环境

打开终端，确认已安装 Node.js 和 Git。没有？去官网下载安装即可。然后用你的 GitHub 账号新建一个仓库，命名为 `你的用户名.github.io`，注意必须完全一致。

 第二步：本地初始化 Hexo

```bash
npm install hexo-cli -g    全局安装
hexo init my-blog         初始化项目
cd my-blog
npm install               安装依赖
hexo s                    本地预览
```

打开浏览器访问 `http://localhost:4000`，看到默认页面就成功了。这时候你可以修改 `_config.yml` 文件，替换成你的站点信息。

 第三步：部署到 GitHub Pages

安装部署插件，然后一条命令搞定：

```bash
npm install hexo-deployer-git --save
hexo d
```

回到 GitHub 仓库的 Settings → Pages，选择 main 分支，等一分钟，你的博客就上线了！

 进阶优化：让博客脱颖而出

基础博客能跑起来只是开始，想让访问量上来，这几点值得花时间：

1. SEO优化：安装 `hexo-generator-seo-friendly-sitemap` 插件，自动生成sitemap.xml，提交给百度站长平台。记住，百度对GitHub Pages的收录速度不如Google，建议绑定自定义域名（比如 `blog.你的名字.com`），能让收录效率提升50%以上。

2. 评论系统：推荐集成 Gitalk 或 Valine，基于GitHub Issue的评论系统，无需额外服务器，访客用GitHub账号就能留言互动。

3. 文章内链接策略：写技术文章时，多链接到自己站内其他相关文章，能有效降低跳出率，百度判断为“有价值页面”后会提高权重。

 写作建议：内容为王，兼顾问答

百度搜索的读者往往带着明确问题来，所以标题切忌文艺范。比如“Hexo安装踩坑记录”就比“我的第一周”强得多。每篇文章开头用2-3句话直接点明要解决的问题，正文按“现象→原因→解决步骤”的逻辑写，结尾总结关键词——这既是SEO技巧，更是对读者负责。

 遇到问题？这些资源能帮你

搭建过程中卡住了？别慌，99%的问题都能在Hexo官方文档、GitHub Issues社区找到答案。搜索时加个“Hexo”前缀，能过滤掉噪音信息。

---

动手是最好的学习。现在就打开终端，按照上面的步骤一步步执行。如果遇到报错，把错误信息复制到搜索引擎，通常第一个结果就是解决方案。如果这篇文章帮到了你，记得在评论区分享你的博客地址，我会去参观交流。

> 好内容值得被更多人看到。觉得有用的话，点赞让更多朋友看到，或者收藏起来需要时随时查。有问题，评论区见，我会尽力解答。

相关推荐：

https://github.com/vazqueznicholas9/tzqtka/blob/main/ch%E1%BB%8Di%20g%C3%A0%20%F0%9F%90%94%20%EF%BC%9A%E6%91%A9%E6%9D%B0%E5%AE%98%E7%BD%91app_%E7%96%9F%E6%80%95%E7%96%9F%E9%B8%A5%E8%80%81aanhn.md

<img src="https://i.postimg.cc/cCYhQM3T/moxin-00002.png" />

相关推荐：

https://github.com/vazqueznicholas9/tzqtka/commit/c6be5654cccaa7e755c2c62ce5e02e9fb0a68d2d

<img src="https://i.postimg.cc/h472WgYT/moxin-00009.png" />
相关推荐：

https://github.com/rossmarissa09/kqyzhh/blob/main/C%E1%BB%91c%20Games%20%F0%9F%A5%8A%EF%BC%9A%E6%91%A9%E6%9D%B0%E5%BC%80%E6%88%B7%E5%AE%98%E7%BD%91_%E6%9C%88%E8%B0%93%E5%88%91%E5%B5%8C%E6%B8%ADjpohh.md

<img src="https://i.postimg.cc/BQ9MJk90/moxin-00015.png" />
相关推荐：

https://github.com/rossmarissa09/kqyzhh/commit/bd66872231ffe25596e8ba1d91f0926516158d2f

<img src="https://i.postimg.cc/wMJ2hcJg/moxin-00006.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
