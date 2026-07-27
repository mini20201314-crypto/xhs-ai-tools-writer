# 上游精华摘录（浓缩版）

完整上游请用：`npx skills add <owner/repo> --skill <name>`  
此处只保留合成本 skill 时用到的要点，避免 Agent 被全量噪声带偏。

---

## 1. dbs-xhs-title（15.2K）— 标题

**精华**

- 角色是「公式匹配器」不是自由生成器  
- 12 类心理触发器  
- 每个标题可追溯公式  
- 标题 ≤20 字；留悬念；张力 ≥2  

**糟粕/未照搬**

- 75 条全塞进主 skill 太重 → 只抽 AI 向子集到 `title-formulas.md`  
- 变现/鸡血类举例过多 → 替换为工具场景举例  

---

## 2. write-xiaohongshu（4.4K）— 流程

**精华**

- 先研究再写再（可选）发  
- 标题 ≤20、正文 ≤1000  
- 固定交付：标题/正文/标签/配图说明  

**糟粕/未照搬**

- 强依赖发布 MCP  
- 配图强制规则过死（本方向 v1 只给文案层建议）  

---

## 3. xhs-note-creator（1.1K）— 正文形态

**精华**

- 短句短段  
- emoji 点缀而非主体  
- 文末 5–10 SEO 标签  

**糟粕/未照搬**

- 图片卡片生成流水线（非本工作流核心）  

---

## 4. xiaohongshu-note-analyzer（2.9K）— 质检

**精华**

六维：关键词、标题钩子、敏感风险、商业化、互动、结构  

**改造**

- 落到 `qc-checklist.md`，并加上 AI 工具场景细则  

---

## 5. copywriting（marketingskills）— 语言

**精华**

- Clarity over cleverness  
- Benefits over features  
- Specificity over vagueness  
- Customer language  

**糟粕/未照搬**

- 网页落地页大结构（Hero/Pricing）不适用于小红书  

---

## 6. xiaohongshu-rewrite 等 — 反面教材

- 「至少 5 个不重复 emoji」→ 明确禁止  
- 无研究直接改写腔调 → 必须先有事实素材  

---

## 7. openclaw-xhs / 各类 MCP 发布

- 安装量高但安全审计不稳、账号风险大  
- **本工作流不接入运行时依赖**；仅保留「人审后自贴」原则  
