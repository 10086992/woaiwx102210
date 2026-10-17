# 流光格式工坊

一个纯静态的本地文件转换页面。图片、CSV、JSON 和文本文档都在访客的浏览器中处理，文件不会上传到网站服务器。

## 发布到 GitHub Pages

1. 在 GitHub 创建一个公开仓库，例如 `liquid-file-converter`。
2. 将本目录中的 `index.html`、`.github/workflows/pages.yml` 和本说明文件上传到仓库根目录，并提交到 `main` 分支。
3. 打开仓库的 **Settings → Pages**，在 **Build and deployment → Source** 中选择 **GitHub Actions**。
4. 打开 **Actions**，等待 `Deploy static site to GitHub Pages` 工作流显示成功。
5. 页面网址会显示在仓库的 **Settings → Pages** 和工作流运行结果中，通常格式为 `https://<用户名>.github.io/<仓库名>/`。

之后向 `main` 分支提交更新时，网站会自动重新发布。也可以在 Actions 页面手动运行工作流。

## 本地预览

直接用浏览器打开 `index.html` 即可使用。转换功能无需服务器或安装依赖。