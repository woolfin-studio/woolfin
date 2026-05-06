# Woolfin Studio Landing Page

一个适合部署到 GitHub Pages 的独立工作室静态站点模板，包含：

- 像素风首页
- 联系方式区块
- 独立隐私政策页面
- 适合直接发布的纯静态结构

## 文件结构

- `index.html`：首页
- `privacy.html`：隐私政策页
- `styles.css`：全站样式
- `.nojekyll`：告诉 GitHub Pages 直接按静态文件发布

## 本地修改

1. 编辑 `index.html` 中的工作室名称、首页文案和联系方式。
2. 按实际业务情况修改 `privacy.html` 中的隐私政策内容。
3. 如需调整像素风配色和布局，修改 `styles.css`。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库。
2. 把当前目录推送到该仓库。
3. 打开仓库 `Settings > Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. 分支选择 `main`，目录选择 `/ (root)`。
6. 保存后等待 GitHub Pages 构建完成。

如果是用户主页仓库，仓库名可使用 `yourname.github.io`。
如果是项目主页仓库，默认地址通常会是 `https://yourname.github.io/repository-name/`。
