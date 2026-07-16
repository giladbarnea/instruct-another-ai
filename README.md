# Instruct Another AI

A Claude Code skill for deciding when delegation is worthwhile and for giving subagents or agent teams enough context to do useful work.

It focuses on the part that usually determines whether multi-agent work helps: preserve the user's goal and the main agent's context without over-prescribing the implementation. It also distinguishes independent parallel research from collaborative implementer–reviewer teams.

## Install

In Claude Code, add this repository as a marketplace and install the plugin:

```text
/plugin marketplace add giladbarnea/instruct-another-ai
/plugin install instruct-another-ai@giladbarnea
```

Claude then activates the skill for requests involving subagents, delegation, agent teams, or documentation written for other agents.

## Local development

Run Claude Code against a checkout to test changes without installing it:

```bash
claude --plugin-dir /path/to/instruct-another-ai
```

## License

[MIT](LICENSE)
