# moon-

这是一个小型网页开发项目，包含一个图书管理信息系统的静态页面实现。

## 项目内容

- 一个单页 HTML 应用
- 图书新增、编辑、删除
- 图书借阅与归还
- 本地存储（localStorage）持久化
- 响应式页面布局

## 本地预览

在项目根目录运行：

```bash
python3 -m http.server 8000
```

然后访问：

```text
http://localhost:8000
```

## GitHub Pages 部署

项目已包含 GitHub Actions 配置，支持自动部署到 GitHub Pages。

步骤：
1. 将代码推送到 GitHub 仓库
2. 进入仓库的 Settings -> Pages
3. 选择 Source: GitHub Actions
4. 等待构建完成

## 文件说明

- `index.html`：主页面和业务逻辑
- `.github/workflows/pages.yml`：GitHub Pages 自动部署配置
