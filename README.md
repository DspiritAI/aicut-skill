# 地鼠AI剪辑标准 Skill

这是地鼠AI剪辑对外公开的唯一标准 AI Skill。Codex、OpenClaw、QwenPaw、QwenClaw 和其他 AI 代理读取这一套 Skill 后，可以按统一流程通过地鼠AI剪辑的 MCP、HTTP、CLI 和 Bridge 能力完成素材理解、口播剪辑、字幕、封面策略、导出验收和训练复盘。

## 安装

```bash
clawhub install aicut-editing-assistant
```

或者把本仓库作为 Skill 源安装到支持 GitHub Skill 的 AI Agent。

## 文件

- `SKILL.md`：唯一标准入口，AI 应优先读取这个文件。
- `reference.md`：详细调用和剪辑规则参考。
- `examples.md`：典型任务示例。
- `dishu-douyin-documentary.skill.json`：结构化模板和兼容校验样例，不是另一套 Skill。
- `skill-card.md`：SkillHub/ClawHub 展示说明。

## 使用前提

AI 代理要实际控制地鼠AI剪辑，需要本机已安装并运行地鼠AI剪辑 App，且 MCP/HTTP/Bridge 或 CLI 可访问。

```text
安装 Skill = AI 学会操作说明书
App 运行 + 本地接口可访问 = AI 能实际控制地鼠AI剪辑
```

## 标准原则

地鼠AI剪辑对外只维护这一套标准 Skill。旧的封面 Skill、训练 Skill 和 JSON 下载入口不再作为独立 Skill 发布。
