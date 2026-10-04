# cyber-civitas

A self-contained system for running AI coding agents across your projects. A fleet directs the
work, a runtime runs the sessions, channels carry the conversation, and a change process keeps
every repository settled. Claude Code, Cursor, and Codex all take part. No MCP server, no daemon.

| Layer | Packages |
| --- | --- |
| Fleet | [cyberfleet](https://github.com/cyberuni/cyberfleet) |
| Runtime | [cyberlegion](https://github.com/cyberuni/cyberlegion), [cyber-mux](https://github.com/cyberuni/cyber-mux) |
| Communication | [cynapse](https://github.com/cyberuni/cynapse) |
| Process | [cyber-truss](https://github.com/cyberuni/cyber-truss), [cyber-sdd](https://github.com/cyberuni/cyber-sdd) |

Each package ships on its own and is useful on its own. The repositories live in
[cyberuni](https://github.com/cyberuni).

**Read more:** [cyber-civitas.github.io](https://cyber-civitas.github.io): the architecture, the
fleet vocabulary, every component's status, and the decisions that span packages.
