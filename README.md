# official-website

用于测试 GitHub Pages 发布与访问的中文静态信息展示网站。

- 网站：https://infegz.github.io/official-website/
- 仓库：https://github.com/infegz/official-website
- 内容：项目介绍、功能概览、最新公告
- 适配：桌面与移动端；支持键盘导航、跳转到主要内容和减少动画偏好

页面中的文字均为演示内容，不代表真实机构或正式服务。

## 本地预览

在仓库目录中运行 `python3 -m http.server 8080`，访问 http://localhost:8080 。也可以直接打开 `index.html`。

## 修改内容

- `index.html`：页面内容、导航、元信息和内嵌 favicon。
- `styles.css`：配色、布局和响应式样式。
- `.nojekyll`：使用静态文件直接发布。

无第三方依赖，无需安装或构建。资源使用相对路径，支持 GitHub Pages 项目子路径。

## GitHub Pages

在 Settings → Pages 中设置：

1. Source：Deploy from a branch。
2. Branch：`main`，目录：`/ (root)`。
3. 点击 Save。GitHub 自动运行 Pages 构建和部署。

后续提交到 `main` 会自动更新网站。部署结果可以在仓库 Actions 中查看。
