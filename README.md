# ad-shot-script-planner

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=for-the-badge)
![Storyboard](https://img.shields.io/badge/Ad-Shot%20Script-22c55e?style=for-the-badge)

把广告需求整理成结构化分镜脚本的 Codex skill。默认提供电影化、技术拆解两版脚本，也支持按指定的「连续画面脚本」格式输出。

## What It Does

- 输出商业广告脚本、镜头描述、转场方式和画面节奏
- 支持短视频广告、TVC、产品卖点片、AI 视频脚本
- 适合需要“导演感”和“可执行镜头语言”的项目
- 连续画面脚本：片头标明时长、画幅和镜头数，每镜按「镜头标题 → 时间段 → 连续画面描述」展开，动作、运镜与转场融入正文
- 支持纯画面版本，省去字幕、旁白、音乐及分栏式技术字段

## Continuous Visual Script

可以这样调用：

```text
请用 $ad-shot-script-planner，按连续画面脚本格式写一版：
15秒，16:9横版，7个镜头，只写画面。
每镜写标题、时间段和自然段描述，把运镜、动作与转场融入正文。
```

时长、画幅和镜头数按项目调整。指定此格式时只输出这一版，原有两版格式仍可使用。完整示例见[连续画面脚本示例](skills/ad-shot-script-planner/references/continuous-visual-script-example.md)。

## Install

复制下面这段到任意电脑的 Codex 中安装：

```text
请用 $skill-installer 安装这个 skill：
https://github.com/zhangjyaa-ctr/codex-skill-ad-shot-script-planner/tree/main/skills/ad-shot-script-planner
```

安装后通常下一轮对话即可使用。

