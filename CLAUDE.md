# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a home directory dotfiles repository (`~`) tracking personal shell configuration files. It is connected to `https://github.com/ryusei132/my-first-project.git`.

The repository currently tracks:
- `.zshrc` — shell configuration; sets `PATH` to include `~/.local/bin` and the `gh` CLI binary at `~/Downloads/gh_2.87.0_macOS_amd64/bin`

## Environment

- Shell: zsh on macOS (Darwin)
- `gh` (GitHub CLI) is available at `~/Downloads/gh_2.87.0_macOS_amd64/bin/gh`
- Python/Node/other runtimes: not yet configured in `.zshrc`

## Common Tasks

Stage and commit dotfile changes:
```sh
git add .zshrc
git commit -m "update zshrc"
git push -u origin main
```
