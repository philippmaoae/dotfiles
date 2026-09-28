# dotfiles

My shell and editor configs, managed with a tiny install script

## Usage

```bash
# configs are symlinked, edit here and it applies everywhere
```

## Installation

```bash
git clone <this repo> ~/.dotfiles
cd ~/.dotfiles
./install.sh
```

## What it does

- Sane vim defaults, no plugins required
- One-command setup: ./install.sh
- Bash prompt with git branch indicator
- Git aliases I actually use daily

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .bashrc
├── .gitignore
├── .vimrc
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
└── install.sh
```
