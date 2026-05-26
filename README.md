# mod-inspiration

AI-assisted-Minecraft-Developers 组织下的 **Minecraft 模组 / 玩法概念稿** 集合。

收录从机制、数据、UI 到落地方案的工程蓝图，作为后续独立仓库实现的起点。每个子目录是一个独立的设计提案，包含 `design.md`（主设计稿）以及可选的辅助资料。

---

## 索引

| 目录 | 概念 | 一句话定位 | 状态 |
|---|---|---|---|
| [spice-bazaar](./spice-bazaar/design.md) | 千味市集 · Spice Bazaar | 偶发刷新的临时维度，丝绸之路风格商队 NPC 集市，以物易物 + 自有货币"香料印记"作中转 | 概念设计稿 v0.3 |
| [lost-future](./lost-future/design.md) | 过去的未来 · Lost Future | 让各版本被移除与未实现的官方内容回归游戏中，原版风格合成 + 新作用 + 不破坏平衡 | 概念设计稿 v0.1 |

---

## 目录约定

每个设计稿目录建议遵循以下结构：

```
<concept-slug>/
├── design.md            # 主设计稿（必需）
├── assets/              # 概念图、UI mock、参考素材（可选）
└── notes/               # 调研笔记、对比表（可选）
```

`design.md` 的章节模板推荐：

1. 一句话定位
2. 设计目标 / KPI
3. 概念全景（建议用 mermaid）
4. 核心机制
5. 物品 / 数据清单
6. 与其他模组的集成
7. 实现路径（KubeJS / Datapack / 独立 mod 三阶段）
8. 平衡性与防滥用
9. 风险与待研究
10. 验收标准
11. 后续可拓展点

---

## 贡献

1. fork 或 new branch
2. 新建 `mod-inspiration/<your-concept>/design.md`
3. 在本 README 的索引表中加一行
4. 开 PR，标题用 `[<concept>] <一句话主题>`

设计稿欢迎讨论、推翻、重写，不必追求"一次成稿"。
