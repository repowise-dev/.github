<p align="center">
  <img src="https://repowise.dev/favicon.ico" width="48" />
</p>

<h3 align="center">Repowise</h3>
<p align="center">Codebase intelligence for AI coding agents.<br/>Your agent stops guessing. Starts knowing.</p>

<p align="center">
  <a href="https://repowise.dev">repowise.dev</a> · 
  <a href="https://pypi.org/project/repowise/">pip install repowise</a> · 
  <a href="https://discord.gg/cQVpuDB6rh">Discord</a> · 
</p>

---

**Repowise indexes your codebase into four intelligence layers** — dependency graph, git history, auto-generated documentation, and architectural decisions — then exposes them to Claude Code (or any MCP-compatible agent) through precisely designed tools.

The result: your AI agent answers *"why does auth work this way?"* instead of *"here is what auth.ts contains."*

---

### Repos

| Repo | What it does | |
|:-----|:-------------|:-:|
| [**repowise**](https://github.com/repowise-dev/repowise) | Core engine — AST graph, git analytics, wiki generation, dead code detection, 8 MCP tools. `pip install repowise` | ![](https://img.shields.io/github/stars/repowise-dev/repowise?style=flat&color=yellow) |
| [**claude-code-prompts**](https://github.com/repowise-dev/claude-code-prompts) | Independently authored prompt templates for AI coding agents — system prompts, tool routing, agent delegation, memory, multi-agent coordination | ![](https://img.shields.io/github/stars/repowise-dev/claude-code-prompts?style=flat&color=yellow) |
| [**modpack**](https://github.com/repowise-dev/modpack) | 15 Claude Code skills that change how your agent thinks, debugs, and reviews. `npx skills add repowise-dev/modpack` | ![](https://img.shields.io/github/stars/repowise-dev/modpack?style=flat&color=yellow) |
| [**repowise-bench**](https://github.com/repowise-dev/repowise-bench) | SWE-QA benchmark — 36% cost reduction, 49% fewer tool calls, quality at parity | ![](https://img.shields.io/github/stars/repowise-dev/repowise-bench?style=flat&color=yellow) |

---

### Quick start

```bash
pip install repowise
cd your-project
repowise init        # builds all four layers (~25 min first time)
repowise serve       # MCP server + local dashboard
```

---

<p align="center">
  <sub>Built for engineers who got tired of asking "why does this code exist?"</sub><br/>
  <sub>hello@repowise.dev</sub>
</p>
