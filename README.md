# 锅圈小炒出海 · AI 化管理体系驾驶舱

> 多伦多样板 · 给杨总看的 CEO Cockpit 原型

## 模块

- 🎯 CEO 驾驶舱（KPI + 花费曲线 + 风险预警 + 项目进度 + 全球地图 + 机器人 + 视频监控）
- 🏛 精简编制（FT 5 + 国内远程 10 + PT 12 + 外包 14）
- 🤖 AI Agent 矩阵（15 个 Agent + Master 编排）
- 🔧 部门工作台 mockup（9 个部门）
- 📊 端到端流程
- ⚙️ 技术架构（4 层）
- ⚠️ 风险监控中心
- 🎬 场景演示（毛利红线 7 分钟闭环）
- 🗺 18 个月路线图
- 🌍 全球布局地图（Leaflet + CartoDB）
- 🍳 小炒机器人（IoT 实时表 + 调度 Agent）
- 📹 末端视频监控（可选）

## 技术栈

- HTML + Tailwind CSS（CDN）
- Chart.js（曲线）
- Leaflet（真世界地图）
- 浅色主题 · 手机自适应（断点 1280 / 900 / 640）
- AI 决策抽屉（4 种关闭方式）

## 部署

部署到 [腾讯云 EdgeOne Pages](https://edgeone.ai/pages) — Git push 自动部署到全球边缘节点。

```
https://guoquan-cockpit-npral13s.edgeone.cool/
```

## 文件结构

```
.
├── index.html          ← 仪表盘主体（部署时从 锅圈小炒出海AI化_驾驶舱原型.html 复制）
├── 锅圈小炒出海AI化_驾驶舱原型.html  ← 源文件
├── gq_logo_final.png   ← 头部 logo
├── gq_logo_header.png  ← 备用
└── README.md
```
