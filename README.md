# Hypit（一句话克隆爆款视频）

> **[hypit](https://github.com/simlpandordinary/hypit)** —— 飞书《WorkBuddy 视频系列 · 全技能与提示词总目录》里推荐的开源技能，已拆分为独立仓库分发（一个技能一个仓库）。

| 项 | 内容 |
| - | - |
| 上游仓库 | <https://github.com/hypit-ai/hypit> |
| 上游路径 | `skills/hypit` |
| 上游协议 | 见上游 LICENSE（NOASSERTION） |
| 上游 Star | 27k+ |
| 拆分方式 | 仅抽取该技能自身文件，独立可用 |

## 技能说明

Direct and produce videos with Hypit, primarily through generated media and authored components while incorporating briefs, references or supplied material; includes SVML/SVS/SVRun authoring and Runtime or credential setup.

## 目录结构

```
├── LICENSE
├── README.upstream.md
├── SKILL.md
├── references/
├── production/
├── audio-clips.md
├── authoring.md
├── browser-capture.md
├── builds.md
├── caption-authoring.md
├── caption-presentation.md
├── component-design.md
├── component-sharing.md
├── component-visuals.md
├── fonts-and-text.md
├── image-operations.md
├── index.md
├── media.md
├── prompt-kits.md
├── rendering.md
├── review.md
├── runs.md
├── script-syntax.md
├── snapshots.md
├── source-syntax.md
├── spatial.md
├── studio-companions.md
├── studio.md
├── system.md
├── timeline.md
├── timing.md
├── track-authoring.md
├── tracks.md
├── video-downloads.md
├── visual-clips.md
├── vocabulary.md
└── examples/
├── detail.svrun
├── direction.svs
├── look.svs
├── material.svrun
├── production.svml
├── production.svrun
└── visuals.ts
├── playbooks/
├── index.md
├── formats/
├── narration-led-demo.md
├── presenter-led-explainer.md
├── ranking-listicle.md
├── short-drama.md
├── street-interview.md
├── talking-head.md
└── two-person-podcast.md
└── craft/
├── b-roll.md
├── caption-tracking.md
├── captions.md
├── generated-dependencies.md
├── graphic-compositions.md
├── image-direction.md
├── motion-graphics.md
├── screen-demonstrations.md
├── sound-mix.md
├── video-direction.md
├── voice-and-performance.md
├── voice-direction.md
└── examples/
├── conversation-images.md
└── image-direction.md
├── environment/
├── distribution.md
├── local-tools.md
├── model-and-provider.md
└── profile.md
└── creation/
├── brief.md
├── project-files.md
├── reference-video.md
├── script-and-time.md
└── transformations.md
└── agents/
└── openai.yaml
```

- `SKILL.md` 是技能入口（触发条件 / 工作流 / 约束），安装时必须位于技能根目录。
- `references/`、`scripts/`、`assets/` 为该技能自带的参考文档、脚本与素材。
- `README.upstream.md` 为上游仓库原始说明，保留出处与版权信息。
- `NOTICE.md` 说明上游未声明许可，本仓库不授予任何许可。

## 安装

WorkBuddy 技能目录为 `~/.workbuddy/skills/hypit/`：

```bash
git clone https://github.com/simlpandordinary/hypit.git ~/.workbuddy/skills/hypit
```

也可以直接对 AI 说：「把 <https://github.com/simlpandordinary/hypit> 装成 Skill」。

安装后用自然语言触发，例如「Hypit（一句话克隆爆款视频）」「用 hypit 帮我处理这个任务」。

## 版权

原始作者与版权归上游仓库 `hypit-ai/hypit` 所有。本仓库仅做独立分发与结构整理，未修改技能内容；商用请遵循上游许可证。
