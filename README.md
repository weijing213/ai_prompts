<div align="center">

# 🪄 AI 提示词工具箱 (AI Prompt Toolbox)
### 专为科研人员、开发者和深度用户打造的高效 Prompt 指令集

[![GitHub Stars](https://img.shields.io/github/stars/weijing213/ai_prompts?style=social)](https://github.com/weijing213/ai_prompts)
[![GitHub Forks](https://img.shields.io/github/forks/weijing213/ai_prompts?style=social)](https://github.com/weijing213/ai_prompts)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**🔗 [网页链接](https://weijing213.github.io/ai_prompts/) | [提交需求](https://github.com/weijing213/ai_prompts/issues)**

</div>

---

## 📖 项目简介

**AI 提示词工具箱** 是一个纯静态、无需后端的高质量 Prompt 集合网站。它汇集了 **40+ 精心打磨的结构化提示词**，覆盖**文献精读**、**学术写作润色**、**中英互译**、**顶会审稿模拟**以及**代码调试**等核心场景。

作为一名科研搬砖人（WeiJing），我将日常高频使用的高阶指令进行了系统化整理。无论你是正在苦苦读论文的研究生，还是需要投稿顶会的 Researcher，抑或是希望提升编码效率的开发者，这个工具箱都能让你少掉几根头发。

## ✨ 核心亮点

- 🧠 **高质量模板**：不是简单的“帮我把这段话翻译成英文”，而是包含角色设定、执行协议、输出格式的**结构化高阶 Prompt**。
- 🏷️ **场景化分类**：涵盖 `文献精读` (26个) · `学术写作` (14个) · `翻译` · `审稿` · `编程` 等专栏。
- ⚡ **一键复制**：点击按钮即刻将复杂的学术指令复制到剪贴板，无缝粘贴到 GPT-4o、Claude 3.5、Gemini 等大模型中。
- 🔍 **极速筛选**：左侧导航栏支持按分类浏览和关键词模糊搜索，开箱即用。
- 📱 **响应式设计**：适配桌面端和移动端，随时随地查阅指令。
- 🎨 **现代 UI**：借鉴系统性设计美学，配合 Tailwind CSS 打造，阅读体验丝滑。

## 🗂️ 提示词分类速览

### 1. 📚 文献精读 (Literature Deep Reading)
从摘要概览、创新点预测、方法剖析、结果质疑，到未来研究方向探讨，全面拆解一篇论文。
- **代表指令**：`Q1. 快速概览`、`Q10. 研究方法批判性评估`、`Q13. 逻辑结构与论证缺陷分析`
- **适用对象**：组会汇报人、综述撰写者、刚入门的研究生。

### 2. ✍️ 学术写作与润色 (Academic Writing)
打磨你的论文语言。支持**中译中**（口语转书面语）、**降 AI 率**（去除 AI 味）、**逻辑检查**等硬核任务。
- **代表指令**：`降低AIGC率`、`去AI味`、`表达润色（中/英）`、`扩写/缩写`
- **适用对象**：正在投稿 CVPR/NeurIPS/ACL 或撰写中文核心期刊的科研人员。

### 3. 🌐 专业翻译 (Translation)
针对科研场景定制的翻译指令，自带 LaTeX 源码保护机制，拒绝乱改数学公式。
- **代表指令**：`中转英（学术版）`、`英转中（逻辑校验版）`

### 4. 👨‍⚖️ 模拟审稿 (Reviewer Simulation)
让 AI 扮演最挑剔的 Reviewer，在投稿前给你的论文挑刺。
- **代表指令**：`论文整体以 Reviewer 视角进行审视`

### 5. 💻 编程辅助 (Coding)
从 Bug 诊断到性能优化，提升开发效率。
- **代表指令**：`代码 Bug 诊断与修复`、`代码重构与性能优化`、`自动化单元测试生成`

## 🚀 如何使用

1. **在线访问**：直接访问 [https://weijing213.github.io/ai_prompts/](https://weijing213.github.io/ai_prompts/)。
2. **选择分类**：点击左侧导航栏（如 “写作”、“翻译”）筛选。
3. **查找指令**：在搜索框输入关键词（如 “润色”、“代码”）。
4. **复制使用**：点击卡片上的 **“复制提示词”** 按钮。
5. **粘贴对话**：将剪贴板内容粘贴到 ChatGPT、Claude、Kimi 等对话框中。
6. **替换参数**：务必将 `[ ]` 内的占位符替换为你自己的实际内容（如 `[论文摘要]`、`[实验数据]`）。

## 🛠️ 技术栈

- **核心**：原生 HTML / CSS / JavaScript
- **样式框架**：Tailwind CSS (CDN)
- **图标库**：Font Awesome 6
- **部署**：GitHub Pages / Vercel / 任意静态服务器
