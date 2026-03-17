my-blog/                      # 本地仓库根
├─ _config.yml                # Jekyll 配置（站点标题、主题、插件等）
├─ index.md                   # 首页（可用 Markdown）
├─ README.md                  # GitHub 仓库说明（会显示在 GitHub 上）
├─ _layouts/
│  ├─ default.html            # 基本 HTML 模板（包含 html head）
│  └─ post.html               # 帖子页面模板
├─ _includes/
│  ├─ header.html
│  └─ footer.html
├─ _posts/
│  └─ 2026-03-17-algo-note.md # 示例笔记（Markdown + front matter）
├─ assets/
│  ├─ css/
│  │  └─ style.css            # 所有样式在这里
│  ├─ js/
│  │  └─ main.js
│  └─ images/
└─ docs/                      # 可选：放生成后静态站点（或用于其它部署方式）