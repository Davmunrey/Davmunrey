### Hi there 👋

I'm **David Muñoz Rey**, a founder-engineer based in Spain 🇪🇸. I build products end to end, and I fix bugs in the open-source projects I rely on.

#### What I do

- 🛠️ **Building [Trazum](https://github.com/Davmunrey/Trazum)**: an open-source CLI and MCP server that prices AI agent and API usage locally, per call
- 📈 **Building [Propel](https://propeltech.io)**: an AI-native CRM for outbound sales
- 🏋️ **Running [AEP Tarima](https://aep-tarima.vercel.app)**: the platform the Spanish Powerlifting Association's referees work in: championships, rosters, payouts, rules and exams ([source](https://github.com/Davmunrey/AEP-Referee-APP))
- 🔓 **Contributing to open source**: [Prowler](https://github.com/prowler-cloud/prowler), [Univer](https://github.com/dream-num/univer), [REA](https://github.com/morluto/rea) and [gstack](https://github.com/garrytan/gstack)

#### Current focus

- ENS (RD 311/2022) in Prowler: Microsoft 365 with SharePoint, Exchange and Teams, and catalog fixes for AWS, Azure and GCP, all merged
- Knowing what AI agents cost before the invoice arrives
- Excel parity in Univer: formulas, sorting, filters, validation
- Reverse engineering in REA, and its Spanish website

#### Open-source contributions

Merged upstream, newest first within each project.

**[Prowler](https://github.com/prowler-cloud/prowler)**
- [#13408](https://github.com/prowler-cloud/prowler/pull/13408), [#13411](https://github.com/prowler-cloud/prowler/pull/13411), [#13409](https://github.com/prowler-cloud/prowler/pull/13409): ENS for Microsoft 365 adds the SharePoint Online, Exchange Online and Teams requirements of CCN-STIC-885B, 885C and 885D
- [#13413](https://github.com/prowler-cloud/prowler/pull/13413): ENS for Microsoft 365 follows the May 2024 edition of CCN-STIC-885A
- [#13417](https://github.com/prowler-cloud/prowler/pull/13417), [#13419](https://github.com/prowler-cloud/prowler/pull/13419), [#13421](https://github.com/prowler-cloud/prowler/pull/13421): correct execution modes, groups, categories and requirement ids in ENS for AWS, Azure and GCP
- [#13423](https://github.com/prowler-cloud/prowler/pull/13423): the ENS PDF report colours the execution mode badge of automated requirements
- [#13430](https://github.com/prowler-cloud/prowler/pull/13430): the local dashboard's compliance sections stay visible without Dash's dev tools
- [#13402](https://github.com/prowler-cloud/prowler/pull/13402): compliance CSVs list each manual requirement once, however many batches the findings arrive in
- [#13394](https://github.com/prowler-cloud/prowler/pull/13394): ENS RD 311/2022 compliance framework for Microsoft 365, with CLI, API and PDF report support

**[Univer](https://github.com/dream-num/univer)**
- [#8237](https://github.com/dream-num/univer/pull/8237): conditional formatting text rules compare case-insensitively, Greek final sigma included
- [#8233](https://github.com/dream-num/univer/pull/8233): TRIM removes only the space character, as Excel does
- [#8312](https://github.com/dream-num/univer/pull/8312): AMORDEGRC evaluates as Excel does, checked against 23,042 results computed in Excel
- [#8238](https://github.com/dream-num/univer/pull/8238): list validation accepts entries that differ from an option only in case
- [#8302](https://github.com/dream-num/univer/pull/8302): EUROCONVERT converts between the euro and its legacy currencies instead of returning `#NAME?`
- [#8243](https://github.com/dream-num/univer/pull/8243): XLOOKUP and XMATCH read `?` and `*` literally outside wildcard mode
- [#8232](https://github.com/dream-num/univer/pull/8232): SEARCH and SEARCHB read `?` and `*` as wildcards
- [#8245](https://github.com/dream-num/univer/pull/8245): ISO.CEILING evaluates instead of returning `#NAME?`
- [#8246](https://github.com/dream-num/univer/pull/8246): EDATE and EOMONTH truncate fractional months toward zero
- [#8210](https://github.com/dream-num/univer/pull/8210): UNICODE and UNICHAR read and build code points above U+FFFF
- [#8216](https://github.com/dream-num/univer/pull/8216): bottom N conditional formatting highlights every number when N exceeds the count
- [#8215](https://github.com/dream-num/univer/pull/8215): number validation reads only decimal numeric text as a number
- [#8217](https://github.com/dream-num/univer/pull/8217): duplicate and unique value rules compare text case-insensitively
- [In review](https://github.com/dream-num/univer/pulls?q=is%3Apr+is%3Aopen+author%3ADavmunrey): locale-aware sorting, case-insensitive text in filters, and wildcard escapes

**[REA](https://github.com/morluto/rea)**
- [#10681](https://github.com/morluto/rea/pull/10681): queue JavaScript binding initializers once per ambient alias
- [#12104](https://github.com/morluto/rea/pull/12104): fix two Spanish strings flagged in review
- [#12103](https://github.com/morluto/rea/pull/12103): review the Spanish guides, case studies and blog
- [#12092](https://github.com/morluto/rea/pull/12092): complete the Spanish edition of the website, 63 untranslated messages
- [#10686](https://github.com/morluto/rea/pull/10686): Kuna stops calling data sections in executable segments definite data
- [#12089](https://github.com/morluto/rea/pull/12089): classify 64-bit PowerPC ELF files in the PowerPC family, so providers decline them by name
- [#12091](https://github.com/morluto/rea/pull/12091): cleanup tests count a killed descendant that awaits reaping as stopped
- [#12082](https://github.com/morluto/rea/pull/12082): read the Authenticode signatures of dual-signed Windows binaries
- [#10683](https://github.com/morluto/rea/pull/10683): name the unsupported Thumb mode when a raw ARM entry address is odd
- [#10663](https://github.com/morluto/rea/pull/10663): Inspector tests spell Node discovery targets the way Node reports them
- [#10679](https://github.com/morluto/rea/pull/10679): reject Android invoke coverage that arrives without its site evidence
- [#10620](https://github.com/morluto/rea/pull/10620): settle an observed exit before reporting a process present
- [#10623](https://github.com/morluto/rea/pull/10623): name the declared-seed recovery when no function covers an address
- [In review](https://github.com/morluto/rea/pulls?q=is%3Apr+is%3Aopen+author%3ADavmunrey): .NET parameter defaults, Apple bundle placement, NES 2.0 headers, Expo Router routes, a Hindi edition of the README, and fixes across Ghidra, JavaScript and the Inspector

**[gstack](https://github.com/garrytan/gstack)**
- [#4394](https://github.com/garrytan/gstack/pull/4394): sixteen documentation links reach their section again
- [In review](https://github.com/garrytan/gstack/pulls?q=is%3Apr+is%3Aopen+author%3ADavmunrey): issue-link fixes and code-fence handling in the docs link check

[All merged](https://github.com/search?type=pullrequests&q=is%3Apr%20is%3Amerged%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey) · [In review](https://github.com/search?type=pullrequests&q=is%3Apr%20is%3Aopen%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey) · [Issues reported](https://github.com/search?type=issues&q=is%3Aissue%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey)

<details>
<summary>Also built</summary>

- [Proposal Engine](https://github.com/MunozRey/Proposal-Engine): proposal studio with live preview and PDF, HTML and DOCX export in six languages
- [CreditCheck Dashboard](https://github.com/Davmunrey/CreditCheck-Dashboard): lead scoring and insights for CreditCheck

</details>

#### Let's connect

[LinkedIn](https://www.linkedin.com/in/davmunrey) · [Trazum on npm](https://www.npmjs.com/package/@trazum/cli)
