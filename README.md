# 口播封面 Skill

根据人物照片和口播主题制作同主题双画幅封面：横版 4:3、竖版 3:4。强调明显夸张的自然面部表情、可读的手写艺术字和纯色或少色背景，支持同一人物不同画风与状态的半脸拼接。

## 特点

- 每组两张独立成图，按横竖空间重新排版。
- 18 类表情与 30 套男性服装描述，用户本次要求优先。
- 文字与头发、帽子或衣服形成前后层次，保护眼睛、嘴和重要手势。
- 双脸模式保持同一人物可辨、两侧风格与情绪不同、接缝可见。

## 安装与使用

```bash
git clone https://github.com/yesterising/koubo-cover.git "${CODEX_HOME:-$HOME/.codex}/skills/koubo-cover"
```

安装后让宿主重新加载技能目录，提供本人照片和主题，例如：

> 用这张照片为“AI 帮我剪口播”制作口播封面，文字夸张但清楚，横版和竖版各一张。

> 做两个半脸拼接：左边惊讶的摄影质感，右边得意的手绘海报质感，仍然是我本人。

需要支持参考图编辑的 imagegen 或同等图像生成能力，用户提供可用于该任务的人物照片。此仓库是提示词与设计流程，不包含模型、生成服务或 API Key。默认目标为横版 1600×1200、竖版 1200×1600；实际输出尺寸取决于工具，交付时报告实际值。

## 公开范围与来源

本版本由 yesterising 维护，保留本地定制的设计与交付规则。公开版不包含作者的肖像、第三方封面截图或图像生成凭据。人物由每位使用者自行提供，风格参考可选。设计观察的来源见 [人物与视觉规则](references/visual-rules.md)，表情与服装库属于本技能的文字制作规则。

MIT，见 [LICENSE](LICENSE)。照片、外部参考图片、字体与生成服务不由本仓库许可提供。
<img width="1448" height="1086" alt="横屏" src="https://github.com/user-attachments/assets/ff2a9628-b6a4-4762-8225-73fef22d3203" />
<img width="1448" height="1086" alt="邵艾伦孙宇晨4小时精华对谈_双脸拼接_横版A" src="https://github.com/user-attachments/assets/ecfed5c4-7d97-49e9-a160-3175fe959ec9" />
<img width="1448" height="1086" alt="ChatGPT封面_横版A" src="https://github.com/user-attachments/assets/01b79e1c-1bfa-4070-be7e-3de99f0e4074" />
<img width="1448" height="1086" alt="一键剪辑封装开源了_横版A" src="https://github.com/user-attachments/assets/1da65062-a84a-4c77-a7e8-e5c1ee3accad" />

