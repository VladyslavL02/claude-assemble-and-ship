## qa-kit Plugin

A collection of Claude Code commands and agents for quality assurance workflows.

### Commands
- `/summarize-changes` — Summarize what changed on a branch

### Agents
- `code-reviewer` — Review recent changes for bugs and improvements

### Plugin Structure
- `.claude-plugin/plugin.json` — plugin manifest
- `commands/` — slash commands
- `agents/` — subagents for code review

### Getting Started
1. Load the plugin: `claude --plugin-dir .`
2. Run commands by their namespaced name (e.g., `/your-plugin:summarize-changes`)
3. Trigger the code-reviewer subagent by asking for a review
4. Use `/reload-plugins` after making edits
