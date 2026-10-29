# Brave

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Brave Software builds a privacy-first Chromium-based browser, an independent search engine (Brave Search), an in-browser AI assistant (Leo), a video conferencing product (Brave Talk), an opt-in attention economy (Brave Rewards / Basic Attention Token), a wallet (Brave Wallet), and a privacy advertising platform (Brave Ads). Developer-facing APIs are concentrated in the Brave Search API (api.search.brave.com), which exposes web, news, image, video, suggest, spellcheck, summarizer, and local POI endpoints authenticated via X-Subscription-Token. Browser code is open source under MPL-2.0 on GitHub.

**Areas:** Browser · Search · Privacy · Chromium · Web3 · Artificial Intelligence · Advertising

## Brave on APIs.io

Everything profiled for Brave is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/brave-browser/](https://apis.io/providers/brave-browser/)** — or go straight to one of the APIs or properties below.

### APIs (27)

- [Brave Browser](https://apis.io/apis/brave-browser/browser/) — Privacy-first Chromium-based browser for Windows, macOS, Linux, Android, and iOS, with built-in tracker and ad blocking (Brave Shields), HTTPS upgrades,…
- [Brave Search](https://apis.io/apis/brave-browser/search/) — Independent privacy-respecting web search engine backed by Brave's own index. Surfaces the consumer product at search.brave.com and powers the Brave Search API.
- [Brave Search API - Web Search](https://apis.io/apis/brave-browser/search-api-web/) — REST endpoint for general web search results with country, language, safe-search, and freshness filtering. Authenticated via X-Subscription-Token header.
- [Brave Search API - Image Search](https://apis.io/apis/brave-browser/search-api-images/) — Image search endpoint returning images with metadata, thumbnails, and SafeSearch filtering.
- [Brave Search API - Video Search](https://apis.io/apis/brave-browser/search-api-videos/) — Video search endpoint returning videos with thumbnails, duration, and source metadata.
- [Brave Search API - News Search](https://apis.io/apis/brave-browser/search-api-news/) — Real-time news search endpoint returning articles from trusted sources with freshness filtering.
- [Brave Search API - Suggest](https://apis.io/apis/brave-browser/search-api-suggest/) — Autosuggest endpoint that returns query completions for a partial input.
- [Brave Search API - Spellcheck](https://apis.io/apis/brave-browser/search-api-spellcheck/) — Spelling correction endpoint for refining noisy or misspelled user queries.
- [Brave Search API - Summarizer](https://apis.io/apis/brave-browser/search-api-summarizer/) — AI summarizer endpoint that condenses search results into a generated summary for use in agentic and AI-grounded applications.
- [Brave Search API - Local POIs](https://apis.io/apis/brave-browser/search-api-local-pois/) — Local search endpoint returning point-of-interest details given IDs surfaced by web search results.
- [Brave Search API - Local Descriptions](https://apis.io/apis/brave-browser/search-api-local-descriptions/) — AI-generated descriptions for local points of interest, complementing the Local POIs endpoint.
- [Brave Search MCP Server](https://apis.io/apis/brave-browser/search-mcp/) — Model Context Protocol server wrapping the Brave Search API so AI agents can ground answers in real-time web results.
- [Brave Leo AI](https://apis.io/apis/brave-browser/leo/) — In-browser AI assistant offering chat, summarization, translation, and content generation grounded in the page or tab the user is viewing. Surfaced inside…
- [Brave Talk](https://apis.io/apis/brave-browser/talk/) — End-to-end encrypted video conferencing product, available free with premium tier for larger meetings.
- [Brave Rewards](https://apis.io/apis/brave-browser/rewards/) — Opt-in attention rewards program paying users in Basic Attention Token (BAT) for viewing privacy-preserving ads, and enabling tipping of verified creators.
- [Brave Ads](https://apis.io/apis/brave-browser/ads/) — Privacy-respecting advertising platform for advertisers that targets anonymized cohorts inside the Brave browser and on Brave Search.
- [Brave Wallet](https://apis.io/apis/brave-browser/wallet/) — Native multi-chain crypto wallet built into the Brave browser. Supports EVM and Solana networks; integrates with WalletConnect and dApps.
- [Brave Images API](https://apis.io/apis/brave-browser/brave-browser-images-api/) — The Images API from Brave — 1 operation(s) for images.
- [Brave Local API](https://apis.io/apis/brave-browser/brave-browser-local-api/) — The Local API from Brave — 2 operation(s) for local.
- [Brave News API](https://apis.io/apis/brave-browser/brave-browser-news-api/) — The News API from Brave — 1 operation(s) for news.
- [Brave Suggest API](https://apis.io/apis/brave-browser/brave-browser-suggest-api/) — The Suggest API from Brave — 1 operation(s) for suggest.
- [Brave Summarizer API](https://apis.io/apis/brave-browser/brave-browser-summarizer-api/) — The Summarizer API from Brave — 1 operation(s) for summarizer.
- [Brave Videos API](https://apis.io/apis/brave-browser/brave-browser-videos-api/) — The Videos API from Brave — 1 operation(s) for videos.
- [Brave Web API](https://apis.io/apis/brave-browser/brave-browser-web-api/) — The Web API from Brave — 1 operation(s) for web.
- [Brave News](https://apis.io/apis/brave-browser/news/) — Privacy-preserving news feed integrated into the browser's new tab page, sourced from a curated set of publisher feeds.
- [Brave Ads API](https://apis.io/apis/brave-browser/brave-ads-api/) — API for managing and reporting on Brave Ads campaigns. Enables advertisers to retrieve campaign details and performance data for privacy-preserving native…
- [Brave Spell Check API](https://apis.io/apis/brave-browser/brave-browser-spell-check-api/) — The Spell Check API from Brave — 1 operation(s) for spell check.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Brave Browser Agentic Access](https://apis.io/agentic-access/brave-browser/brave-browser-agentic-access/)

#### Collections (9)

Postman and Open Collection request collections.

- [Brave Search API](https://apis.io/collections/brave-browser/open-brave-browser/)
- [Brave Search Images API](https://apis.io/collections/brave-browser/open-brave-browser-images-api/)
- [Brave Search Images Local API](https://apis.io/collections/brave-browser/open-brave-browser-local-api/)
- [Brave Search Images News API](https://apis.io/collections/brave-browser/open-brave-browser-news-api/)
- [Brave Search Images Spellcheck API](https://apis.io/collections/brave-browser/open-brave-browser-spellcheck-api/)
- [Brave Search Images Suggest API](https://apis.io/collections/brave-browser/open-brave-browser-suggest-api/)
- [Brave Search Images Summarizer API](https://apis.io/collections/brave-browser/open-brave-browser-summarizer-api/)
- [Brave Search Images Videos API](https://apis.io/collections/brave-browser/open-brave-browser-videos-api/)
- [Brave Search Images Web API](https://apis.io/collections/brave-browser/open-brave-browser-web-api/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Brave Browser Authentication](https://apis.io/security/brave-browser/brave-browser-authentication/)
- [Brave Browser Domain Security](https://apis.io/security/brave-browser/brave-browser-domain-security/)
- [Brave Browser Vulnerability Disclosure](https://apis.io/security/brave-browser/brave-browser-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Brave Browser Plans Pricing](https://apis.io/plans/brave-browser/brave-browser-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Brave Browser Rate Limits](https://apis.io/rate-limits/brave-browser/brave-browser-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Brave Browser Finops](https://apis.io/finops/brave-browser/brave-browser-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://brave.com/)
- [Documentation](https://api-dashboard.search.brave.com/app/documentation)
- [Pricing](https://ads.brave.com/)
- [Blog](https://brave.com/blog/index.xml)

## API Evangelist rating

**Kin Score 31.5** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 46.7 |
| Contract governance | 0.0 |
| Operational transparency | 36.8 |
| Developer ergonomics | 23.8 |
| Access clarity | 21.1 |

**Agent readiness 22.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/brave-browser/](https://apis.io/providers/brave-browser/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Brave: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/brave-browser/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
