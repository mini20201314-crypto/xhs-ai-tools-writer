# xhs-ai-tools-writer

[![skills.sh](https://skills.sh/b/mini20201314-crypto/xhs-ai-tools-writer)](https://skills.sh/mini20201314-crypto/xhs-ai-tools-writer)

小红书 **AI 工具向** 编稿 Skill（真实测评 + 场景干货）。

适用于 OpenCode / Claude Code / Cursor 等支持 Agent Skills 的工具。

## 垂直方向

- 受众：想用 AI 提效的职场人 / 开发者 / 自媒体 / 学生
- 内容：ChatGPT、Claude、Cursor、效率插件等测评与干货
- 不做：美妆万能模板、编造数据、自动发帖

## 安装

```bash
npx skills add mini20201314-crypto/xhs-ai-tools-writer --skill xhs-ai-tools-writer
```

或把本仓库 `skills/` 路径加入 OpenCode：

```json
{
  "skills": {
    "paths": ["./skills"]
  }
}
```

## 触发词

小红书、xhs、编稿、笔记、AI 工具测评、Cursor、ChatGPT 种草、科技干货

## 目录

```
skills/xhs-ai-tools-writer/   # 成品 skill
  SKILL.md
  refs/                       # 标题公式 / 质检 / 黑名单 / 人设
AUTHORS.md                    # 开源作者矩阵（上游来源）
sources/                      # 精华摘录说明
composed/                     # 融合决策记录
```

## 使用前

1. 编辑 `skills/xhs-ai-tools-writer/refs/persona.md` 填入你的账号人设
2. 对 Agent 说：`用 xhs-ai-tools-writer 写一篇 Cursor 测评`

## 合成自（精华）

| 上游 | 吸收 |
|------|------|
| dbs-xhs-title | 标题公式匹配 |
| write-xiaohongshu | 字数硬限、结构化交付 |
| xhs-note-creator | 短段、轻 emoji、标签 |
| xiaohongshu-note-analyzer | 六维质检 |
| marketingskills/copywriting | 清晰、具体、用户语言 |

详见 [AUTHORS.md](./AUTHORS.md) 与 [sources/EXTRACTS.md](./sources/EXTRACTS.md)。

## License

MIT
