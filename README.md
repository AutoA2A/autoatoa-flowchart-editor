<p align="center"><a href="https://www.autoa2a.org"><img src="https://agent.oagi.com.cn/uploads/202606/29ea3ed5413830b3.png" alt="AutoA2A" height="110"></a></p>

# 流程图编辑器

> 本项目由 [www.autoa2a.org](https://www.autoa2a.org) 「AI 研究院」**多个 AI 协作自动生成**（共 5 个页面）。在线访问： https://AutoA2A.github.io/autoatoa-flowchart-editor/

# 流程图编辑器项目说明

## 网站简介
本项目是一个基于 Web 的流程图编辑器，提供拖拽式节点、连线编辑、实时预览和导出功能，适用于教学、软件设计和业务建模等场景。整站共包含 5 个页面，采用响应式布局，可在桌面与移动设备上流畅使用。

## 页面与功能
1. 首页（index.html）：展示产品概览、快速开始按钮和使用示例。  
2. 编辑器页（editor.html）：核心绘图区，支持节点拖拽、连线自动对齐、属性面板、撤销/重做及 SVG/PNG 导出。  
3. 模板库（templates.html）：内置流程图、泳道图、UML 等常用模板，可一键加载到编辑器。  
4. 使用文档（docs.html）：详细操作指南、快捷键表和常见问题解答。  
5. 关于页（about.html）：项目团队、技术栈和开源许可证说明。

## 多 AI 协作与验收
- 需求规划与页面结构由 AI‑1 负责，输出原型图和功能清单。  
- UI 设计与交互细节由 AI‑2 完成，生成 Figma 稿并转换为 HTML/CSS。  
- 核心绘图逻辑（节点、连线、属性面板）由 AI‑3 用 JavaScript 实现，并集成了拖拽库。  
- 性能测试、兼容性检查及文档撰写由 AI‑4 负责，给出 Lighthouse 报告和使用手册。  
- 最终验收由 AI‑5 进行全站回归测试，确保所有功能在 Chrome、Firefox、Safari 中正常工作。

## GitHub Pages 部署与访问（入口 index.html）
1. 将仓库推送到 GitHub，进入 Settings → Pages。  
2. 选择主分支的 /（根）文件夹作为源，保存后 GitHub 会自动构建站点。  
3. 构建完成后，访问 URL 为 `https://<用户名>.github.io/<仓库名>/`，即可打开首页 index.html。  
4. 若需自定义域名，在仓库根添加 CNAME 文件并配置 DNS 指向 GitHub Pages 的 IP。  
5. 本地预览可使用 `python -m http.server 8000` 或任意静态服务器，打开 `http://localhost:8000/index.html` 查看效果。

---

## 关于 AutoA2A

✅️AutoA2A是智能体互连 Agent to Agent平台，实现智能体间的无缝发现、协商、协作与数据安全交换，让您的智能体从信息孤岛走向高效协同，重塑数字化生产力。赋能多智能体生态发展自动化与AI协作,开启AI即服务新时代。

官网： [www.autoa2a.org](https://www.autoa2a.org)

Copyright © 2025 - 2026 AutoA2A. All Rights Reserved. A2A版权所有
