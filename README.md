# IPFS 图床

> 简洁、开源、免费的 IPFS 图床服务，基于 xlog API 逆向，由 EdgeOne 提供全球 CDN 加速。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/H2O-ME/IPFS-img-host.svg)](https://github.com/H2O-ME/IPFS-img-host/stargazers)

> **⚠️ 本仓库仅供留档，不再维护。**
>
> - Crossbell IPFS 服务（`ipfs-relay.crossbell.io`）及网关（`ipfs.crossbell.io`）已无法使用
> - 演示站点 `img.tianhw.top` 与 CDN 域名 `ipfs.tianhw.top` 同步关闭

---

## 展示

> 以下截图仅供历史参考，站点已无法访问。

![网站截图](https://image.tianhw.top/ipfs/3.webp)
![网站截图](https://image.tianhw.top/ipfs/4.webp)
![网站截图](https://image.tianhw.top/ipfs/5.webp)

---

## 使用

> **已关闭** — ~~访问 [img.tianhw.top](https://img.tianhw.top/) 即可使用~~


[![Deploy to EdgeOne Pages](https://cdnstatic.tencentcs.com/edgeone/pages/deploy.svg)](https://edgeone.ai/pages/new?repository-url=https://github.com/H2O-ME/IPFS-img-host)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/H2O-ME/IPFS-img-host)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/H2O-ME/IPFS-img-host)

---

## 文件大小限制

- 最大文件大小：30 MB

---

## 技术栈

| 类别 | 技术 | 备注 |
|------|------|------|
| 前端框架 | 原生 HTML / CSS / JavaScript | — |
| 样式 | Tailwind CSS | CDN 引入 |
| 动画 | GSAP | — |
| 存储 | IPFS（Crossbell API） | 已停用 |
| CDN | EdgeOne（`ipfs.tianhw.top`） | 已关闭 |

---

## 项目结构

```
├── index.html    # 主页面（上传界面）
├── script.js     # 核心逻辑（上传、进度、结果展示）
├── style.css     # 自定义样式
├── LICENSE       # MIT 许可证
└── README.md     # 项目说明
```

---

## 许可证

本项目采用 [MIT 许可证](./LICENSE)。
