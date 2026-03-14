# Ghostty Config

My personal [Ghostty](https://ghostty.org/) terminal configuration.

## Features

- Semi-transparent background with blur effect
- Hidden titlebar for a clean look
- Auto-copy on select
- Clipboard paste protection
- `Cmd+D` to split right
- Command finish notifications

## Claude Code Friendly

This config works well with [Claude Code](https://docs.anthropic.com/en/docs/claude-code):

- **Command finish notifications** — long-running tasks will send a push notification when done
- **Clipboard paste protection** — prevents accidental execution of dangerous commands
- **Split pane (`Cmd+D`)** — run Claude Code in one pane, keep another for manual commands

## Usage

```bash
git clone git@github.com:jasontsaicc/ghostty-config.git ~/.config/ghostty
```
