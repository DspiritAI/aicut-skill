## Description: <br>
地鼠AI剪辑标准 Skill helps AI agents such as Codex, QwenPaw, OpenClaw, and QwenClaw operate the 地鼠AI剪辑 desktop app through MCP, HTTP, CLI, and Bridge workflows. <br>

It defines the professional editing workflow for short-form documentary narration, including asset understanding, audio transcription, breath-point review, timeline planning, subtitles, B-roll audio handling, preview review, export validation, and human final review. <br>

This public Skill is intended as the AI-facing protocol and workflow package. The 地鼠AI剪辑 desktop product, brand assets, backend services, and private API keys are not included in this Skill package. <br>

## Publisher: <br>
地鼠精灵 / Dishu AI <br>

## Contact: <br>
企业 AI 转型方案、地鼠AI剪辑合作和技术接入，可扫码添加地鼠微信：<br>
[微信二维码](https://raw.githubusercontent.com/DspiritAI/aicut-skill/main/assets/contact-wechat.jpg) <br>

### License/Terms of Use: <br>
Public Skill instructions for AI-agent interoperability. Product code, trademarks, customer materials, and private credentials remain reserved by their respective owners. <br>

## Use Case: <br>
AI agents use this Skill when a user asks for AI video editing, automatic rough cut, narration-first short-video editing, Douyin/TikTok documentary editing, asset analysis, subtitle timing, B-roll selection, export validation, or deep integration with 地鼠AI剪辑. <br>

### Deployment Geography for Use: <br>
China and global AI-agent workflows where local desktop editing plus optional cloud vision services are allowed. <br>

## Known Risks and Mitigations: <br>
Risk: An AI agent may generate captions or story facts that are not present in the source media. <br>
Mitigation: Captions must come from transcript segments or user-confirmed scripts; unverified AI planning text must not become final subtitles. <br>
Risk: Customer privacy, contracts, backend screens, contact information, vehicle plates, or chat records may appear in local footage. <br>
Mitigation: Require human confirmation before using sensitive frames, and avoid uploading or publishing customer-private material without approval. <br>
Risk: Cloud vision/video models may require public URLs or temporary tunnels for frame/video access. <br>
Mitigation: Use short-lived URLs, environment variables for credentials, and explicit user approval before exposing local media. <br>
Risk: Automatic editing may produce an export with missing audio, loud B-roll, wrong subtitles, black frames, or poor pacing. <br>
Mitigation: Run export validation, audio checks, preview-frame review, and human final review before delivery or publishing. <br>

## Reference(s): <br>
- [地鼠AI剪辑 standard Skill](SKILL.md) <br>
- [Editing examples](examples.md) <br>
- [Detailed reference](reference.md) <br>
- [Documentary editing JSON template](dishu-douyin-documentary.skill.json) <br>
- [Contact QR code](https://raw.githubusercontent.com/DspiritAI/aicut-skill/main/assets/contact-wechat.jpg) <br>

## Skill Output: <br>
**Output Type(s):** [markdown, json, shell commands, MCP calls, HTTP calls, timeline plans, review reports] <br>
**Output Format:** [Actionable editing workflow, AICut CLI/MCP/HTTP instructions, timeline/review JSON, concise human-facing delivery notes] <br>
**Output Parameters:** [local media paths, AICut HTTP URL, MCP port, project id, export path, optional cloud vision configuration] <br>
**Other Properties Related to Output:** [Never include private API keys in the Skill, frontend code, logs, or published package.] <br>

## Skill Version(s): <br>
1.0.0 <br>

## Ethical Considerations: <br>
Users and agents should respect privacy, copyright, customer confidentiality, platform rules, and local laws. This Skill should assist professional editing and review, not automatically publish videos or fabricate unverifiable business results. <br>
