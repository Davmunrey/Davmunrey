<picture>
  <source media="(max-width: 480px), (min-width: 768px) and (max-width: 899px)" srcset="assets/scoreboard-mobile.svg">
  <source media="(max-width: 1119px)" srcset="assets/scoreboard-mid.svg">
  <img src="assets/scoreboard.svg" width="100%" alt="Scoreboard for MUÑOZ REY, DAVID. Founder-engineer: strategy, product and code, judged by what ships. Six attempts, each judged by three lamps: shipped, tested, public. Two white lamps make a good lift; fewer reads pending, not failed. AEP Tarima: Referee operations, Spanish powerlifting (1,233 tests). Shipped, tested, public source; good lift. Trazum: Open-source AI spend analysis (npm 2.7.7). Shipped, tested, public source; good lift. Propel: AI-native CRM for outbound sales (propeltech.io). Shipped, tested, private source; good lift. Axis: ECG decision-support copilot (12-lead ECG). Not shipped yet, tested, public source; good lift. Zolts: GTM operating system (10 blueprints). Not shipped yet, tested, public source; good lift. Atesta: Audit readiness for ENS and NIS2 (ENS + NIS2). Not shipped yet, tested, private source; pending.">
</picture>

**[Message me on LinkedIn](https://www.linkedin.com/in/davmunrey)** · [Trazum on npm](https://www.npmjs.com/package/@trazum/cli) · [AEP Tarima, live](https://aep-tarima.vercel.app)

See where your own agents' money goes. One command, runs locally, no provider key:

```bash
npx @trazum/cli bill
```

## The attempts

The scoreboard is borrowed from AEP Tarima: I built the software Spain's powerlifting referees run on. Each lamp is a fact, not a rating. **Shipped:** you can open it today. **Tested:** an automated test suite ships with the code. **Public:** the source is on GitHub; private repositories keep that lamp dark and are described here, not linked. As at a real meet, two white lamps out of three make a good lift; fewer reads pending, not failed.

**[AEP Tarima](https://aep-tarima.vercel.app)** runs referee operations for the Asociación Española de Powerlifting: championships, platform rosters, payouts, rules and exams.<br>
<sub>Live · v2.15 · 1,233 tests · Next.js 15, Supabase Realtime · [source](https://github.com/Davmunrey/AEP-Referee-APP)</sub>

**[Trazum](https://github.com/Davmunrey/Trazum)** prices AI agent and API usage locally, per call, and ranks what to change. Agents ask its MCP `spend_guard` before they spend.<br>
<sub>`@trazum/cli` 2.7.7 on npm · MIT · zero runtime dependencies · TypeScript, MCP</sub>

**[Propel](https://propeltech.io)** is an AI-native CRM for outbound sales teams: Gmail threads, pipelines, sequences and AI in one workspace.<br>
<sub>Live at propeltech.io · private repository</sub>

**[Axis](https://github.com/Davmunrey/Heartcheck)** is an ECG decision-support copilot: from a photo or a 12-lead signal to a structured read.<br>
<sub>R&D · PyTorch CNN-1D on PTB-XL diagnostic classes · FastAPI, OpenCV, Flutter</sub>

**[Zolts](https://github.com/Davmunrey/Zolts)** is a GTM operating system: signals become decisions, plays and revenue, measured against holdouts.<br>
<sub>In build · 10 company blueprints · Python 3.11, FastAPI, Postgres, Claude agents</sub>

**Atesta** keeps Spanish SMEs continuously ready for ENS and NIS2 audits: it connects to Microsoft 365 or Google Workspace read-only, scans daily and builds an auditor-ready evidence pack. ISO 27001, GDPR, DORA and SOC 2 follow as framework packs.<br>
<sub>In build · private repository</sub>

## Technical rules

Each one is written into one of my repositories as a project rule.

1. **Wired or it doesn't ship.** No delivered screen runs on mock data.
2. **Fail closed.** A failed read is an error, not an empty list. Permissions default to deny.
3. **Paid money doesn't move.** A settled payout in AEP Tarima freezes its amount and the referee's seat.
4. **Estimates are not outcomes.** Trazum keeps projected savings apart from measured ones, and `verify` checks a plan against later usage.
5. **One owner per fact.** Design tokens, copy, data and secrets each live in exactly one place.

## Contributing upstream

Fixes I send to other people's projects, held to their own review and CI. Merged means it landed; the rest is in review.

- **[REA: Reverse Engineer Anything](https://github.com/morluto/rea)** [![GitHub stars](https://img.shields.io/github/stars/morluto/rea?style=flat&color=gold)](https://github.com/morluto/rea) - Merged: settle a process exit in progress before reporting the process present ([#10620](https://github.com/morluto/rea/pull/10620)), and name Ghidra's declared-seed recovery when no function covers an address ([#10623](https://github.com/morluto/rea/pull/10623)). In review: .NET parameter defaults, Apple bundle placement, NES 2.0 headers, Ghidra, Kuna and Hopper providers, and JavaScript analysis. [All PRs](https://github.com/morluto/rea/pulls?q=is%3Apr+author%3ADavmunrey)
- **[gstack](https://github.com/garrytan/gstack)** [![GitHub stars](https://img.shields.io/github/stars/garrytan/gstack?style=flat&color=gold)](https://github.com/garrytan/gstack) - Merged: sixteen docs links reach their section again ([#4394](https://github.com/garrytan/gstack/pull/4394)). In review: the docs link check reads code fences as CommonMark does, and gstack-issue-links names the right commit and skips review trailers. [All PRs](https://github.com/garrytan/gstack/pulls?q=is%3Apr+author%3ADavmunrey)
- **[Univer](https://github.com/dream-num/univer)** [![GitHub stars](https://img.shields.io/github/stars/dream-num/univer?style=flat&color=gold)](https://github.com/dream-num/univer) - In review: Excel compatibility in formulas (UNICODE and UNICHAR above U+FFFF), filters (case and `~` wildcards), number validation, conditional formatting (bottom N, duplicates) and sorting. [All PRs](https://github.com/dream-num/univer/pulls?q=is%3Apr+author%3ADavmunrey)

## Your door

- **Investing or co-founding:** read the [Zolts plan](https://github.com/Davmunrey/Zolts), then [message me](https://www.linkedin.com/in/davmunrey).
- **Need a system built:** open [AEP Tarima](https://aep-tarima.vercel.app) or [Propel](https://propeltech.io), the bar I build to, then [message me](https://www.linkedin.com/in/davmunrey).
- **Writing code:** run `npx @trazum/cli bill` and [open an issue](https://github.com/Davmunrey/Trazum/issues) with what it got wrong.
- **Hiring:** the attempts above are the CV. [LinkedIn](https://www.linkedin.com/in/davmunrey) has the rest.

<details>
<summary>Also shipped</summary>

- [Proposal Engine](https://github.com/MunozRey/Proposal-Engine): proposal studio for CreditCheck with live preview, PDF, HTML and DOCX export in six languages.
- [CreditCheck Dashboard](https://github.com/Davmunrey/CreditCheck-Dashboard): lead scoring and insights for CreditCheck.

</details>
