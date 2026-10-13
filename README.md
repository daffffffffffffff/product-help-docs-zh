# product-help-docs-zh

写作和修订中文产品对外使用文档（帮助中心、使用说明、FAQ、更新说明）的 Skill。

## 流程

1. 收集上下文：5 个元问题 + 5～10 个追问
2. 按读者需求选文档类型（快速上手 / 操作指南 / 参考 / 概念解释，另含 FAQ、更新说明模板）
3. 起草（长文逐节写）
4. 读者测试（子代理或新对话，只依据文档回答）
5. 统一中文排版
6. 去 AI 腔、营销腔
7. 交付：文档 + 待确认清单 + 推断项

核心原则：只用用户提供的产品事实，缺口标【待确认】，不编造。

## 文件

- `SKILL.md`：主流程
- `references/doc-types.md`：文档类型与模板
- `references/style-guide.md`：中文排版规范（已统一常见分歧）
- `references/humanize-patterns.md`：去 AI 腔检查模式
- `references/reader-test.md`：读者测试提示词模板

## 许可

本项目按 MIT License 发布，详见 [LICENSE](LICENSE)。

## 来源与致谢

本 Skill 用自己的话改写并合并了以下项目的流程和规则，未复制原文：

- [anthropics/skills](https://github.com/anthropics/skills) 中的 doc-coauthoring：上下文收集、逐节写作、读者测试
- [FunnyWolf/document-style-guide-skill](https://github.com/FunnyWolf/document-style-guide-skill) 中的 zh-review：中文排版规则
- [op7418/Humanizer-zh](https://github.com/op7418/Humanizer-zh)（MIT）：去 AI 腔模式
- [Diátaxis](https://diataxis.fr/) 文档框架：文档类型划分
