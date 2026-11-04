# 日常使用指南

## 基本流程

1. 在 `docs/` 目录中修改或新增 Markdown 文件。
2. 运行 `python -m mkdocs serve` 在本地预览。
3. 使用 `git add` 和 `git commit` 保存修改。
4. 使用 `git push origin main` 推送到 GitHub。
5. 在 Actions 页面查看构建与部署状态。
6. 打开网站，确认内容已经更新。

## Git 核心概念

| 概念 | 含义 |
| --- | --- |
| 仓库（repository） | 保存项目文件和历史记录的地方 |
| 提交（commit） | 一次带有说明的版本记录 |
| 分支（branch） | 独立的开发线，本站使用 `main` |
| 远程（remote） | 托管在 GitHub 上的仓库，名称通常为 `origin` |

## 常用命令示例

```bash
git status
git add docs/index.md
git commit -m "更新首页内容"
git push origin main
```

更多命令说明请见 [API 参考](api.md)。