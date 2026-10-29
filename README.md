# 疫研 VaxRWE

疫苗真实世界研究平台交互 Demo，使用合成演示数据。

- [在线体验](https://huiwen7.github.io/vax-rwe-demo/)
- [下载完整 React 源码](./vax-rwe-source.zip)
- 本地使用：下载本仓库 ZIP，解压后用 Chrome 或 Edge 双击 `index.html`。无需安装或启动服务。

## 功能

CSV/Excel 上传、11 个数据模块、按字段自动拆分、字段检查、模块完整性、描述性图表和规则式数据问答、有效性/安全性研究预检及配置草稿。

这是前端演示，不含真实 AI 模型或正式统计研究引擎。上传的数据仅在浏览器当前页面内处理，刷新后清空。

## 修改源码

解压 `vax-rwe-source.zip`，安装 Node.js 后运行：

```bash
npm install
npm run dev
```

详细说明和合成示例表格见源码包内的 README.md 和 public/samples/。
