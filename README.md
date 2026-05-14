# 兰星个人学术主页

这是一个可直接部署到 GitHub Pages 的静态个人学术主页，入口文件是 `index.html`。

## 本地预览

直接用浏览器打开 `index.html` 即可预览。也可以在仓库目录运行：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 部署到 GitHub Pages

1. 在 GitHub 创建仓库，推荐命名为 `你的用户名.github.io`。
2. 将本目录内容提交并推送到该仓库的 `main` 分支。
3. 如果仓库不是 `你的用户名.github.io`，进入 GitHub 仓库的 `Settings -> Pages`，选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/root`。
4. 等待 GitHub Pages 构建完成后访问页面地址。

## 更新内容

- 头像：替换 `assets/profile.png`。
- 个人信息、论文和招生信息：编辑 `index.html`。
- 页面样式：编辑 `styles.css`。
