# Inlinr — community

Feature requests, questions and roadmap discussion for
[Inlinr](https://inlinr.com), time tracking for developers.

The product itself is closed-source, so this repository exists purely so the
conversation is not. Nothing here is a code repository — it is Discussions and
Issues.

## Where to go

| | |
|---|---|
| **Vote for a planned idea** | Add a 👍 to its [roadmap issue](https://github.com/inlinrhq/inlinr/issues?q=is%3Aissue+is%3Aopen+label%3Aroadmap+sort%3Areactions-%2B1-desc) |
| **Suggest something new** | [Discussions → Ideas](https://github.com/inlinrhq/inlinr/discussions/categories/ideas) |
| **Report a bug** | [Issues](https://github.com/inlinrhq/inlinr/issues) |
| **See what's planned** | [inlinr.com/roadmap](https://inlinr.com/roadmap) |

👍 are how the roadmap gets reordered: every idea under Considering has an
issue labelled `roadmap`, and [inlinr.com/roadmap](https://inlinr.com/roadmap)
lists them by votes. An editor ten people ask for moves ahead of one nobody has
mentioned, which is more useful than a form that disappears into an inbox.

<!-- roadmap:start -->
## Roadmap

Mirrors [inlinr.com/roadmap](https://inlinr.com/roadmap), which is the
reference. Nothing is listed as available until it works in production.
Last updated 14 Oct 2026.

### ✅ Available

In production. Install it today.

| | |
|---|---|
| **VS Code, Cursor and Windsurf** | Automatic tracking from the editor, with AI attribution that only fires when an assistant actually wrote something. |
| **Claude Code** | Time, token counts and assistant-written lines — in the terminal, the desktop app, inside any editor, and in cloud sessions. |
| **Teams** | Roll up time across a repository. Teammates see hours per repository and per member — never each other's files. |
| **Seat-based team billing** | One subscription for the team, one seat per active member, prorated when people join or leave. |
| **Client share links** | A read-only report you choose the contents of, optionally PIN-protected. |
| **Invoices and hourly rates** | Printable invoices from tracked time and billable manual entries, with versioned rates so raising yours never rewrites an old invoice. |
| **Manual entries** | Meetings, calls and reviews logged by hand, billable or not, next to the tracked time. |
| **File history** | Every file of a project with its time, its edits and how much an assistant wrote, day by day. |
| **WakaTime import** | Bring your WakaTime history with you, computed with the same idle rule as live data. |
| **Dependency feed** | Opt in per project for a feed of releases, release notes and security advisories for the npm packages it declares. Off by default, and switching it off deletes what was stored. |
| **Public profile and README card** | An opt-in profile page and an SVG card for your GitHub README, light or dark, with languages, editors and AI share. |
| **Weekly target** | Set the hours you aim for each week and watch the dashboard fill toward them. |
| **Your WakaTime plugins, pointed at Inlinr** | A WakaTime-compatible API, so any editor with a WakaTime plugin can send its time here with one line of config. |

### 🔨 In progress

Being built now. Not usable yet.

| | |
|---|---|
| **Shipped vs edited code** | Commit line counts next to editing time, so rework is visible rather than implied. |

### 💭 Considering

Wanted, not started. Add a 👍 to an idea's issue to move it up: [inlinr.com/roadmap](https://inlinr.com/roadmap) lists them by votes.

| | | |
|---|---|---|
| **AI costs on client invoices** | An optional line for what an assistant cost on a project, and a budget per project that warns before it runs out. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/7) |
| **Time per ticket** | Read the ticket key in your branch name (ABC-123, #123) to show time and AI cost per ticket. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/8) |
| **Calendar, Toggl and Clockify import** | Turn the meetings in a Google or Outlook calendar into manual entries you confirm, and bring your Toggl or Clockify history the way WakaTime history already comes in. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/9) |
| **A switch from WakaTime in one sitting** | Your WakaTime dashboards and status-bar tools reading from Inlinr too, and a guide for sending to both while you compare. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/10) |
| **Public demo dashboard** | Fictional data, read-only, no account: see the time, AI cost and invoice views before signing up. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/11) |
| **Locked invoices and e-invoicing export** | An invoice frozen once issued, exported as Factur-X and to the invoicing tools freelancers already use. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/12) |
| **Inlinr inside your assistant** | An MCP server, so an assistant can tell you your time and AI cost this week, or log a manual entry, without leaving the chat. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/13) |
| **More AI assistants** | Token and line counts from Codex, Gemini CLI and other assistants that keep local transcripts, like Claude Code today. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/6) |
| **Monthly AI report by email** | Once a month, your share of AI-written code, what the assistants cost, and which projects it went to. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/14) |
| **JetBrains plugin** | A native plugin for IntelliJ, WebStorm, PyCharm, GoLand and Rider, with AI attribution. Their WakaTime plugin already sends time today. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/4) |
| **Neovim plugin** | A native Lua plugin, lazy-loadable, with AI attribution. The WakaTime plugin already sends time today. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/5) |
<!-- roadmap:end -->

Something missing? Open an idea in
[Discussions](https://github.com/inlinrhq/inlinr/discussions/categories/ideas).

## Plugins, which are open

| | |
|---|---|
| Claude Code | [inlinrhq/inlinr-claude-code](https://github.com/inlinrhq/inlinr-claude-code) |
| CLI | [inlinrhq/inlinr-cli](https://github.com/inlinrhq/inlinr-cli) |
| VS Code | [inlinrhq/inlinr-vscode](https://github.com/inlinrhq/inlinr-vscode) |

## Security

For anything involving other people's data, email **contact@inlinr.com**
rather than opening a public issue.
