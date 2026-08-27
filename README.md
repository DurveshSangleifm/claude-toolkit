# claude-toolkit

Reusable agent skills: review, commit, refactor, test

## How to use

```bash
# skills trigger automatically on matching tasks
# or invoke directly: /code-review
```

## Getting started

```bash
git clone <this repo>
cp -r skills/* ~/.claude/skills/
```

## Features

- Concrete instructions, output formats and examples
- Each skill is a folder with a single SKILL.md
- Drop-in compatible with ~/.claude/skills
- YAML frontmatter: name + when-to-use description
- Versioned like code: review changes in PRs

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── skills/
│   ├── code-review/
│   │   └── SKILL.md
│   ├── commit-message/
│   │   └── SKILL.md
│   ├── refactor-plan/
│   │   └── SKILL.md
│   └── test-writer/
│       └── SKILL.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── Makefile
└── SECURITY.md
```

## License

MIT - see [LICENSE](LICENSE).
