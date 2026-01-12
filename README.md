# claude-plugins

My Claude Code Plugins

## Installation

In Claude Code, run the following command to add the plugin marketplace:

```
/plugin marketplace add toshimaru/claude-plugins
```

After adding the marketplace, you can discover and install the plugins by running:

```
❯ /plugin
───────────────────────────────────────────────────────────────────────────
 Plugins  Discover   Installed   Marketplaces  (←/→ or tab to cycle)

 Discover plugins
 ╭─────────────────────────────────────────────────────────────────────╮
 │ ⌕ simple-git█                                                       │
 ╰─────────────────────────────────────────────────────────────────────╯

   ◯ simple-git · toshimaru-claude-plugins · 0 installs
     simple git commands

 Type to search · Space: (de)select · Enter: details · Esc: back
```

## Available Plugins

| Plugin | Description |
|:------:|-------------|
| [simple-git](./plugins/simple-git) | Simple git commands |

## Commands

### `/auto-commit` - Auto Commit

Create a git commit with Co-Authored-By trailer.

### `/push` - Push

Push commits to remote repository.

### `/pull` - Pull

Pull changes from remote repository.
