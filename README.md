# Neon Cyber Portfolio

赛博朋克风格个人网站模板，适合嵌入式/硬件/软件工程师。

## 🚀 部署到 GitHub Pages

### 方式一：一键部署

1. 在 GitHub 创建仓库 `https://github.com/<你的用户名>/<你的用户名>.github.io`
2. 在终端运行：

```bash
cd C:\Users\Administrator\personal-site
git init
git add .
git commit -m "🚀 Initial commit: cyberpunk portfolio"
git branch -M main
git remote add origin https://github.com/<你的用户名>/<你的用户名>.github.io.git
git push -u origin main
```

3. 去 GitHub 仓库 Settings → Pages → 选 Deploy from branch `main` / `/ (root)`
4. 等几分钟，访问 `https://<你的用户名>.github.io` 即可

### 方式二：项目页面

如果想放在项目子路径 `https://<你的用户名>.github.io/my-site`：

1. 把 `index.html` 里的所有 `/` 开头的路径换成相对路径
2. 在 GitHub 仓库 Settings → Pages 选 Deploy from branch

## ✏️ 自定义内容

打开 `index.html`，找到开头的 `CONFIG` 对象：

```js
const CONFIG = {
    name: 'Your Name',           // ← 改你的名字
    skills: [ ... ],             // ← 改你的技能
    projects: [ ... ],           // ← 改你的项目
};
```

其他需要修改的地方：
- 页面顶部的名称和标题
- 关于我部分的介绍文字
- 联系方式（email、location）
- 页脚的社交链接
- Favicon（可选）

## 🎨 配色参考

| 颜色 | 用途 |
|------|------|
| `#ff00ff` (霓虹粉) | 主色调，强调色 |
| `#00ffff` (霓虹青) | 辅助色，链接 |
| `#7000ff` (紫色) | 渐变过渡 |
| `#0a0a0f` (深黑) | 背景 |

## 📄 License

MIT
