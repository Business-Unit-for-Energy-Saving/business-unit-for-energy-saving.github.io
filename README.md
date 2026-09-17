# Business-Unit-for-Energy-Saving Pages

`business-unit-for-energy-saving.github.io` 是节能业务单元的公开 Pages 站点。

站点展示组织定位、业务边界和节能行业公开资料简报，不承载内部需求、
客户隐私、原始页面、数据库、附件全文、生产配置或敏感凭据。

## 简报

- `index.md`：组织与简报入口。
- `reports/YYYY-MM-DD.md`：按日期汇总运行记录。
- `reports/YYYY-MM-DD-HHMMSS-RUN_ID.md`：单次采集的短摘录和原文链接。
- 页面按 GitHub Pages 的 `main` 根目录配置构建，保留 Markdown front matter。
- 输出由私有采集仓库的 `public-report` 命令生成，不手工复制内部 `data/`。

2026-09-17 首份公开简报来自 GitHub Actions 的真实采集结果：
4 个启用来源、6 篇基线归档、0 个正文错误、17 条待处理队列。
基线包含历史资料，不代表这些文章都在采集当天发布。

采集仓库已配置 `PAGES_DEPLOY_TOKEN`，后续由每日 GitHub Actions 自动更新；
原始内容和运行明细仅保存在私有采集环境。
