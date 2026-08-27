# homestead

dotfiles: bash + vim + git, symlinked by install.sh

## How to use

```bash
# configs are symlinked, edit here and it applies everywhere
```

## Installation

```bash
git clone <this repo> ~/.dotfiles
cd ~/.dotfiles
./install.sh
```

## Highlights

- Sane vim defaults, no plugins required
- Bash prompt with git branch indicator
- Git aliases I actually use daily
- One-command setup: ./install.sh

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .bashrc
├── .editorconfig
├── .gitignore
├── .vimrc
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
└── install.sh
```

## License

MIT - see [LICENSE](LICENSE).
