# cjl-autoresearch-cc

通过迭代变异测试自动改进任何 skill、prompt、文章、工作流或系统。

灵感来自 [Karpathy/autoresearch](https://github.com/karpathy/autoresearch) 和 [openclaw-autoresearch-pro](https://github.com/0xcjl/openclaw-autoresearch-pro)。

## 快速开始

```
autoresearch coding-standards
autoresearch ~/.claude/skills/my-skill
自动优化 这个prompt：[粘贴内容]
```

## 支持的模式

| 模式 | 描述 |
|------|------|
| **Skill** | 优化 SKILL.md 文件 |
| **Plugin** | 优化插件配置 |
| **Prompt** | 提升 prompt 效果 |
| **Article** | 润色文章和文档 |
| **Workflow** | 优化工作流程 |
| **System** | 改进系统设计 |

## 工作原理

1. **变异** — 每轮一个小改动
2. **测试** — 用测试用例运行
3. **评分** — 应用检查清单
4. **决策** — 分数提升则保留，否则回滚

## 触发关键词

**英文:** `autoresearch`
**中文:** `自动优化`, `自动研究`

详细文档请查看 [SKILL.md](SKILL.md)。

---

[English](README.md)
