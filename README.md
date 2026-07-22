# 露珠小院 · Dewdrop Courtyard

小清新风格的休闲种田 Web UI 原型。

## 在线体验

GitHub Pages：https://xiaoqianran.github.io/Web003-dewdrop-garden/

（推送到 `main` 后由 Actions 自动部署）

## 玩法

播种 → 浇水 → 过夜成长 → 收获，循环照料九宫格花圃。

## 本地运行

用浏览器直接打开 `index.html` 即可，无需构建。

## 部署

仓库已配置 GitHub Actions → Pages：

- 工作流：`.github/workflows/deploy-pages.yml`
- 触发：`main` 分支 push，或手动 `workflow_dispatch`
- 产物：仅上传 `index.html` 到 Pages

## 提交规范

遵循阿里 / Angular 约定式提交：

```
<type>(<scope>): <subject>
```

常用 type：`feat` / `fix` / `docs` / `style` / `refactor` / `chore` / `ci`
