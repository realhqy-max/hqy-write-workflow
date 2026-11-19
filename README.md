# hqy-write-workflow

面向科研论文写作、结构重构、语言精修与投稿前自检的工作流 Skill，结合国际通用学术写作方法论（IMRAD、Swales CARS 引言模型、Old-to-New 段落衔接、清晰度与去名词化原则）及中文工科顶刊实践。

## 核心特点

- **双模式支持**：支持 `中文工科顶刊模式`（允许“结果与分析”按专题合并、无主句/“本文”、工程落点）与 `英文 SCI 模式`（严格分离 Results/Discussion、主动语态、时态与结论强度校准表），不写死特定刊物文献比例或字数上限。
- **四阶段闭环**：立骨与红线对照（两阶段起草：先段落地图、后连贯正文） → 分章撰写 → 去黑话/去“代码翻译腔”/去 AI 腔精修 → 图表分工、文献核查与排版验收。
- **严格学术边界**：正向立论（No negative framing）、结论不超越证据强度、禁用网页/软件手册作文献、改稿不覆盖原稿。

## 目录结构

```text
hqy-write-workflow/
├── SKILL.md
├── README.md
└── references/
    ├── structure-and-sections.md
    ├── style-clarity-anti-ai.md
    └── figures-tables-citations.md
```

## 安装方式

将本仓库克隆到你的全局 Skills 目录即可：

```bash
# Windows (PowerShell)
git clone https://github.com/realhqy-max/hqy-write-workflow.git "$env:USERPROFILE\.gemini\config\skills\hqy-write-workflow"

# macOS / Linux
git clone https://github.com/realhqy-max/hqy-write-workflow.git ~/.gemini/config/skills/hqy-write-workflow
```
