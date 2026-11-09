# ad-shot-script-planner

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=for-the-badge)
![Storyboard](https://img.shields.io/badge/Ad-Shot%20Script-22c55e?style=for-the-badge)

把广告需求整理成分镜脚本或视频生成提示词的 Codex skill。目前支持电影化分镜脚本、技术拆解分镜脚本、时间戳视频提示词三种格式；默认提供前两版，指定时间戳格式时只输出该格式。

## What It Does

- 输出商业广告脚本、镜头描述、转场方式和画面节奏
- 支持短视频广告、TVC、产品卖点片、AI 视频脚本
- 适合需要“导演感”和“可执行镜头语言”的项目
- 电影化分镜脚本：先写风格、氛围和产品调性，再逐镜描述画面与转场衔接
- 技术拆解分镜脚本：逐镜列出时长、画面、叙事、景别、角度、运镜、景深、光线、音乐与转场
- 时间戳视频提示词：整片要求 → 时间段画面描述 → 全局运镜、剪辑、视觉、音效配乐与一致性约束
- 支持只写画面的要求；时间戳格式采用自然段，一个时间段可以包含多个连贯镜头

## Timestamp Video Prompt

可以这样调用：

```text
请用 $ad-shot-script-planner，按时间戳提示词格式写一版产品广告：
30秒，16:9横版，具体产品、卖点和素材见附件。
先写整体要求，再按“0-5秒：”这样的时间段描述画面，
最后统一补充运镜、剪辑、视觉风格、音效配乐与一致性要求。
```

时长、画幅、时间段数量和各段长度按项目调整，不固定为 30 秒或每段 5 秒。若只要画面，可省略声音设计与配乐。格式模板和完整原例见[时间戳视频提示词格式](skills/ad-shot-script-planner/references/timestamp-video-prompt-format.md)；原例的追车剧情与限制仅用于示范。

## Install

复制下面这段到任意电脑的 Codex 中安装：

```text
请用 $skill-installer 安装这个 skill：
https://github.com/zhangjyaa-ctr/codex-skill-ad-shot-script-planner/tree/main/skills/ad-shot-script-planner
```

安装后通常下一轮对话即可使用。

