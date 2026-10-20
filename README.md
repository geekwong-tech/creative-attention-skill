# Creative Attention Skill

一个以中文为主、工具无关的 Agent Skill：从广告、封面和视觉参考中提炼出奇机制与可复用辅助方法。重点是“具体做了什么、关系为何成立、换素材保留什么”，并区分观察、解释和目标品牌事实。

## 安装

克隆本仓库后，将 `extracting-creative-mechanisms` 文件夹复制到你的技能目录，例如 Codex 的 `~/.codex/skills/`。目录结果应为 `~/.codex/skills/extracting-creative-mechanisms/SKILL.md`。如已存在同名技能，先比较并备份，避免覆盖个人修改。按所用 Agent 的方式刷新技能列表或开始新会话。

其他支持 `SKILL.md` 的 Agent 可放入其技能发现目录；具体加载方式以所用工具为准。无需依赖安装、API key、数据库或特定图像服务。

## 使用

```text
使用 $extracting-creative-mechanisms 分析我提供的海报，
保存观察，再提炼独立创意方法与可选配方。
先给简明结论，把证据与边界放到折叠详情。
```

已有保存分析时：

```text
使用 $extracting-creative-mechanisms，依据以下保存分析提炼，别重复读图。
观察 v1：一张露营灯海报，灯光锥被画成展开的书页；
文字“把夜晚翻到下一页”；底部有常规规格表。
请分开本例解释与通用方法，另给向音乐教学迁移的草案。
不要入库，品牌能力都待核实。
```

完整流程可在单次请求中完成：观察/案例解释 → 从保存分析抽象 → 自检 → 简明交付。只有缺关键观察才回到第一阶段。入库、发布等外部修改仍依当次用户授权和实际工具执行；生成草稿不代表已保存。

## 内容

- [技能入口](extracting-creative-mechanisms/SKILL.md)
- [记录与质量审阅](extracting-creative-mechanisms/references/records-and-review.md)
- [合成示例与可选评估](extracting-creative-mechanisms/references/examples-and-evaluation.md)
- [一手研究与局限](extracting-creative-mechanisms/references/research.md)

主创意可以没有，辅助方法不必新奇，方法独立于可选组合配方。自检不代表独立审核；改动内容会让旧检查对新版过期。研究只提供分析视角，本技能不保证点击或转化提升。示例均为虚构教学材料，不包含客户素材或论文图文。

MIT License。许可适用于本仓库自有文字，不改变外链论文和第三方内容的权利。
