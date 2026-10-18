# OneHRL 论文展示网站

纯静态网站源码，包含 HTML、CSS、JavaScript、全部图片和论文 PDF，无需安装依赖或构建。

- 展示网页：https://yuhongwei22.github.io/onehrl-site/
- 源码仓库：https://github.com/yuhongwei22/onehrl-site

## GitHub Pages

在仓库的 **Settings → Pages** 中选择 **Deploy from a branch**，使用 `main` 分支的 `/ (root)` 目录。`.nojekyll` 使 GitHub Pages 直接发布静态文件。

## 本地运行

进入 `onehrl-site` 目录，执行：

```bash
python3 -m http.server 8000
```

然后打开 http://localhost:8000 。

## 文件

- `index.html`：页面内容与结构。
- `style.css`：排版、颜色和响应式样式。
- `app.js`：中英文切换、图像对比、案例切换、图像放大和引用复制。
- `assets/`：图片、图标和论文 PDF。

可将以上文件直接上传到静态网站托管服务，保持目录结构即可。字体通过 Google Fonts 加载，无法联网时使用系统字体。
