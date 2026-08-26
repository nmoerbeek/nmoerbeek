## Noah Moerbeek

**Full-stack .NET engineer.** I build and maintain the software a city runs on: business
licensing, permitting, and pet licensing systems used by municipal governments across
California, Washington, Nevada and beyond. Roughly 50 public-sector clients.

Most of what I do is the unglamorous, high-stakes half of software: making a 15-year-old
ASP.NET Web Forms application talk to a modern REST API, moving a production database
between clouds without losing a row, and getting a legacy system to pass a WCAG 2.1 AA
audit before a statutory deadline.

### What I work on

**Legacy modernization.** Incremental migration of ASP.NET Web Forms (.NET Framework 4.8)
to Blazor on .NET 8. Strangler-fig approach, shared authentication, no big-bang rewrite.

**Enterprise integrations.** Tyler EnerGov permitting APIs, CyberSource and Authorize.Net
payment gateways, Microsoft Graph, Zendesk, GoTo. OAuth 2.0 authorization-code + PKCE,
token refresh, and credential storage that does not end up in source control.

**Accessibility.** WCAG 2.1 AA remediation across a large Web Forms and Blazor surface:
focus management through partial postbacks, ARIA live regions, keyboard parity, and the
documentation trail auditors actually ask for.

**Cloud and infrastructure.** Azure (SQL, Functions, Key Vault, NSGs, ARM RunCommand) and
AWS (Lightsail, Route 53, S3). Automated DTU autoscaling, key-based fleet access,
cross-region backup replication, and compliance evidence: CloudTrail, SQL auditing, DR
tabletop exercises.

### Stack

`C#` `.NET 8` `Blazor (WASM + Server)` `ASP.NET Core` `ASP.NET Web Forms` `Java` `Spring`
`T-SQL` `SQL Server` `Azure SQL` `SQLite` `PowerShell` `Python` `TypeScript`
`Azure` `AWS` `Playwright` `xUnit`

### Selected work

**[Latin Diurnale Trainer](https://github.com/nmoerbeek/LatinPractice)** - Blazor
WebAssembly. An IXL-style adaptive skill tree for learning to read the day hours of the
Roman Breviary in Latin. 976 tokens glossed with lemma and morphology, 94 skills, 2,172
generated questions, 65 tests. Source text diffed against a reference edition to catch
transcription errors. [Live demo](https://nmoerbeek.github.io/LatinPractice/)

> Most of my production work lives in private repositories owned by my employer. Happy to
> walk through architecture and decisions in conversation.

### Contact

- Twitter/X: [@NoahMoerbeek](https://twitter.com/NoahMoerbeek)
- LinkedIn: [noah-moerbeek](https://www.linkedin.com/in/noah-moerbeek-72ba469/)
- Email: [nmoerbeek@gmail.com](mailto:nmoerbeek@gmail.com)
