# 国内大模型价格看板

国内主流大模型厂商 API 价格的单页看板，单文件 HTML（`index.html`，自包含，无本地依赖）。

## 部署

- GitHub Pages：`Settings → Pages → Source: Deploy from a branch → main / (root)`
- 访问地址：`https://<用户名>.github.io/llm-price-board/`

## 说明

- 外部依赖仅 ECharts（jsDelivr CDN），断网环境下图表不可用。
- 数据内联在页面脚本中，更新价格需改 `index.html` 后重新提交。
