<picture>
  <source media="(max-width: 480px), (min-width: 768px) and (max-width: 899px)" srcset="assets/scoreboard-mobile.svg">
  <source media="(max-width: 1119px)" srcset="assets/scoreboard-mid.svg">
  <img src="assets/scoreboard.svg" width="100%" alt="Scoreboard for MUÑOZ REY, DAVID. Founder-engineer: strategy, product and code, judged by what ships. Six attempts, each judged by three lamps: shipped, tested, public. Two white lamps make a good lift; fewer reads pending, not failed. AEP Tarima: Referee operations, Spanish powerlifting (1,233 tests). Shipped, tested, public source; good lift. Trazum: Open-source AI spend analysis (npm 2.7.7). Shipped, tested, public source; good lift. Propel: AI-native CRM for outbound sales (propeltech.io). Shipped, tested, private source; good lift. Axis: ECG decision-support copilot (12-lead ECG). Not shipped yet, tested, public source; good lift. Zolts: GTM operating system (10 blueprints). Not shipped yet, tested, public source; good lift. Atesta: Audit readiness for ENS and NIS2 (ENS + NIS2). Not shipped yet, tested, private source; pending.">
</picture>

**Founder-engineer.** Strategy, product and code, judged by what ships.<br>
[LinkedIn](https://www.linkedin.com/in/davmunrey) · [Trazum on npm](https://www.npmjs.com/package/@trazum/cli) · [AEP Tarima, live](https://aep-tarima.vercel.app)

[![upstream merged](https://img.shields.io/github/issues-search?query=is%3Apr%20is%3Amerged%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey&label=upstream%20PRs%20merged&color=2ea44f&style=flat-square)](https://github.com/search?type=pullrequests&q=is%3Apr%20is%3Amerged%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey) [![upstream in review](https://img.shields.io/github/issues-search?query=is%3Apr%20is%3Aopen%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey&label=in%20review&color=blue&style=flat-square)](https://github.com/search?type=pullrequests&q=is%3Apr%20is%3Aopen%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey) [![issues reported](https://img.shields.io/github/issues-search?query=is%3Aissue%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey&label=issues%20reported&color=8250df&style=flat-square)](https://github.com/search?type=issues&q=is%3Aissue%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey)

## Attempts

Lamps, as on a powerlifting platform: **shipped** · **tested** · **public source**. Two white lamps make a good lift.

| | Project | What it does | Status | Stack |
|---|---|---|---|---|
| ⚪⚪⚪ | **[AEP Tarima](https://aep-tarima.vercel.app)** | Referee operations for Spanish powerlifting: championships, rosters, payouts, rules, exams | Live · v2.15 · 1,233 tests · [source](https://github.com/Davmunrey/AEP-Referee-APP) | Next.js 15, Supabase Realtime |
| ⚪⚪⚪ | **[Trazum](https://github.com/Davmunrey/Trazum)** | Prices AI agent and API usage locally, per call; agents ask its MCP `spend_guard` before they spend | `@trazum/cli` 2.7.7 · MIT · zero deps | TypeScript, MCP |
| ⚪⚪⚫ | **[Propel](https://propeltech.io)** | AI-native CRM for outbound sales: Gmail threads, pipelines, sequences | Live · private repo | |
| ⚫⚪⚪ | **[Axis](https://github.com/Davmunrey/Heartcheck)** | ECG decision support: photo or 12-lead signal to a structured read | R&D | PyTorch CNN-1D (PTB-XL), FastAPI, Flutter |
| ⚫⚪⚪ | **[Zolts](https://github.com/Davmunrey/Zolts)** | GTM operating system: signals to decisions, plays and revenue, measured against holdouts | In build · 10 blueprints | Python 3.11, FastAPI, Postgres, Claude agents |
| ⚫⚪⚫ | **Atesta** | Continuous ENS and NIS2 audit readiness for Spanish SMEs, read-only on Microsoft 365 or Google Workspace | In build · private repo | |

Try one in a minute, locally, no provider key:

```bash
npx @trazum/cli bill
```

## Upstream

Fixes to other people's projects, held to their review and CI.

| Project | | Merged | In review | Reported | Focus |
|---|---|---|---|---|---|
| **[REA](https://github.com/morluto/rea)** | ![stars](https://img.shields.io/github/stars/morluto/rea?style=flat-square&label=%E2%98%85&color=gold) | [#10620](https://github.com/morluto/rea/pull/10620) · [#10623](https://github.com/morluto/rea/pull/10623) | [![open](https://img.shields.io/github/issues-search?query=repo%3Amorluto/rea%20is%3Apr%20is%3Aopen%20author%3ADavmunrey&label=open&color=blue&style=flat-square)](https://github.com/search?type=pullrequests&q=repo%3Amorluto/rea%20is%3Apr%20is%3Aopen%20author%3ADavmunrey) | [#10687](https://github.com/morluto/rea/issues/10687) · [#10688](https://github.com/morluto/rea/issues/10688) · [#11393](https://github.com/morluto/rea/issues/11393) | .NET, Apple bundles, Android, NES 2.0, Ghidra, Kuna, Hopper, JavaScript |
| **[Univer](https://github.com/dream-num/univer)** | ![stars](https://img.shields.io/github/stars/dream-num/univer?style=flat-square&label=%E2%98%85&color=gold) | [#8215](https://github.com/dream-num/univer/pull/8215) · [#8217](https://github.com/dream-num/univer/pull/8217) | [![open](https://img.shields.io/github/issues-search?query=repo%3Adream-num/univer%20is%3Apr%20is%3Aopen%20author%3ADavmunrey&label=open&color=blue&style=flat-square)](https://github.com/search?type=pullrequests&q=repo%3Adream-num/univer%20is%3Apr%20is%3Aopen%20author%3ADavmunrey) | [#8211](https://github.com/dream-num/univer/issues/8211) · [#8229](https://github.com/dream-num/univer/issues/8229) · [#8231](https://github.com/dream-num/univer/issues/8231) | Excel parity: formulas, filters, sorting, validation, conditional formatting |
| **[gstack](https://github.com/garrytan/gstack)** | ![stars](https://img.shields.io/github/stars/garrytan/gstack?style=flat-square&label=%E2%98%85&color=gold) | [#4394](https://github.com/garrytan/gstack/pull/4394) | [![open](https://img.shields.io/github/issues-search?query=repo%3Agarrytan/gstack%20is%3Apr%20is%3Aopen%20author%3ADavmunrey&label=open&color=blue&style=flat-square)](https://github.com/search?type=pullrequests&q=repo%3Agarrytan/gstack%20is%3Apr%20is%3Aopen%20author%3ADavmunrey) | [#4391](https://github.com/garrytan/gstack/issues/4391) · [#4392](https://github.com/garrytan/gstack/issues/4392) | Docs link check, prose lint, issue links |
| **[Prowler](https://github.com/prowler-cloud/prowler)** | ![stars](https://img.shields.io/github/stars/prowler-cloud/prowler?style=flat-square&label=%E2%98%85&color=gold) | | | Proposed: [#13387](https://github.com/prowler-cloud/prowler/issues/13387) | ENS RD 311/2022 for Microsoft 365 |

## Rules I build by

Each one is a written project rule in one of my repositories.

| Rule | Means |
|---|---|
| **Wired or it doesn't ship** | No delivered screen runs on mock data |
| **Fail closed** | A failed read is an error, not an empty list; permissions default to deny |
| **Paid money doesn't move** | A settled payout in AEP Tarima freezes its amount and the referee's seat |
| **Estimates are not outcomes** | Trazum keeps projected savings apart from measured ones; `verify` checks a plan against later usage |
| **One owner per fact** | Design tokens, copy, data and secrets each live in exactly one place |

## Work with me

| If you are | Start here |
|---|---|
| Investing or co-founding | Read the [Zolts plan](https://github.com/Davmunrey/Zolts), then [message me](https://www.linkedin.com/in/davmunrey) |
| Needing a system built | Open [AEP Tarima](https://aep-tarima.vercel.app) or [Propel](https://propeltech.io), the bar I build to, then [message me](https://www.linkedin.com/in/davmunrey) |
| Writing code | Run `npx @trazum/cli bill` and [open an issue](https://github.com/Davmunrey/Trazum/issues) with what it got wrong |
| Hiring | The attempts above are the CV; [LinkedIn](https://www.linkedin.com/in/davmunrey) has the rest |

<details>
<summary>Also shipped</summary>

- [Proposal Engine](https://github.com/MunozRey/Proposal-Engine): proposal studio for CreditCheck with live preview and PDF, HTML and DOCX export in six languages.
- [CreditCheck Dashboard](https://github.com/Davmunrey/CreditCheck-Dashboard): lead scoring and insights for CreditCheck.

</details>
