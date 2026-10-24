# 我的运动博客

免费、纯静态的中文运动博客，无需安装依赖，不含私人测试记录。

## 首次发布

1. 登录 GitHub，点击右上角 + → New repository。
2. Repository name 填 bqiuruixing-art.github.io，选择 Public（内容和代码均公开），创建仓库。若同名仓库已存在，先检查内容，不要覆盖。
3. 在仓库中通过 uploading an existing file 或 Add file → Upload files，上传本目录中的 index.html 和 README.md。文件应位于仓库根目录，不要再套一层 sports-blog 文件夹。
4. 点击 Commit changes 提交。
5. 打开仓库 Settings → Pages，在 Build and deployment 中选择 Deploy from a branch，分支选择实际上传使用的分支（通常为 main），目录选 / (root)，保存。
6. 等待部署完成，访问 https://bqiuruixing-art.github.io/ 。如暂时未生效，可到 Actions 查看部署状态。无需购买域名或选择付费套餐。

## 发表文章

在仓库中打开 index.html，点击铅笔编辑。找到带有“发表新文章”注释的位置，复制一个完整的 <article>...</article> 区块并修改标题、标签和正文，提交后等待网站重新部署。示例文章应替换为自己的公开内容。正文中的 &、<、> 应分别写为 &amp;、&lt;、&gt;。

可上传图片，例如 images/walk.jpg，再在文章中使用 <img src="images/walk.jpg" alt="散步风景" style="max-width:100%;height:auto">。注意图片版权和位置隐私。

## 重要边界

这不是在线登录后台或可视化文章编辑器；不含数据库、评论、AI 接口和定时发文。上传到公开仓库的内容及提交历史可能被他人查看，切勿上传密码、验证码、私人日记、体重或健康信息。免费托管仍受 GitHub 的服务条款及使用额度限制，不保证未来政策永远不变。

## 本地预览

双击 index.html 即可在浏览器预览。此文件由 AI 准备，尚未上传 GitHub，也尚未完成线上部署验证。
