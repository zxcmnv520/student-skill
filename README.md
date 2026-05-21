# student-skill

> **student** — Claude Code skill for students. Learn with AI, not just from AI.

A Claude Code skill designed for students. Helps you learn, document, and build better — whether it's course projects, lab reports, competitions, or your thesis.

## Features

- **Learning-first workflow** — understand the *why* before the *how*
- **Study journaling** — effortless project & experiment documentation
- **Code quality awareness** — naming, comments, simplicity
- **Chinese mirror priority** — built-in mirror sources for npm/pip/git (China-friendly)
- **Scenario-tailored** — adapts to homework, labs, competitions, thesis, self-study

## Installation

```bash
# Clone the repo into your Claude Code skills directory
mkdir -p ~/.claude/skills
git clone https://github.com/zxcmnv520/student-skill.git ~/.claude/skills/student
```

Or just copy `SKILL.md` into `.claude/skills/student/`:

```bash
mkdir -p ~/.claude/skills/student
# Copy SKILL.md into that directory
```

Once installed, invoke it in Claude Code with:

```
/student
```

## Contents

- `SKILL.md` — The skill ruleset loaded by Claude Code

## Usage

When you start a session, type `/student` to load the student workflow rules. Claude will then follow the learning-oriented rules for that session.

## License

MIT
