# lingva-static

LingVa Chrome 扩展的静态页面托管仓库，用于存放不需要随扩展包分发的静态内容：隐私权政策与使用手册。

- `index.html` — 首页，导航到隐私政策与中/英文使用手册
- `privacy-policy.html` / `privacy-policy.md` — 隐私权政策（正文 + Markdown 源文件）
- `help.html` — 使用手册（中文）
- `help-en.html` — 使用手册（English）
- `assets/style.css` — 各页面共用样式（浅/深色自适应，无外部依赖）

## 发布方式

仓库当前保持私有，待内容准备完成后，在 GitHub 仓库 Settings → Pages 中启用 GitHub Pages（Branch: `main` / root），即可通过
`https://mushanyu.github.io/lingva-static/` 公开访问。

## 维护说明

- 修改 `privacy-policy.md` 后，请同步更新 `privacy-policy.html` 中的对应内容，保持两者一致。
- 中英文使用手册（`help.html` / `help-en.html`）内容需保持同步：任一语言更新功能说明后，请同步翻译到另一份文件。
- 使用手册内容与 `easy-translate` 主仓库的 `src/views/setting/components/GeneralOption.tsx`、`manifest.json` 等实际功能保持一致，主仓库功能变更（新增设置项、调整权限等）时需回来同步更新。
