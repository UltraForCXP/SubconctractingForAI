# SubconctractingForAI

委外加工 / AI 相关项目的资料与代码仓库，使用 Git 进行版本管理。

## 首次克隆

```bash
git clone git@github.com:UltraForCXP/SubconctractingForAI.git
cd SubconctractingForAI
```

## 日常操作

```bash
git pull --rebase origin main
git add . && git commit -m "feat: 本次改动说明"
git push
```

## 约定

- 主分支为 `main`，日常改动建议先建 `feature/xxx` 分支再合并
- 依赖、构建产物、日志、密钥与环境配置已由 `.gitignore` 排除，请勿强制提交
