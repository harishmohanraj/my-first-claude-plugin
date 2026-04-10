# Claude Code Plugin: greet-user

This repository contains the `greet-user` plugin for Claude Code. It features a single skill designed to facilitate automated greeting interactions within the terminal. The plugin is configured for direct installation and use through standard Claude Code commands.

## Installation

Run the following commands inside your Claude Code session:

```
# 1. Add this repository as a plugin source
/plugin marketplace add harishmohanraj/my-first-claude-plugin

# 2. Install the greet-user plugin
/plugin install greet-user@my-first-claude-plugin

# 3. Reload to activate the new skill
/reload-plugins
```

## Usage

Once installed, you can use the following prompts to trigger the skill:

```
"Greet John Doe"

"Introduce yourself and welcome Jane Doe"

"Say hi to the user"
```

## Removal
To remove the plugin and clean up the marketplace source:

```
/plugin marketplace remove harishmohanraj/my-first-claude-plugin
```
