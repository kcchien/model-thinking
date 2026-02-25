<div align="center">

<img src="assets/cover.svg" alt="Model Thinking — 思維模型工具箱" width="100%"/>

<br/>
<br/>

[![授權: MIT](https://img.shields.io/badge/授權-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Agent Skill](https://img.shields.io/badge/Agent_Skill-通用相容-blueviolet?style=flat-square)](#-相容的-ai-agent)
[![領域](https://img.shields.io/badge/領域-10_大知識域-34d399?style=flat-square)](#-十大知識領域)
[![模型](https://img.shields.io/badge/模型-200+-60a5fa?style=flat-square)](#-十大知識領域)
[![零依賴](https://img.shields.io/badge/零依賴-裝了就用-f59e0b?style=flat-square)](#-前置條件)

**把 200+ 個思維模型裝進你的 AI 助手，系統性擴展你的思考維度。**

[快速安裝](#-快速安裝) · [使用範例](#-你可以怎麼用) · [十大領域](#-十大知識領域) · [運作原理](#️-運作原理)

</div>

---

你做決策時，是靠直覺，還是有一套系統？

大多數人面對複雜問題時，只會用自己最熟悉的那一兩個角度去想。結果不是盲點太大，就是想了半天原地打轉。

**Model Thinking** 讓你的 AI 助手成為一個裝備了 200+ 個思維模型的思考夥伴。不是給你一份模型清單讓你自己讀——而是根據你的問題，即時挑選 2-3 個最合適的模型，從不同領域交叉分析，幫你看見自己看不見的角度。

## ⚡ 快速安裝

```bash
npx skills add kcchien/model-thinking
```

就這樣。當你請 AI 助手幫你分析問題、做決策、或學習思維模型時，它會自動啟用。

## 💬 你可以怎麼用？

用自然語言跟你的 AI 助手對話即可：

| 你說 | 發生什麼事 |
|------|-----------|
| *「幫我想清楚要不要接這個 offer」* | 自動用後悔最小化、機會成本、可逆性等模型交叉分析 |
| *「這個系統為什麼越修越壞？」* | 用系統基模（Shifting the Burden）診斷根因 |
| *「我們該不該搶先進入東南亞市場？」* | 用賽局理論、網路效應、肥尾風險三角驗證 |
| *「教我什麼是二階思考」* | 進入教學模式：概念 → 範例 → 常見錯誤 → 練習題 |
| *「用反向思考分析這個商業計畫」* | 直接套用指定模型 |
| *「幫我做風險評估」* | 引導模式：先問幾個關鍵問題，再選模型 |

### 三種模式，自動適配

| 模式 | 觸發條件 | 你會得到什麼 |
|------|---------|------------|
| **引導模式** | 問題模糊或複雜 | 2-3 個診斷問題 → 模型推薦 → 結構化分析 |
| **直接模式** | 問題清楚或指定模型 | 立即套用 2-3 個模型，交叉驗證 |
| **教學模式** | 想學習特定模型 | 一句話定義 → 具體範例 → 常見陷阱 → 練習題 |

你不需要知道哪個模型適用——描述你的問題，AI 會自動選擇。

## 🧠 十大知識領域

不只是模型清單，而是一套有組織的**思考工具箱**。每個領域獨立成冊，AI 按需載入，不浪費上下文視窗。

| 領域 | 涵蓋主題 | 代表模型 |
|------|---------|---------|
| **決策** (Decisions) | 選擇、判斷、認知工具 | 反向思考、二階效應、事前驗屍、六頂思考帽 |
| **系統** (Systems) | 回饋迴路、湧現、干預 | 存量與流量、槓桿點、成長極限、轉嫁負擔 |
| **統計** (Statistics) | 機率、推論、謬誤 | 貝氏思維、回歸均值、倖存者偏差、辛普森悖論 |
| **策略** (Strategy) | 賽局、競爭、談判 | 納許均衡、囚徒困境、BATNA、護城河 |
| **心理** (Psychology) | 偏誤、社會心理、動機 | 確認偏誤、損失趨避、從眾效應、鄧寧-克魯格 |
| **網路** (Networks) | 連結、影響力、平台 | 網路效應、梅特卡夫定律、小世界、弱連結 |
| **演算法** (Algorithms) | 計算思維、搜尋、排序 | 探索/利用、模擬退火、貪心法、快取策略 |
| **風險** (Risk) | 不確定性、脆弱性、黑天鵝 | 肥尾分佈、反脆弱、安全邊際、槓鈴策略 |
| **學習** (Learning) | 知識獲取、技能建構 | 間隔重複、刻意練習、費曼技巧、能力圈 |
| **經濟** (Economics) | 市場、激勵、資源配置 | 機會成本、供需、比較優勢、公地悲劇 |

### 跨領域組合 — 真正的威力所在

單一模型只看到一個面向。**Model Thinking** 的核心價值是跨領域組合：

```
問題：該不該推出新產品？

┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   決策域     │     │   系統域     │     │   決策域     │
│  事前驗屍    │ ──→ │ 回饋迴路     │ ──→ │  機會成本    │
│  失敗原因？  │     │ 哪個迴路贏？ │     │  不做的代價？│
└─────────────┘     └─────────────┘     └─────────────┘
        │                  │                   │
        ▼                  ▼                   ▼
    執行風險清單       正負迴路分析        資源配置建議
                       │
                       ▼
              ✅ 綜合建議：延後一季，先修核心產品流失率
```

模型之間**同意** = 高信心。模型之間**不同意** = 值得深挖的複雜性。

## ⚙️ 運作原理

**漸進式揭露架構** — AI 不會一次載入所有模型，而是按需取用：

| 階段 | 載入什麼 | 上下文成本 |
|------|---------|-----------|
| 待機 | 技能名稱 + 觸發描述 | ~100 詞 |
| 啟動 | SKILL.md 核心工作流 | ~800 詞 |
| 分析 | 相關領域的參考檔（1-2 個） | ~3,000 詞/檔 |
| 組合 | combinations.md（按需） | ~2,000 詞 |

這代表你的上下文視窗不會被用不到的模型塞滿。AI 只讀它需要的東西。

### 分析流程

```
你的問題
   │
   ▼
┌──────────────────────┐
│ 1. 分類問題模式       │  決策？系統？策略？資料？風險？
└──────────┬───────────┘
           ▼
┌──────────────────────┐
│ 2. 選擇回應模式       │  模糊→引導 │ 清楚→直接 │ 學習→教學
└──────────┬───────────┘
           ▼
┌──────────────────────┐
│ 3. 載入對應參考檔     │  只載入相關領域（1-2 個檔案）
└──────────┬───────────┘
           ▼
┌──────────────────────┐
│ 4. 套用 2-3 個模型    │  主要洞察 + 互補視角 + 盲點檢查
└──────────┬───────────┘
           ▼
┌──────────────────────┐
│ 5. 交叉驗證           │  反向思考 + 基本率 + 激勵分析
└──────────┬───────────┘
           ▼
   結構化建議 + 風險 + 下一步
```

## 📁 技能結構

```
model-thinking/
├── SKILL.md                        # AI 指令入口（工作流 + 模板 + 路由表）
└── references/
    ├── decisions.md                # 決策模型（25 個）
    ├── systems.md                  # 系統模型（24 個）
    ├── statistics.md               # 統計模型
    ├── strategy.md                 # 策略模型
    ├── psychology.md               # 心理模型（27 個）
    ├── networks.md                 # 網路模型
    ├── algorithms.md               # 演算法模型
    ├── risk.md                     # 風險模型
    ├── learning.md                 # 學習模型
    ├── economics.md                # 經濟模型
    └── combinations.md             # 跨領域組合策略（5 個情境範例）
```

## 🤝 相容的 AI Agent

| Agent | 安裝方式 |
|-------|---------|
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | `npx skills add kcchien/model-thinking` |
| 其他相容 Agent | 任何能讀取 `SKILL.md` 作為指令的 AI Agent |

> Model Thinking 遵循開放的 `SKILL.md` 慣例。任何能發現並載入 `SKILL.md` 的 AI Agent 都能使用。

## 📋 前置條件

- 支援 Agent Skills 的 AI 編碼助手（例如 [Claude Code](https://docs.anthropic.com/en/docs/claude-code)）
- **零額外依賴** — 不需要 Python、不需要 API key、不需要安裝任何套件

## 📄 授權

[MIT](LICENSE)

---

<div align="center">

<img src="assets/cover.svg" alt="Model Thinking — Mental Models Toolkit" width="100%"/>

# Model Thinking

**200+ mental models in your AI assistant. Think wider, decide better.**

<br/>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Agent Skill](https://img.shields.io/badge/Agent_Skill-Compatible-blueviolet?style=flat-square)](#-compatible-agents)
[![Domains](https://img.shields.io/badge/Domains-10-34d399?style=flat-square)](#-ten-knowledge-domains)
[![Models](https://img.shields.io/badge/Models-200+-60a5fa?style=flat-square)](#-ten-knowledge-domains)
[![Zero Dependencies](https://img.shields.io/badge/Zero_Deps-Install_and_Go-f59e0b?style=flat-square)](#-requirements)

An AI-native thinking toolkit that equips your assistant with 200+ mental models<br/>
across 10 domains — with cross-domain synthesis for real-world problems.

[Quick Install](#-quick-install-1) · [Usage](#-what-can-you-do-with-it) · [Domains](#-ten-knowledge-domains) · [How It Works](#️-how-it-works-1)

</div>

---

When you face a complex decision, how many angles do you consider?

Most people rely on one or two familiar perspectives. The result: blind spots, circular thinking, or analysis paralysis.

**Model Thinking** turns your AI assistant into a thinking partner armed with 200+ mental models. It doesn't hand you a reading list — it selects 2-3 models that fit your specific problem, cross-references them across domains, and surfaces the angles you'd miss on your own.

## ⚡ Quick Install

```bash
npx skills add kcchien/model-thinking
```

That's it. Your AI agent will automatically activate when you ask it to analyze problems, make decisions, or learn about mental models.

## 💬 What Can You Do With It?

Just talk to your AI assistant naturally:

| You say | What happens |
|---------|-------------|
| *"Help me think through this job offer"* | Cross-analyzes with Regret Minimization, Opportunity Cost, Reversibility |
| *"Why does this system keep getting worse?"* | Diagnoses root cause with system archetypes (Shifting the Burden) |
| *"Should we enter the Southeast Asian market first?"* | Triangulates with Game Theory, Network Effects, Fat Tail Risk |
| *"Teach me second-order thinking"* | Teaching mode: concept → example → common mistake → practice prompt |
| *"Apply inversion to this business plan"* | Directly applies the specified model |
| *"Help me assess the risks"* | Guided mode: diagnostic questions first, then model selection |

### Three Modes, Auto-Selected

| Mode | Trigger | What You Get |
|------|---------|-------------|
| **Guided** | Ambiguous or complex problem | 2-3 diagnostic questions → model recommendations → structured analysis |
| **Direct** | Clear problem or specific model requested | Immediate 2-3 model application with cross-validation |
| **Teaching** | Wants to learn a model | One-liner → concrete example → common pitfall → practice prompt |

You don't need to know which model to use — describe your problem, and the AI selects automatically.

## 🧠 Ten Knowledge Domains

Not just a model catalog, but an organized **thinking toolkit**. Each domain is a separate reference file, loaded on demand to preserve your context window.

| Domain | Topics | Representative Models |
|--------|--------|----------------------|
| **Decisions** | Choice, judgment, cognitive tools | Inversion, Second-Order Thinking, Pre-Mortem, Six Thinking Hats |
| **Systems** | Feedback loops, emergence, intervention | Stocks & Flows, Leverage Points, Limits to Growth, Shifting the Burden |
| **Statistics** | Probability, inference, fallacies | Bayesian Thinking, Regression to Mean, Survivorship Bias, Simpson's Paradox |
| **Strategy** | Game theory, competition, negotiation | Nash Equilibrium, Prisoner's Dilemma, BATNA, Moats |
| **Psychology** | Biases, social psychology, motivation | Confirmation Bias, Loss Aversion, Social Proof, Dunning-Kruger |
| **Networks** | Connections, influence, platforms | Network Effects, Metcalfe's Law, Small Worlds, Weak Ties |
| **Algorithms** | Computational thinking, search, sorting | Explore/Exploit, Simulated Annealing, Greedy, Caching |
| **Risk** | Uncertainty, fragility, black swans | Fat Tails, Antifragile, Margin of Safety, Barbell Strategy |
| **Learning** | Knowledge acquisition, skill building | Spaced Repetition, Deliberate Practice, Feynman Technique, Circle of Competence |
| **Economics** | Markets, incentives, resource allocation | Opportunity Cost, Supply & Demand, Comparative Advantage, Tragedy of the Commons |

### Cross-Domain Synthesis — Where the Real Power Lives

A single model reveals one dimension. **Model Thinking**'s core value is cross-domain combination:

- **Models agree** → High confidence in the conclusion
- **Models disagree** → Hidden complexity worth exploring before deciding
- Each model's blind spot is covered by another's strength

The skill includes a dedicated `combinations.md` reference with battle-tested pairing strategies and five detailed scenario walkthroughs.

## ⚙️ How It Works

**Progressive disclosure architecture** — the AI doesn't load all models at once, but pulls them on demand:

| Stage | What Loads | Context Cost |
|-------|-----------|-------------|
| Standby | Skill name + trigger description | ~100 words |
| Activation | SKILL.md core workflow | ~800 words |
| Analysis | Relevant domain reference files (1-2) | ~3,000 words/file |
| Synthesis | combinations.md (on demand) | ~2,000 words |

Your context window stays clean. The AI only reads what it needs.

## 📁 Skill Structure

```
model-thinking/
├── SKILL.md                        # Agent instructions (workflow + templates + routing)
└── references/
    ├── decisions.md                # Decision models (25)
    ├── systems.md                  # Systems models (24)
    ├── statistics.md               # Statistics models
    ├── strategy.md                 # Strategy models
    ├── psychology.md               # Psychology models (27)
    ├── networks.md                 # Network models
    ├── algorithms.md               # Algorithm models
    ├── risk.md                     # Risk models
    ├── learning.md                 # Learning models
    ├── economics.md                # Economics models
    └── combinations.md             # Cross-domain combination strategies (5 scenarios)
```

## 🤝 Compatible Agents

| Agent | Install Method |
|-------|---------------|
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | `npx skills add kcchien/model-thinking` |
| Other compatible agents | Any agent that reads `SKILL.md` as instructions |

> Model Thinking follows the open `SKILL.md` convention. Any AI agent that can discover and load `SKILL.md` files will work.

## 📋 Requirements

- An AI coding assistant that supports Agent Skills (e.g., [Claude Code](https://docs.anthropic.com/en/docs/claude-code))
- **Zero additional dependencies** — no Python, no API keys, no packages to install

## 📄 License

[MIT](LICENSE)
