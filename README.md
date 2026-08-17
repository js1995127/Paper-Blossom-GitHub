# Paper Blossom

这是可直接部署到 GitHub Pages 的静态版本，不需要安装依赖，也不需要运行构建命令。

## 部署方法

1. 在 GitHub 新建一个 repository。
2. 将本文件夹内的所有内容上传到仓库根目录；请保留 `assets` 文件夹以及 `.nojekyll` 文件。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 下选择 **Deploy from a branch**。
5. Branch 选择 `main`，Folder 选择 `/ (root)`，点击 **Save**。
6. 等待约 1–3 分钟，GitHub 会显示网站链接。

如果将来修改源码并重新导出，请同时替换 `index.html` 和整个 `assets` 文件夹，因为文件名带有版本指纹。
