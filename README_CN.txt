GitHub Pages 发布包说明
日期: 2026-07-01

这个文件夹已经整理成可直接上传到 GitHub 仓库根目录的结构。

包含内容:
- index.html
- terms.html
- license.html
- privacy.html
- contact.html
- tokutei.html
- legal.css
- assets/
- CNAME
- .nojekyll

你现在要做的事:
1. 登录 GitHub
2. 新建一个 public repository
3. 把本文件夹里的全部内容上传到仓库根目录
4. 打开仓库 Settings -> Pages
5. Source 选择:
   - Deploy from a branch
6. Branch 选择:
   - main
   - /(root)
7. 保存
8. 等 GitHub Pages 生成站点
9. 在仓库 Pages 页面确认 Custom domain 显示为:
   cadtools-lab.com
10. 等 HTTPS 证书签发后，勾选 Enforce HTTPS

注意:
- 这个仓库建议用 public，否则 GitHub Free 下 Pages 方案可能不符合你的低成本目标。
- CNAME 文件已经写好，内容是 cadtools-lab.com。
- .nojekyll 文件已经加好，避免 GitHub Pages 对静态文件做不必要处理。
