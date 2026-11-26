# PIXdesign

PIXdesign 是一个 Codex 技能，用于设计夸张长颈、细长腿和大头小身的现代都市 3D 人偶。它通过内置的 imagegen 工具，结合角色参考图与风格提示词，生成黏土皮肤、针织和毛呢质感的原创角色。

## 安装与使用

1. 下载完整仓库，把目录命名为 `pixdesign`，放入 `~/.codex/skills/`。如设置了 `CODEX_HOME`，放入 `$CODEX_HOME/skills/`。
2. 在可使用内置 imagegen 的 Codex 聊天中调用 `$pixdesign`，描述新角色的职业、动作和场景。

> 使用 `$pixdesign`，设计一个在办公室敲键盘的程序员，坐姿、单人、竖幅全身构图。

## 文件

- [`SKILL.md`](SKILL.md) 提供参考图选择、生成和视觉验收流程。
- [`agents/openai.yaml`](agents/openai.yaml) 提供技能显示名称和默认调用提示。
- [`references/`](references) 内含 7 张角色参考图、人物风格提示词和比例验收说明。安装时请保留目录结构。
