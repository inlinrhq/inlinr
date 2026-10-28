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
Last updated 28 Oct 2026.

### ✅ Available

In production. Install it today.

| | |
|---|---|
| **VS Code, Cursor and Windsurf** | Automatic tracking from the editor, with AI attribution that only fires when an assistant actually wrote something. |
| **Claude Code** | Time, token counts and assistant-written lines — in the terminal, the desktop app, inside any editor, and in cloud sessions. |
| **Teams** | Roll up time across a repository. Teammates see hours per repository and per member — never each other's files. |
| **Seat-based team billing** | One subscription for the team, one seat per active member, prorated when people join or leave. |
| **Client share links** | A read-only report you choose the contents of, optionally PIN-protected. |
| **Invoices, hourly and day rates** | Invoices from tracked time and billable manual entries, by the hour, by the day or for a fixed price in instalments, with your VAT or its legal mention. Numbered in the series you choose (prefix, year, next number), never billing a day twice, and an overview of what is billed, unpaid and left to bill. |
| **Clients** | Who you bill, with legal name, SIREN or company number, VAT number, address and a default rate, imported from Qonto if you use it. |
| **Qonto** | Import your clients and the invoices you made in Qonto, and create an invoice in Qonto from tracked time, as a Qonto draft or finalized. |
| **Quotes** | A quote for a client before the work: flat fees, days or hours at a rate, expenses and discounts, a validity date and a payment schedule. Numbered in its own series, printed with the same VAT and mentions as an invoice, then marked accepted or declined, or revised. |
| **Manual entries** | Meetings, calls and reviews logged by hand, billable or not, next to the tracked time. |
| **File history** | Every file of a project with its time, its edits and how much an assistant wrote, day by day. |
| **WakaTime import** | Bring your WakaTime history with you, all of it or from a day you choose, computed with the same idle rule as live data. The preview gathers a project's spellings into one row, suggests merges, and remembers where each name goes. |
| **Toggl, Clockify, Harvest and calendar import** | A Toggl Track, Clockify or Harvest CSV export, or the meetings in an .ics calendar, become manual entries you confirm. Every import can be undone. |
| **Merging projects** | Merge two projects that are one repository, keep the old name as one of its other names, and archive or file projects under a client several at a time. |
| **Dependency feed** | Opt in per project for a feed of releases, release notes and security advisories for the npm packages it declares. Off by default, and switching it off deletes what was stored. |
| **Public profile and README card** | An opt-in profile page and an SVG card for your GitHub README, light or dark, with languages, editors and AI share. |
| **Weekly target** | Set the hours you aim for each week and watch the dashboard fill toward them. |
| **Public demo dashboard** | Made-up data, read-only, no account: see the time, AI usage and invoice views before signing up. |
| **Your WakaTime plugins, pointed at Inlinr** | A WakaTime-compatible API, so any editor with a WakaTime plugin can send its time here with one line of config. |
| **A switch from WakaTime in one sitting** | The status bar, summaries and stats that WakaTime's tools read come from Inlinr too, and a guide covers moving over and comparing both for a week. |
| **Inlinr inside your assistant** | An MCP server in the inlinr CLI, so Claude Code, Cursor or any MCP client can tell you your time and AI cost, log a manual entry, or check your dependencies, without leaving the chat. |
| **Codex and Gemini CLI** | Time, tokens and the lines each assistant wrote, read from the sessions Codex and Gemini CLI keep on your machine, like Claude Code's. |

### 🔨 In progress

Being built now. Not usable yet.

| | |
|---|---|
| **Shipped vs edited code** | Commit line counts next to editing time, so rework is visible rather than implied. |
| **E-invoices through Qonto** | An invoice from tracked time can already be created in Qonto, which can send it as the e-invoice French business clients need from September 2027. What is left is sending it that way from Inlinr, in the same step. The printable invoice stays for clients abroad. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/12) |

### 💭 Considering

Wanted, not started. Add a 👍 to an idea's issue to move it up: [inlinr.com/roadmap](https://inlinr.com/roadmap) lists them by votes.

| | | |
|---|---|---|
| **AI costs on client invoices** | An optional line for what an assistant cost on a project, and a budget per project that warns before it runs out. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/7) |
| **Time per ticket** | Read the ticket key in your branch name (ABC-123, #123) to show time and AI cost per ticket. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/8) |
| **More AI assistants** | opencode and other assistants that keep their sessions on your machine, like Claude Code, Codex and Gemini CLI today. | [👍 Vote](https://github.com/inlinrhq/inlinr/issues/6) |
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

For anything involving other people's data, email **support@inlinr.com**
rather than opening a public issue.
