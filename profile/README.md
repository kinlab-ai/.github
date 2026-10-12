<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/kin-logo-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/kin-logo-light.png">
    <img src="assets/kin-logo-light.png" alt="Kin" width="200">
  </picture>
</p>

<h3 align="center">A new foundation for code.</h3>

<p align="center">
  A graph-native code repository for AI agents and the people who build with them.
</p>

<p align="center">
  <a href="https://kinlab.ai">kinlab.ai</a>
  &nbsp;·&nbsp;
  <a href="https://kinlab.ai/docs">Docs</a>
  &nbsp;·&nbsp;
  <a href="https://kinlab.ai/install">Install</a>
  &nbsp;·&nbsp;
  <a href="https://kinlab.ai/demo">Browser demo</a>
</p>

<br>

Kin stores source, recorded code relationships, and versioned history as repository state. The graph is the repository model, not a search index maintained beside another repository. You work with it through the `kin` CLI and VS Code, and your coding agents query the same record over MCP.

**Open source. Public beta.**

## Try Kin

Start in a fresh, full clone of a project you know well. On macOS, Linux or WSL2, one command installs Kin and connects the AI coding tools it finds. It needs Node.js 20 or newer.

```sh
npx -y @kinlab/kin setup
```

Other install methods and platforms are in the [installation guide](https://kinlab.ai/install).

## Where to start

| Project | What it is |
| --- | --- |
| **[kin](https://github.com/kinlab-ai/kin)** | The repository itself, with the `kin` CLI, the daemon and the MCP server. Start here. |
| **[kin-editor](https://github.com/kinlab-ai/kin-editor)** | The VS Code extension. Explore code, follow recorded connections and review changes in your editor. |
| **[@kinlab/kin-mcp](https://www.npmjs.com/package/@kinlab/kin-mcp)** | Kin's MCP server for Claude Code, Codex, Cursor and other agents, packaged for npm. Its source lives in kin. |

**The libraries behind Kin.**
[kin-db](https://github.com/kinlab-ai/kin-db) ·
[kin-model](https://github.com/kinlab-ai/kin-model) ·
[kin-lsp](https://github.com/kinlab-ai/kin-lsp) ·
[kin-search](https://github.com/kinlab-ai/kin-search) ·
[kin-vector](https://github.com/kinlab-ai/kin-vector) ·
[kin-infer](https://github.com/kinlab-ai/kin-infer) ·
[kin-blobs](https://github.com/kinlab-ai/kin-blobs)

**Install, evidence and release.**
[homebrew-kin](https://github.com/kinlab-ai/homebrew-kin) ·
[kin-bench-spec](https://github.com/kinlab-ai/kin-bench-spec) ·
[kin-actions](https://github.com/kinlab-ai/kin-actions)

## Get in touch

Bring questions and ideas to [Discussions](https://github.com/kinlab-ai/kin/discussions). To talk about trying Kin on your team's code, write to [troy@kinlab.ai](mailto:troy@kinlab.ai).

KinLab, our hosted product for teams, is in development.
