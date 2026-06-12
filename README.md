# 弥雅脱口秀 2️⃣ Skill

这个 Skill 用于让 Codex 或其他 AI 助手稳定生成「弥雅脱口秀 2️⃣」的短视频剧本提示词。

## 用途

- 生成 15 秒弥雅脱口秀完整剧本
- 生成即梦 / Seedance 可用的视频提示词
- 保持弥雅角色、舞台、镜头、分镜格式稳定
- 避免字幕、人物变矮、腿短、全景、乱运镜、AI 主播感

## 文件说明

- `SKILL.md`：核心规则，给 Codex 读取
- `templates/miya-standup-template.md`：固定剧本结构
- `examples/input-example.md`：输入示例
- `examples/output-example.md`：输出示例

## 使用方式

把本文件夹放入 Codex 可读取的项目目录中。

在需求中说明：

```txt
请使用 miya-standup-skill，基于以下台词生成弥雅脱口秀 2️⃣ 完整剧本。
```

然后提供台词即可。

## 注意

不要把用户的人物参考图、声音文件、私密素材上传到公开仓库。公开仓库只保留文字规则、模板和示例。
