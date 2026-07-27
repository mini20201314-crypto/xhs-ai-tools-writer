# 开源作者矩阵 · 小红书编稿

> 信任级：high / med / low  
> 用途：title=标题 · write=正文 · qc=质检 · auto=自动化发布 · copy=转化文案

| 作者/仓库 | Skill | Installs | 用途 | 信任 | 吸取 | 丢弃 | 本地摘录 |
|-----------|-------|----------|------|------|------|------|----------|
| dontbesilent2025/dbskill | dbs-xhs-title | 15.2K | title | high | 75公式→12触发器匹配、≤20字、悬念铁律 | 全量75条硬塞进主skill；夸大变现承诺模板滥用 | sources/dbs-xhs-title |
| zhjiang22/openclaw-xhs | xiaohongshu | 11.1K | auto | low* | 搜索/分析流程概念 | MCP登录态、自动发帖、安全审计Fail | 不落地依赖 |
| adjfks/corner-skills | write-xiaohongshu | 4.4K | write | med | 先研究再写；标题≤20/正文≤1000；结构化交付 | 强依赖MCP发布；配图硬规则过死 | sources/write-xiaohongshu |
| softbread/xiaohongshu-doctor | note-analyzer | 2.9K | qc | med | 关键词/风险/商业感/互动/结构 六维质检 | 无垂直行业词库时泛泛而谈 | sources/xiaohongshu-note-analyzer |
| comeonzhj/auto-redbook-skills | xhs-note-creator | 1.1K | write | med | 短段+轻emoji；5-10标签 | 图片卡片流水线（本方向非必须） | sources/xhs-note-creator |
| redfox-data/redfox-community | xiaohongshu-rewrite | 243 | write | low | 语气改写思路 | 强制≥5 emoji；套路感重 | 仅记反面教材 |
| coreyhaines31/marketingskills | copywriting | 161K | copy | high | 清晰>花哨；利益>功能；具体>模糊；用户语言 | 网页落地页结构（非小红书） | sources/copywriting |
| freestylefly / iamzifei 等 | 封面/配图类 | 1-2K | media | med | 图文节奏意识 | 本工作流 v1 不做图 | 暂缓 |
| autoclaw-cc / jackwener | MCP/CLI | 1-3K | auto | low* | — | 账号风险、合规灰区 | 不接入 |

\* low 仅指「不作为本工作流运行时依赖」，非否定作者。

## 本工作流成品

| 成品 Skill | 方向 | 合成自 |
|------------|------|--------|
| `xhs-ai-tools-writer` | AI 工具真实测评 + 场景干货 | 上表 title+write+qc+copy 精华 |

## 冲突优先级

```
账号人设 persona.md
  > 垂直方向规则（AI工具/科技）
    > 本 skill 硬规则
      > 标题公式库
        > 上游通用小红书模板
```
