# Jinbin Luo · Academic homepage

主页：<https://crazydave999.github.io/>

这是一个静态英文主页。直接在 GitHub 编辑文件，提交到 main 后 GitHub Pages 会自动发布。也可以在本机双击 index.html 预览。

## 更新个人信息

- **简介和联系方式**：打开 index.html，点击铅笔，搜索现有英文简介或邮箱并替换。邮箱的可见文字和 mailto: 链接都要改。
- **照片**：替换 assets/portrait.jpg 即可，建议使用方形 JPEG。
- **论文**：在 index.html 搜索 Publications &amp; Manuscripts，复制 article 区块并更新标题、作者、会议和链接。
- **简历**：用新版 PDF 替换 assets/CV.pdf，保留文件名即可。首页和原网页版简历地址都会打开此文件。
- **样式**：字体、配色、宽度和小屏布局集中在 style.css。

提交后到仓库 Actions 查看 Pages 部署结果，再打开主页并检查相关链接。

## 图像与搜索配置

三篇 overview 分别提取自对应论文的 Figure 4。校徽图像来自 https://xingyangli.com/images/sjtu.png 和 https://xingyangli.com/images/mit.png。照片位于 assets/portrait.jpg，论文缩略图位于 assets/*-overview.png。

网页标题、描述、canonical 和 ProfilePage 结构化数据在 index.html 的 head 中。robots.txt 允许抓取并指向 sitemap.xml。可在 Google Search Console 添加 URL 前缀属性 https://crazydave999.github.io/，验证后通过 URL Inspection 请求收录，并提交 sitemap.xml。
