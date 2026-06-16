# Claude Code Haha
![Claude Code Haha](docs/images/logo-horizontal.png)
![GitHub Stars](https://img.shields.io/github/stars/NanmiCoder/cc-haha?style=social)
![GitHub Forks](https://img.shields.io/github/forks/NanmiCoder/cc-haha?style=social)
![GitHub Issues](https://img.shields.io/github/issues/NanmiCoder/cc-haha){width=22%}
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/NanmiCoder/cc-haha)
![License](https://img.shields.io/github/license/NanmiCoder/cc-haha)
![中文](https://img.shields.io/badge/🇨🇳_中文-Available-green)
![English](https://img.shields.io/badge/🇺🇸_English-当前-blue)
![Docs](https://img.shields.io/badge/📖_Documentation-Visit-FF7A00)
A Claude Code build repaired from the source leaked from Anthropic's npm registry on 2026-03-31. Claude Code Haha is now primarily a **desktop Claude Code workspace** for macOS and Windows: sessions, projects, branch / Worktree launch, right-side file changes, code diffs, permission review, provider setup, Computer Use, H5 remote access, IM integration, and scheduled tasks in one app.

[Desktop Preview](#desktop-preview) · [Install](#install-the-desktop-app) · [Highlights](#desktop-highlights) · [Sponsorship](#sponsorship--partnership) · [More Docs](#more-documentation)

---
## Desktop Preview
The Claude Code Haha desktop app brings sessions, multi-project navigation, branch / Worktree controls, right-side file changes, code diffs, permission review, provider setup, and remote access into one graphical workspace for daily development flows beyond the terminal.
![Download Desktop](https://img.shields.io/badge/⬇_Download_Desktop-macOS_%7C_Windows-FF7A00?style=for-the-badge)
  [](docs/desktop/04-installation.md)

|                                                                                              |                                                                                                                                     |                                                                                            |                                                                                                                            |
| :--------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: |
| ![Desktop workspace](docs/images/desktop_ui/10_desktop_workspace.png) **Desktop Workspace** | ![Right-side changes and Worktree](docs/images/desktop_ui/13_workspace_changes_worktree.png) **Right-side Changes & Worktree** | ![Code editing](docs/images/desktop_ui/02_edit_code.png) **Code Editing & Diff View** | ![Permission control](docs/images/desktop_ui/03_ask_question_and_permission.png) **Permission Review & AI Questions** |
| ![H5 remote access](docs/images/desktop_ui/12_h5_access.png) **H5 Remote Access**           | ![Token usage](docs/images/desktop_ui/11_token_usage.png) **Token Usage**                                                          | ![Computer Use](docs/images/desktop_ui/06_settings_computer_use.png) **Computer Use**     | ![Scheduled tasks](docs/images/desktop_ui/08_scheduled_task.png) **Scheduled Tasks**                                      |

---
## Install the Desktop App
1. Download the macOS or Windows desktop installer from [Releases](https://github.com/NanmiCoder/cc-haha/releases).
2. On first launch, configure your model provider, API key, and default model in Settings.
3. If macOS blocks the app on first open, follow the [desktop installation guide](docs/desktop/04-installation.md) for Gatekeeper steps.
## Run the CLI from Source
For users who want to debug the underlying CLI, server, or local development flow:
```bash
bun install
cp .env.example .env
./bin/claude-haha
```
See [environment variables](docs/en/guide/env-vars.md) and [global usage](docs/en/guide/global-usage.md) for more configuration options.

---
## Desktop Highlights
- **Multi-session workspace**: tabs, project switching, terminal entry, and session history in one place.
- **Branch / Worktree launch**: choose a repository branch and decide whether to use the current working tree or an isolated Worktree.
- **Right-side file changes**: review changed files, added/removed lines, and current workspace state while chatting.
- **Visual code changes**: inspect edits, file writes, and diffs directly in the desktop app.
- **Permission review**: approve risky commands, tool calls, and model follow-up questions in the GUI.
- **Multi-provider setup**: configure Anthropic-compatible APIs, third-party models, WebSearch fallback, and local options.
- **Computer Use**: let the agent take screenshots, click, type, and control desktop apps after authorization.
- **H5 remote access**: open the current desktop session from a phone or another device with a one-time token.
- **IM integration**: chat, switch projects, and approve actions through Telegram / Feishu / WeChat / DingTalk.
- **Scheduled tasks and usage stats**: create planned tasks and track local token usage trends.
---
## More Documentation

| Document                                                    | Description                                                                                                                                                                    |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Environment Variables](docs/en/guide/env-vars.md)          | Full env var reference and configuration methods                                                                                                                               |
| [Third-Party Models](docs/en/guide/third-party-models.md)   | Using OpenAI / DeepSeek / Ollama and other non-Anthropic models                                                                                                                |
| [Contributing](docs/en/guide/contributing.md)               | Local tests, live model baselines, PR gates, and release gates                                                                                                                 |
| [Memory System](docs/memory/01-usage-guide.md)              | Cross-session persistent memory usage and implementation                                                                                                                       |
| [Multi-Agent System](docs/agent/01-usage-guide.md)          | Agent orchestration, parallel tasks and Teams collaboration                                                                                                                    |
| [Skills System](docs/skills/01-usage-guide.md)              | Extensible capability plugins, custom workflows and conditional activation                                                                                                     |
| [IM Integration](docs/im/)                                  | Remote chat, project switching, and permission approval via Telegram / Feishu / WeChat / DingTalk                                                                              |
| [Computer Use](docs/en/features/computer-use.md)            | Desktop control (screenshots, mouse, keyboard) — [Architecture](docs/en/features/computer-use-architecture.md)                                                                 |
| [Desktop App](docs/desktop/)                                | Tauri 2 + React GUI client — [Quick Start](docs/desktop/01-quick-start.md) | [Architecture](docs/desktop/02-architecture.md) | [Installation](docs/desktop/04-installation.md) |
| [Global Usage](docs/en/guide/global-usage.md)               | Run claude-haha from any directory                                                                                                                                             |
| [FAQ](docs/en/guide/faq.md)                                 | Common error troubleshooting                                                                                                                                                   |
| [Source Fixes](docs/en/reference/fixes.md)                  | Fixes compared with the original leaked source                                                                                                                                 |
| [Project Structure](docs/en/reference/project-structure.md) | Code directory structure                                                                                                                                                       |

---
## Sponsorship & Partnership
This project is maintained in the author's spare time. Corporate or individual sponsorships are welcome to support ongoing development. Custom features, integrations, and business partnerships are also open for discussion.

| Sponsor                                                                                                    | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| :----------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![JieKou AI](docs/images/sponsors/jiekou-logo.svg) [接口AI](https://jiekou.ai/referral?invited_code=OBNU3K) | Thanks to [JieKou AI](https://jiekou.ai/referral?invited_code=OBNU3K) for sponsoring this project. JieKou AI provides official model resources with stable, high-performance API access. Subscription bundles are priced at 20% off the official rate; new users who register through [this link](https://jiekou.ai/referral?invited_code=OBNU3K) and bind GitHub can claim a $3 coupon.                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ![ShengSuanYun](docs/images/sponsors/shengsuanyun-logo.svg)                                                | Thanks to [ShengSuanYun](https://www.shengsuanyun.com/?from=CH_LEJ88KWR) for sponsoring this project. ShengSuanYun is an industrial-grade AI task parallel execution platform for AI Native Teams, aggregating Claude, ChatGPT, Gemini, and other LLM, image, and video model capacity through direct, non-reverse-engineered access. Its platform SLA reaches 99.7%, with [service status](https://watch.shengsuanyun.com/status/shengsuanyun) available online. It also supports dedicated enterprise gateways, cost and permission controls, smart routing, security protection, BYOK, usage-based billing, upcoming tokens plans, and invoicing. New users registering through [this link](https://www.shengsuanyun.com/?from=CH_LEJ88KWR) can receive 10 yuan in model credits plus a 10% first top-up bonus. |

📧 **Contact**: [relakkes@gmail.com](mailto:relakkes@gmail.com)

---
## ☕ Buy Me a Coffee
If this project helps you, consider buying me a coffee — every bit of support keeps this project going ❤️

|                                                                   |                                                       |                                                                            |
| :-----------------------------------------------------------------: | :-----------------------------------------------------: | :--------------------------------------------------------------------------: |
| ![WeChat Pay](docs/images/donate/wechat_pay.jpeg) **WeChat Pay** | ![Alipay](docs/images/donate/zfb_pay.png) **Alipay** | ![Buy Me a Coffee](docs/images/donate/bmc_button.png) **Buy Me a Coffee** |

---
## Tech Stack

| Category      | Technology                                         |
| ------------- | -------------------------------------------------- |
| Language      | TypeScript                                         |
| Desktop app   | Tauri 2                                            |
| Desktop UI    | React + Vite                                       |
| Local runtime | [Bun](https://bun.sh)                              |
| Terminal UI   | React + [Ink](https://github.com/vadimdemedes/ink) |
| CLI parsing   | Commander.js                                       |
| API           | Anthropic SDK                                      |
| Protocols     | MCP, LSP                                           |

## Thanks
Thanks to the following open-source projects and community practices for reference and inspiration:
- [React](https://github.com/facebook/react): frontend engineering and component-based UI ecosystem.
- [Tauri](https://github.com/tauri-apps/tauri): cross-platform desktop app capabilities and engineering practices.
- [cc-switch](https://github.com/farion1231/cc-switch): reference for model provider configuration.
---
## ⭐ Star History
If this project helps you, please support it with a ⭐ Star so more people can discover Claude Code Haha.
![Star History Chart](https://api.star-history.com/svg?repos=NanmiCoder/cc-haha&type=Date)
---
## Disclaimer
This repository is based on the Claude Code source leaked from the Anthropic npm registry on 2026-03-31. All original source code copyrights belong to [Anthropic](https://www.anthropic.com). It is provided for learning and research purposes only.