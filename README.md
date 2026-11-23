### Hi there 👋

I'm **David Muñoz Rey**, a founder-engineer based in Spain 🇪🇸. I build products end to end, and I fix bugs in the open-source projects I rely on.

#### What I do

- 🛠️ **Building [Trazum](https://github.com/TrazumAPP/Trazum)**: an open-source CLI and MCP server that prices AI agent and API usage locally, per call
- 📈 **Building [Propel](https://propeltech.io)**: an AI-native CRM for outbound sales
- 🏋️ **Running [AEP Tarima](https://aep-tarima.vercel.app)**: the platform the Spanish Powerlifting Association's referees work in: championships, rosters, payouts, rules and exams ([source](https://github.com/Davmunrey/AEP-Referee-APP))
- 🔓 **Contributing to open source**: [Prowler](https://github.com/prowler-cloud/prowler), [Univer](https://github.com/dream-num/univer), [REA](https://github.com/morluto/rea), [gstack](https://github.com/garrytan/gstack) and [Plane](https://github.com/makeplane/plane)

#### Current focus

- ENS (RD 311/2022) in Prowler: Microsoft 365 with SharePoint, Exchange and Teams is merged; AWS, Azure and GCP are in review, aligned with their CCN-STIC guides
- Knowing what AI agents cost before the invoice arrives
- Excel parity in Univer: formulas, sorting, filters, validation
- Reverse engineering in REA, and its Spanish website

#### Open-source contributions

What I've shipped upstream, project by project.

**[Prowler](https://github.com/prowler-cloud/prowler)** · [merged](https://github.com/prowler-cloud/prowler/pulls?q=is%3Apr+is%3Amerged+author%3ADavmunrey) · [in review](https://github.com/prowler-cloud/prowler/pulls?q=is%3Apr+is%3Aopen+author%3ADavmunrey)<br>
Brought Spain's National Security Framework (ENS, RD 311/2022) to Microsoft 365: a new compliance framework with CLI, API and PDF report support that follows the CCN-STIC-885A guide and adds the SharePoint Online, Exchange Online and Teams requirements of 885B, 885C and 885D. Corrected requirement ids, groups and execution modes in the ENS catalogs for AWS, Azure and GCP, fixed how compliance CSVs, the ENS PDF report and the local dashboard present results, and made the AWS SNS, Service Catalog and IAM services read every page of their listings. In review: ENS for AWS, Azure and GCP aligned with their CCN-STIC guides.

**[Univer](https://github.com/dream-num/univer)** · [merged](https://github.com/dream-num/univer/pulls?q=is%3Apr+is%3Amerged+author%3ADavmunrey) · [in review](https://github.com/dream-num/univer/pulls?q=is%3Apr+is%3Aopen+author%3ADavmunrey)<br>
Brought Univer's formulas and rules closer to Excel. AMORDEGRC, EUROCONVERT and ISO.CEILING now evaluate instead of returning `#NAME?`, with AMORDEGRC checked against 23,042 results computed in Excel; SEARCH, SEARCHB, XLOOKUP and XMATCH read `?` and `*` the way Excel does; and TRIM, EDATE, EOMONTH, UNICODE and UNICHAR return Excel's results. Conditional formatting and data validation compare text case-insensitively, Greek final sigma included, and handle Excel's edge cases in number validation and bottom N rules. In review: locale-aware sorting, case-insensitive filters and wildcard escapes.

**[REA](https://github.com/morluto/rea)** · [merged](https://github.com/morluto/rea/pulls?q=is%3Apr+is%3Amerged+author%3ADavmunrey) · [in review](https://github.com/morluto/rea/pulls?q=is%3Apr+is%3Aopen+author%3ADavmunrey)<br>
Widened what REA can analyze: 64-bit PowerPC executables through Ghidra, NES 2.0 ROM containers, Expo Router routes and dual-signed Windows binaries. Fixed findings across Ghidra, Kuna, Android, Apple bundles, ARM entry points, JavaScript analysis and process handling, so results say what could not be recovered instead of overstating it, and made several tests reliable. Completed and reviewed the Spanish edition of the rea.tools website. In review: .NET parameter defaults, Apple bundle placement, a Hindi README, and fixes in macOS setup and tests.

**[gstack](https://github.com/garrytan/gstack)** · [merged](https://github.com/garrytan/gstack/pulls?q=is%3Apr+is%3Amerged+author%3ADavmunrey) · co-authored [#4677](https://github.com/garrytan/gstack/pull/4677) and [#4672](https://github.com/garrytan/gstack/pull/4672)<br>
Fixed sixteen documentation links that pointed to missing sections. The maintainer batches that landed my other fixes credit me as co-author: the docs link check reads code fences as CommonMark does, the bootstrap tests pass when run as root, and `gstack-issue-links` labels each issue mention with the commit it comes from.

**[Plane](https://github.com/makeplane/plane)** · [merged](https://github.com/makeplane/plane/pulls?q=is%3Apr+is%3Amerged+author%3ADavmunrey)<br>
Improved Plane's translations: the settings sidebar headings now read in 16 more languages, the Sticky brand mark stays untranslated in Spanish, French, Italian and Portuguese, and GitLab and plane.so are spelled correctly in every locale. I also reported that the Spanish interface mixed *tú* and *usted*; the maintainers' fix, which includes my commit for the last 19 strings, is in review.

[All merged](https://github.com/search?type=pullrequests&q=is%3Apr%20is%3Amerged%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey%20-user%3ATrazumAPP) · [In review](https://github.com/search?type=pullrequests&q=is%3Apr%20is%3Aopen%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey%20-user%3ATrazumAPP) · [Issues reported](https://github.com/search?type=issues&q=is%3Aissue%20author%3ADavmunrey%20-user%3ADavmunrey%20-user%3AMunozRey%20-user%3ATrazumAPP)

<details>
<summary>Also built</summary>

- [Proposal Engine](https://github.com/MunozRey/Proposal-Engine): proposal studio with live preview and PDF, HTML and DOCX export in six languages
- [CreditCheck Dashboard](https://github.com/Davmunrey/CreditCheck-Dashboard): lead scoring and insights for CreditCheck

</details>

#### Let's connect

[LinkedIn](https://www.linkedin.com/in/davmunrey) · [Trazum on npm](https://www.npmjs.com/package/@trazum/cli)
