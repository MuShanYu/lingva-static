# lingva-static

LingVa Chrome 扩展的静态页面托管仓库，目前用于存放 Chrome 网上应用店审核所需的隐私权政策页面。

- `index.html` — 隐私权政策正文，用于 GitHub Pages 直接作为首页展示
- `privacy-policy.md` — 同内容的 Markdown 源文件，便于后续编辑维护

## 发布方式

仓库当前保持私有，待内容准备完成后，在 GitHub 仓库 Settings → Pages 中启用 GitHub Pages（Branch: `main` / root），即可通过
`https://mushanyu.github.io/lingva-static/` 公开访问隐私权政策页面。

修改 `privacy-policy.md` 后，请同步更新 `index.html` 中的对应内容，保持两者一致。
