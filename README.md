# Polanyi Stack

Turn tacit knowledge into reusable agents and skills.

The Polanyi stack for AI agents.

把“会做但说不清”的能力，落成可复用的 agent、skill 和训练系统。

The most valuable operating systems in a company are almost never fully written down. They live in judgment, timing, escalation, taste, and refusal. That invisible layer is where quality compounds, onboarding breaks, and expert performance becomes hard to scale.

`Polanyi Stack` is an open-source system for converting tacit knowledge, Polanyi's paradox, and expert judgment into reusable AI agents, Codex skills, and training workflows. It turns Michael Polanyi's core insight, "we know more than we can tell," into operating structure: extract the hidden cues, surface the transfer boundary, and package expert behavior into software or repeatable practice.

`Polanyi Stack` 关心的是一个很具体的问题：为什么高手能稳定做对，新人和模型总差最后一步。差距通常不在信息量，落点往往在判断线索、注意力切换、升级边界和情境感。这个仓库做的事，就是把那层隐性的东西尽量拉到台面上。

[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](./LICENSE)
[![Star History Chart](https://api.star-history.com/svg?repos=11Yuxuanyang/polanyi-stack&type=Date)](https://www.star-history.com/#11Yuxuanyang/polanyi-stack&Date)

Documentation site:

- https://11yuxuanyang.github.io/polanyi-stack/

## Why This Exists

Most teams do not lose leverage because they lack information. They lose leverage because their best judgment is trapped inside a few people.

- Your best operator leaves, and your margin leaves with them.
- Your onboarding looks complete, but new hires still cannot perform.
- Your AI agent can automate syntax, but not judgment.
- Your team can repeat the words, but not reproduce the outcome.

Tacit knowledge is the hidden layer behind all of that. If you can extract it, you can scale it. If you can package it, you can productize it.

中文直白版：

- 多数团队真正卡住的地方，在于最值钱的判断只活在少数人脑子里。
- 文档能复制流程，复制不了火候、边界感和取舍。
- AI 能处理显性规则，但真正拉开差距的，往往是 tacit knowledge。
- 谁先把默会知识提炼成 agent 和 skill，谁就先把人的能力变成组织资产。

## Why Polanyi's Paradox Matters for AI Skill Learning

Polanyi 悖论把 AI 技能学习里最难的一层点了出来。人会的东西，很多并不以规则、条款、步骤的形式存在。它们藏在手感、时机、场景判断、例外处理和边界感里。自动化系统想稳定复现高手表现，迟早都会撞上这堵墙。

这也是 AI skill 设计最值得盯住的地方。Skill 文件能承载目标、触发条件、流程、约束和输出格式。真正拉开差距的那部分，常常还在案例、演示、反馈和反复试错里。文档能写到哪，训练要接到哪，这条边界基本就是 Polanyi 边界。

如果你要继续往下读，这里有一篇更完整的解释：

- [Why Polanyi's paradox matters for AI skill learning](./docs/polanyis-paradox-ai-skill-learning.html)

## What Tacit Knowledge Means Here

Tacit knowledge is knowledge embedded in expert judgment, timing, pattern recognition, escalation sense, and embodied action. People use it constantly, but they often cannot fully explain it in explicit step-by-step language.

This matters because documentation can copy sequence, but it usually cannot copy feel, boundary sense, or the ability to notice the right signal at the right time. That hidden layer is exactly what strong AI agents, strong training systems, and strong onboarding workflows need.

Further reading:

- [What is tacit knowledge?](./docs/what-is-tacit-knowledge.html)
- [Michael Polanyi for AI builders](./docs/michael-polanyi-ai.html)

## How This Becomes an AI Agent

To turn tacit knowledge into an AI agent, do not start with broad expertise. Start with one role, one recurring task, one high-value scene, and one boundary where the system must stop and escalate. Then extract cues, trigger phrases, failure signatures, and default moves from real expert performance.

Once that hidden layer is visible, you can package it into a reusable AI agent, Codex skill, copilot, or onboarding workflow. If you skip the extraction step, you usually end up with a polished but shallow prompt.

Further reading:

- [How to turn tacit knowledge into an AI agent](./docs/tacit-knowledge-to-ai-agent.html)
- [How to convert expert judgment into a Codex skill](./docs/expert-judgment-to-codex-skill.html)

## What You Can Build With It

This repo gives you a fixed set of skills for turning invisible expertise into reusable assets.

| Skill | What it does |
|------|---------------|
| `convert-tacit-to-skill` | Converts a narrow expert workflow into a reusable agent or Codex skill |
| `extract-tacit-knowledge` | Pulls hidden cues, trigger signals, failure signatures, and escalation boundaries out of expert performance |
| `design-embodied-learning` | Designs practice ladders for tacit or judgment-heavy skills |
| `map-personal-knowledge` | Separates direct understanding from borrowed language and weak assumptions |
| `design-apprenticeship-transfer` | Builds mentor-led transfer and onboarding for tacit work |
| `train-attention-switching` | Trains focal and subsidiary attention switching for diagnosis, debugging, review, and other expert work |

## Where It Gets Commercial

This is not just a philosophy repo. It is a commercialization layer for expertise.

Use it to:

- turn a founder's judgment into a repeatable copilot
- turn a senior engineer's review instinct into a reusable skill
- turn sales, diagnosis, or content taste into a teachable system
- reduce onboarding time for judgment-heavy roles
- build agents that know when to act and when to escalate

The open-source core is the framework. The commercial upside is what you build on top of it.

中文商业化理解：

- 把创始人的判断变成固定 copilot
- 把资深员工的经验变成 onboarding 系统
- 把高质量服务背后的“感觉”变成可交付产品
- 把原本只能靠少数高手完成的工作，变成可训练、可复制、可放大的能力

## Where This Helps

- Tacit knowledge for code review
- Tacit knowledge for onboarding judgment-heavy roles
- Tacit knowledge for debugging and diagnosis
- Tacit knowledge for design critique and creative review
- Tacit knowledge for founder judgment and specialized copilots

Use case page:

- [Tacit knowledge examples](./docs/tacit-knowledge-examples.html)

## Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/11Yuxuanyang/polanyi-stack.git
cd polanyi-stack
```

### 2. Install the skills into Codex

If your Codex setup reads from `~/.codex/skills`, symlink the skill folders you want to use:

```bash
ln -s "$(pwd)/skills/convert-tacit-to-skill" ~/.codex/skills/convert-tacit-to-skill
ln -s "$(pwd)/skills/extract-tacit-knowledge" ~/.codex/skills/extract-tacit-knowledge
ln -s "$(pwd)/skills/design-embodied-learning" ~/.codex/skills/design-embodied-learning
ln -s "$(pwd)/skills/map-personal-knowledge" ~/.codex/skills/map-personal-knowledge
ln -s "$(pwd)/skills/design-apprenticeship-transfer" ~/.codex/skills/design-apprenticeship-transfer
ln -s "$(pwd)/skills/train-attention-switching" ~/.codex/skills/train-attention-switching
```

### 3. Start from the orchestrator

The main entry point is:

- [`skills/convert-tacit-to-skill/SKILL.md`](./skills/convert-tacit-to-skill/SKILL.md)

Use it when you want to turn one narrow type of expert judgment into a reusable agent or skill.

Example prompts:

```text
Use convert-tacit-to-skill to turn my code review judgment into a reusable Codex skill.
```

```text
Help me convert the way I evaluate short-video hooks into a fixed agent with escalation boundaries.
```

```text
Use the tacit skills to extract the hidden cues behind our best sales call diagnosis.
```

Chinese examples:

```text
用 convert-tacit-to-skill 帮我把代码 review 的 tacit knowledge 做成一个可复用的 Codex skill。
```

```text
帮我把我判断短视频开头好坏的经验，转成一个固定 agent，并定义清楚升级边界。
```

## What Lives In The Repository

```text
docs/
├── index.html
├── polanyis-paradox-ai-skill-learning.html
├── what-is-tacit-knowledge.html
├── tacit-knowledge-to-ai-agent.html
├── expert-judgment-to-codex-skill.html
├── michael-polanyi-ai.html
└── tacit-knowledge-examples.html

skills/
├── convert-tacit-to-skill/
├── extract-tacit-knowledge/
├── design-embodied-learning/
├── map-personal-knowledge/
├── design-apprenticeship-transfer/
└── train-attention-switching/
```

Each skill contains:

- `SKILL.md`: the trigger and operating instructions
- `references/`: the minimum templates needed to run the workflow

## Design Principle

Do not try to automate "expertise" in the abstract.

Start with:

- one role
- one task
- one high-value scene
- one boundary where the system must stop and escalate

That is how tacit knowledge becomes durable instead of vague.

## Topics This Repository Covers

This repository is written to be found through real questions, not only through the project name.

Core keyword clusters:

- tacit knowledge
- Polanyi's paradox
- Michael Polanyi
- expert judgment
- AI agents
- Codex skills
- knowledge transfer
- onboarding
- diagnosis
- code review

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=11Yuxuanyang/polanyi-stack&type=Date)](https://www.star-history.com/#11Yuxuanyang/polanyi-stack&Date)

## License

MIT. See [LICENSE](./LICENSE).
