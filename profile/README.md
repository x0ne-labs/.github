# x0ne labs

Confidential AI inference and hardened tooling for AI agents.

| Project | What it does | Status |
|---|---|---|
| [**x0ne Engine**](https://github.com/x0ne-labs/x0ne-Engine) | Runs an open model inside a confidential virtual machine (Intel TDX with one NVIDIA H100) in your own Google Cloud account. Your machine checks a hardware proof of what runs there before any question is sent; then your applications call it like the OpenAI API. | Preview |
| [**x0ne Harness**](https://github.com/x0ne-labs/x0ne-Harness) | A safety layer between an AI agent and your machine: every action is typed and checked against a policy before it runs, files are snapshotted before they change, and actions are journaled. Its own terminal agent, or an MCP server for Claude Code and Codex. | Preview 0.2.0 |

Both projects are in preview. Read the **Status** section of each README before relying on them:
it says what is measured, what is not, and what is not covered yet.

## Security

Report a vulnerability through the `SECURITY.md` of the repository concerned. Please do not open a public issue.

## Links

[x0ne.co](https://x0ne.co) · [Engine](https://x0ne.co/en/engine) · [Harness](https://x0ne.co/harness)
