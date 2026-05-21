<p align="center">
  <h1 align="center">student-skill</h1>
  <p align="center"><i>Claude Code skill for students — learn with AI, not just from AI</i></p>
  <p align="center">
    <a href="https://github.com/zxcmnv520/student-skill/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/license-MIT-blue" alt="MIT License">
    </a>
    <a href="https://claude.ai/code">
      <img src="https://img.shields.io/badge/Claude%20Code-skill-8A2BE2" alt="Claude Code Skill">
    </a>
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen" alt="PRs Welcome">
  </p>
</p>

---

A **[Claude Code](https://claude.ai/code)** skill designed for **students**. Load it with `/student` and get a learning-first coding assistant that helps you understand *why* before *how*.

适用于课程项目、实验报告、竞赛、毕业设计等场景。帮助学生更高效地与 AI 协作学习。

---

## Features

| | Feature | Description |
|---|---------|-------------|
| 🎓 | **Learning-first** | Understand principles, not just get answers |
| 📝 | **Study journaling** | Auto-document your progress and key takeaways |
| 🎯 | **Scenario-aware** | Adapts to homework, labs, competitions, thesis, self-study |
| 🌐 | **China-friendly mirrors** | Built-in npm/pip/git mirror sources |
| 💡 | **Code quality** | Meaningful naming, clear comments, keep it simple |

## Quick Start

```bash
# Install the skill
mkdir -p ~/.claude/skills
git clone https://github.com/zxcmnv520/student-skill.git ~/.claude/skills/student

# Then in Claude Code, just type:
/student
```

## Usage

Once loaded, the skill guides Claude to:

- **Explain trade-offs** — when there are multiple approaches, you'll see pros and cons
- **Prioritize learning** — concepts are explained before code is written
- **Keep records** — session notes and lessons learned are auto-generated
- **Write clean code** — meaningful names, purposeful comments, no over-engineering

### Examples

| Scenario | What happens |
|----------|-------------|
| Course project | Understand requirements → design → implement → explain key code |
| Lab report | Record process → analyze data → visualize → draw conclusions |
| Competition | Fast prototype → iterate → document debugging journey |
| Thesis | Tech research → architecture → phased delivery → documentation |
| Self-study | Concept explanation → code examples → practice suggestions |

## Contents

```
student-skill/
├── SKILL.md       # The skill ruleset (loaded by Claude Code)
├── README.md      # This file
└── LICENSE        # MIT
```

## License

MIT — free to use, modify, and share.
