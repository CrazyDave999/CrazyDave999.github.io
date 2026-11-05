# Jinbin Luo · Academic homepage

主页：<https://crazydave999.github.io/>

这是一个静态英文主页。直接在 GitHub 编辑文件，提交到 main 后 GitHub Pages 会自动发布。也可以在本机双击 index.html 预览。

## 更新个人信息

- **简介和联系方式**：打开 index.html，点击铅笔，搜索现有英文简介或邮箱并替换。邮箱的可见文字和 mailto: 链接都要改。
- **照片**：把准备公开的 JPEG 命名为 portrait.jpg，放入 assets 文件夹。编辑 index.html，搜索 Optional portrait，把下一行 img 标签两侧的 HTML 注释符号删掉。照片显示在简介右侧，建议使用脸部居中的竖图。之后只需替换同名照片。
- **论文**：在 index.html 搜索 Publications，复制已有的 article 区块，修改标题、作者、会议、摘要及链接。用 strong 标出自己的名字。
- **项目与经历**：在 index.html 搜索 Selected projects 或 Research experience，编辑相应条目。
- **简历**：编辑 cv.html 更新网页版简历。若要提供 PDF，在 assets 里上传公开版 CV.pdf，然后把 index.html 中的 href="cv.html" 改成 href="assets/CV.pdf"，链接文字改为 CV (PDF)。
- **样式**：字体、配色、宽度和小屏布局集中在 style.css。

提交后到仓库 Actions 查看 Pages 部署结果，再打开主页并检查相关链接。
