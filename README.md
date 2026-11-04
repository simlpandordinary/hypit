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
['SKILL.md', 'agents/openai.yaml', 'references/creation/brief.md', 'references/creation/project-files.md', 'references/creation/reference-video.md', 'references/creation/script-and-time.md', 'references/creation/transformations.md', 'references/environment/distribution.md', 'references/environment/local-tools.md', 'references/environment/model-and-provider.md', 'references/environment/profile.md', 'references/playbooks/craft/b-roll.md', 'references/playbooks/craft/caption-tracking.md', 'references/playbooks/craft/captions.md', 'references/playbooks/craft/examples/conversation-images.md', 'references/playbooks/craft/examples/image-direction.md', 'references/playbooks/craft/generated-dependencies.md', 'references/playbooks/craft/graphic-compositions.md', 'references/playbooks/craft/image-direction.md', 'references/playbooks/craft/motion-graphics.md', 'references/playbooks/craft/screen-demonstrations.md', 'references/playbooks/craft/sound-mix.md', 'references/playbooks/craft/video-direction.md', 'references/playbooks/craft/voice-and-performance.md', 'references/playbooks/craft/voice-direction.md', 'references/playbooks/formats/narration-led-demo.md', 'references/playbooks/formats/presenter-led-explainer.md', 'references/playbooks/formats/ranking-listicle.md', 'references/playbooks/formats/short-drama.md', 'references/playbooks/formats/street-interview.md', 'references/playbooks/formats/talking-head.md', 'references/playbooks/formats/two-person-podcast.md', 'references/playbooks/index.md', 'references/production/audio-clips.md', 'references/production/authoring.md', 'references/production/browser-capture.md', 'references/production/builds.md', 'references/production/caption-authoring.md', 'references/production/caption-presentation.md', 'references/production/component-design.md', 'references/production/component-sharing.md', 'references/production/component-visuals.md', 'references/production/examples/detail.svrun', 'references/production/examples/direction.svs', 'references/production/examples/look.svs', 'references/production/examples/material.svrun', 'references/production/examples/production.svml', 'references/production/examples/production.svrun', 'references/production/examples/visuals.ts', 'references/production/fonts-and-text.md', 'references/production/image-operations.md', 'references/production/index.md', 'references/production/media.md', 'references/production/prompt-kits.md', 'references/production/rendering.md', 'references/production/review.md', 'references/production/runs.md', 'references/production/script-syntax.md', 'references/production/snapshots.md', 'references/production/source-syntax.md', 'references/production/spatial.md', 'references/production/studio-companions.md', 'references/production/studio.md', 'references/production/system.md', 'references/production/timeline.md', 'references/production/timing.md', 'references/production/track-authoring.md', 'references/production/tracks.md', 'references/production/video-downloads.md', 'references/production/visual-clips.md', 'references/production/vocabulary.md', 'LICENSE', 'README.upstream.md']
```

- `SKILL.md` 是技能入口（触发条件 / 工作流 / 约束），安装时必须位于技能根目录。
- `references/`、`scripts/`、`assets/` 为该技能自带的参考文档、脚本与素材。
- `README.upstream.md` 为上游仓库原始说明，保留出处与版权信息。
- `LICENSE` 为上游许可证原文。

## 安装

WorkBuddy 技能目录为 `~/.workbuddy/skills/hypit/`：

```bash
git clone https://github.com/simlpandordinary/hypit.git ~/.workbuddy/skills/hypit
```

也可以直接对 AI 说：「把 <https://github.com/simlpandordinary/hypit> 装成 Skill」。

安装后用自然语言触发，例如「Hypit（一句话克隆爆款视频）」「用 hypit 帮我处理这个任务」。



## 版权

原始作者与版权归上游仓库 `hypit-ai/hypit` 所有。本仓库仅做独立分发与结构整理，未修改技能内容；商用请遵循上游许可证。
