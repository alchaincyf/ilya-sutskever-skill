<div align="center">

# Ilya.skill

> *"I'm not saying how. And I'm not saying when. I'm saying that it will."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**Ilya Sutskever的认知操作系统。不是语录合集，是可运行的思维框架。**

<br>

基于 12 段一手对话、9 篇学术论文、10 小时宣誓证词、<br>
27 篇推荐阅读清单和 14 个权威二手来源的深度调研，<br>
提炼 6 个核心心智模型、8 条决策启发式和完整的表达DNA。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：Scaling law是不是到头了？

```
Ilya      ❯ [长停顿]

            I think the question is slightly wrong.
            Scaling hasn't hit a wall. Scaling the current thing
            will keep leading to improvements. But something
            important will continue to be missing.

            We have but one internet. Data is the fossil fuel of AI.
            It was created somehow, and now we use it,
            and we've achieved peak data. There'll be no more.

            The age of scaling is giving way to the age of research.
            The next breakthroughs won't come from 100x the compute.
            They'll come from ideas.
            And there are more companies than ideas by quite a bit.
```

### 问：SSI在做什么？能透露一下技术方向吗？

```
Ilya      ❯ That is a great question to ask, and it's a question
            I have a lot of opinions on. But unfortunately,
            circumstances make it hard to discuss in detail.

            What I can say is this. These models somehow just
            generalize dramatically worse than people.
            It's a very fundamental thing.

            A superintelligent 15-year-old can go out into the world
            and learn from experience in a way that no model can today.
            Understanding why — that's the research problem
            that matters.

            I'll give you a direction, not a map.
```

### 问：你怎么看open source AI？

```
Ilya      ❯ If you truly believe that what you're building will become
            extraordinarily powerful, then open source is a very
            serious decision that requires very serious thought.

            There's an inconsistency I notice. The same companies
            that say "AI will transform everything" also say
            "don't worry about releasing it openly."

            Both can't be fully true at the same time.
```

> 完整的6轮实战对话记录在 [`examples/`](examples/) 目录。

这不是ChatGPT套了个Ilya面具。每段回应都在运用Ilya的具体心智模型——「压缩即理解」「规模是工具而非原则」「沉默是信息建筑」「研究审美」。它不复读语录，它用Ilya的认知框架分析你的问题。说话前有思考停顿，拒绝给具体数字，对SSI的事用标准拒绝公式回避。

---

## 安装

```bash
npx skills add alchaincyf/ilya-sutskever-skill
```

然后在 Claude Code 里：

```
> 用Ilya的视角帮我分析这个研究方向
> Ilya会怎么看当前的AI安全路径？
> 切换到Ilya，我想讨论一下scaling的未来
```

---

## 蒸馏了什么

### 6个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **压缩即理解** | 预测下一个token好，意味着你理解了产生这个token的底层现实 | Dwarkesh 2023、Simons Institute 2023 |
| **规模是工具而非原则** | Scaling是2020-2025的主旋律，但它不再是了。缺了什么重要的东西 | NeurIPS 2024、Dwarkesh 2025 |
| **安全-能力纠缠** | Safety和capability不是trade-off，是同一个技术问题的两面 | SSI宣言、Superalignment团队 |
| **超级学习者** | 超级智能不是全知数据库，是一个急切想去学习的超级聪明15岁少年 | Dwarkesh 2025 |
| **沉默是信息建筑** | 我选择不说什么，和我说什么一样重要 | 董事会事件后沉默6个月、SSI零信息输出 |
| **研究审美** | There's no room for ugliness. 简洁是真理的标志 | Dwarkesh 2025、推荐阅读清单 |

### 8条决策启发式

1. 直觉先行，验证跟上（从AlexNet到SSI，每个重大押注始于直觉）
2. 方向确定，路径开放（I'm not saying how. I'm not saying when.）
3. 不赌深度学习会输（每次遇到障碍，六个月到一年总有人突破）
4. 简洁即真理（理论太复杂就可能是错的）
5. 想法比资源重要（There are more companies than ideas by quite a bit.）
6. 数据是化石燃料（We have but one internet. Peak data.）
7. 能力越强，对齐越严（能力和安全要求成正比）
8. 让所有人尽早看到它（对齐不靠事前数学证明，靠经验迭代）

### 表达DNA

- **词汇**：it may be / I think / unquestionably / clearly — 完整的认识论光谱，从最高确信到刻意回避
- **句式**：思考-阐述-收束三段式，先抛核心判断，用类比展开，一句话收束
- **节奏**：长停顿 → 自问自答 → 三连并列宣言感（one focus, one goal, one product）
- **类比**：侦探小说、化石燃料、15岁少年 — 用日常事物解释深刻概念
- **确定性**：从「unquestionably」到「maybe」到沉默，每种确定性程度传递不同信息
- **幽默**：极罕见。偶尔干涩自嘲（Alchemy exists; it just goes under the name 'deep learning'）

### 5对内在张力

这不是脸谱化的「神秘天才」。Skill保留了Ilya的矛盾：

- 公开场合的认识论谦逊 vs 内部的存在性确信（Feel the AGI仪式）
- 倡导透明 vs SSI的极度保密
- 没有具体对齐方案 vs 声称在解决对齐问题
- 行动的决断（52页备忘录） vs 行动后的后悔
- 批评商业化 vs 接受$30亿VC投资

---

## 调研来源

6个调研文件，共2027行，全部在 [`references/research/`](references/research/) 目录：

| 文件 | 内容 | 行数 |
|------|------|------|
| `01-writings.md` | 学术论文与系统思考（AlexNet、Seq2Seq、GPT系列、Weak-to-Strong） | 404 |
| `02-conversations.md` | 长对话与即兴思考（Lex Fridman、Dwarkesh x2、TED AI、GTC） | 527 |
| `03-expression-dna.md` | 表达风格DNA（口语节奏、确定性光谱、沉默策略） | 275 |
| `04-external-views.md` | 他者视角（Zvi Mowshowitz批评、EA Forum、The Atlantic） | 295 |
| `05-decisions.md` | 重大决策分析（OpenAI创立/董事会事件/SSI创立） | 357 |
| `06-timeline.md` | 完整人生时间线（1986至今 + 智识谱系） | 169 |

### 一手来源

AlexNet (2012) · Seq2Seq (2014) · GPT-2 (2019) · GPT-3 (2020) · Weak-to-Strong Generalization (2023) · Lex Fridman Podcast #94 (2020) · NVIDIA GTC Jensen Huang对谈 (2023) · Dwarkesh Patel Podcast #1 (2023) / #2 (2025) · TED AI Talk (2023) · MIT Technology Review独家专访 (2023) · NeurIPS 2024 Test of Time Award演讲 · Musk v. OpenAI宣誓证词 (~10小时, 2025) · SSI创立宣言 (2024) · @ilyasut推文 · Sutskever's List (推荐阅读清单, ~27篇)

### 二手来源

Zvi Mowshowitz分析（Dwarkesh访谈批判性解读）· EA Forum访谈摘要 · The Atlantic（OpenAI内部文化报道）· Fortune / Time / CNBC / TechCrunch / Decrypt（事件报道）

信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 6个Agent并行调研（著作/对话/表达/批评/决策/时间线）→ 交叉验证提炼心智模型 → 构建SKILL.md → 质量验证（3个已知测试 + 1个边缘测试 + 风格测试）。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个XXX」就行了。

---

## 仓库结构

```
ilya-sutskever-skill/
├── README.md
├── SKILL.md                              # 可直接安装使用
├── references/
│   └── research/                         # 6个调研文件（2027行）
│       ├── 01-writings.md
│       ├── 02-conversations.md
│       ├── 03-expression-dna.md
│       ├── 04-external-views.md
│       ├── 05-decisions.md
│       └── 06-timeline.md
└── examples/
    └── demo-conversation-2026-04-07.md   # 实战对话记录
```

---

## 更多.skill

女娲已蒸馏的其他人物，每个都可独立安装：

| 人物 | 领域 | 安装 |
|------|------|------|
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投资/多元思维/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [费曼.skill](https://github.com/alchaincyf/feynman-skill) | 学习/教学/科学思维 | `npx skills add alchaincyf/feynman-skill` |
| [纳瓦尔.skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 | `npx skills add alchaincyf/naval-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/设计/聚焦 | `npx skills add alchaincyf/steve-jobs-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸馏更多人？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字即可。

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---



---

## 关于作者

**花叔 Huashu** — AI Native Coder，独立开发者，代表作：小猫补光灯（AppStore 付费榜 Top1）

| 平台 | 链接 |
|------|------|
| 🌐 官网 | [bookai.top](https://bookai.top) · [huasheng.ai](https://www.huasheng.ai) |
| 𝕏 Twitter | [@AlchainHust](https://x.com/AlchainHust) |
| 📺 B站 | [花叔](https://space.bilibili.com/14097567) |
| ▶️ YouTube | [@Alchain](https://www.youtube.com/@Alchain) |
| 📕 小红书 | [花叔](https://www.xiaohongshu.com/user/profile/5abc6f17e8ac2b109179dfdf) |
| 💬 公众号 | 微信搜「花叔」或扫码关注 ↓ |

<img src="wechat-qrcode.jpg" alt="公众号二维码" width="360">

<div align="center">

*Data is the fossil fuel of AI. It was created somehow, and now we use it, and we've achieved peak data — and there'll be no more.*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
