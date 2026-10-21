# Xeldule

Unreal Engine / C++ 技术笔记。

正式网站：https://xeldule.github.io/

本站使用 Hexo 8.1.2 与 [Redefine 2.9.0](https://github.com/EvanNotFound/hexo-theme-redefine)。

## 发布方式

- `site-part-*.zip` 是已构建、审核后的静态站点分包，保留全部目录结构，不是原始导出备份。
- GitHub Actions 校验每个分包和站点文件的 SHA-256 后，仅将解压后的 `public/` 目录发布到 GitHub Pages。
- 分包、校验清单、工作流和本 README 不会作为网站内容发布。
- 网站含 9 篇文章、205 个原始媒体文件及已确认的首页背景和分类结构。
- 写作源码和锁定依赖另行保留。更新时从生产源码构建，替换静态分包和校验清单，提交到 `main` 后自动发布。

仅使用 GitHub 官方 Pages 工作流，不需要自行保存部署密钥。
