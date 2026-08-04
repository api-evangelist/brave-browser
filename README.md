# Brave (brave-browser)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Brave Software builds a privacy-first Chromium-based browser, an independent search engine (Brave Search), an in-browser AI assistant (Leo), a video conferencing product (Brave Talk), an opt-in attention economy (Brave Rewards / Basic Attention Token), a wallet (Brave Wallet), and a privacy advertising platform (Brave Ads). Developer-facing APIs are concentrated in the Brave Search API (api.search.brave.com), which exposes web, news, image, video, suggest, spellcheck, summarizer, and local POI endpoints authenticated via X-Subscription-Token. Browser code is open source under MPL-2.0 on GitHub.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/brave-browser/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/brave-browser/refs/heads/main/apis.yml)

## Tags

- Browser
- Search
- Privacy
- Chromium
- Web3
- AI
- Advertising

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Brave Browser

Privacy-first Chromium-based browser for Windows, macOS, Linux, Android, and iOS, with built-in tracker and ad blocking (Brave Shields), HTTPS upgrades, Global Privacy Control, and a Tor-enabled private window on desktop. Open source under MPL-2.0.

- **Human URL:** [https://brave.com/](https://brave.com/)
- **Base URL:** `https://github.com/brave/brave-browser`

#### Tags

- Browser
- Chromium
- Open Source

#### Properties

- [Repository](https://github.com/brave/brave-browser)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Search

Independent privacy-respecting web search engine backed by Brave's own index. Surfaces the consumer product at search.brave.com and powers the Brave Search API.

- **Human URL:** [https://search.brave.com/](https://search.brave.com/)
- **Base URL:** `https://search.brave.com/`

#### Tags

- Search
- Web

#### Properties

- [Website](https://search.brave.com/)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Search API - Web Search

REST endpoint for general web search results with country, language, safe-search, and freshness filtering. Authenticated via X-Subscription-Token header.

- **Human URL:** [https://api-dashboard.search.brave.com/app/documentation](https://api-dashboard.search.brave.com/app/documentation)
- **Base URL:** `https://api.search.brave.com/res/v1/web/search`

#### Tags

- Search API
- Web Search

#### Properties

- [Documentation](https://api-dashboard.search.brave.com/app/documentation)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Search API - Image Search

Image search endpoint returning images with metadata, thumbnails, and SafeSearch filtering.

- **Human URL:** [https://api-dashboard.search.brave.com/app/documentation](https://api-dashboard.search.brave.com/app/documentation)
- **Base URL:** `https://api.search.brave.com/res/v1/images/search`

#### Tags

- Search API
- Image Search

#### Properties

- [Documentation](https://api-dashboard.search.brave.com/app/documentation)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Search API - Video Search

Video search endpoint returning videos with thumbnails, duration, and source metadata.

- **Human URL:** [https://api-dashboard.search.brave.com/app/documentation](https://api-dashboard.search.brave.com/app/documentation)
- **Base URL:** `https://api.search.brave.com/res/v1/videos/search`

#### Tags

- Search API
- Video Search

#### Properties

- [Documentation](https://api-dashboard.search.brave.com/app/documentation)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Search API - News Search

Real-time news search endpoint returning articles from trusted sources with freshness filtering.

- **Human URL:** [https://api-dashboard.search.brave.com/app/documentation](https://api-dashboard.search.brave.com/app/documentation)
- **Base URL:** `https://api.search.brave.com/res/v1/news/search`

#### Tags

- Search API
- News

#### Properties

- [Documentation](https://api-dashboard.search.brave.com/app/documentation)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Search API - Suggest

Autosuggest endpoint that returns query completions for a partial input.

- **Human URL:** [https://api-dashboard.search.brave.com/app/documentation](https://api-dashboard.search.brave.com/app/documentation)
- **Base URL:** `https://api.search.brave.com/res/v1/suggest/search`

#### Tags

- Search API
- Autosuggest

#### Properties

- [Documentation](https://api-dashboard.search.brave.com/app/documentation)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Search API - Spellcheck

Spelling correction endpoint for refining noisy or misspelled user queries.

- **Human URL:** [https://api-dashboard.search.brave.com/app/documentation](https://api-dashboard.search.brave.com/app/documentation)
- **Base URL:** `https://api.search.brave.com/res/v1/spellcheck/search`

#### Tags

- Search API
- Spellcheck

#### Properties

- [Documentation](https://api-dashboard.search.brave.com/app/documentation)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Search API - Summarizer

AI summarizer endpoint that condenses search results into a generated summary for use in agentic and AI-grounded applications.

- **Human URL:** [https://api-dashboard.search.brave.com/app/documentation](https://api-dashboard.search.brave.com/app/documentation)
- **Base URL:** `https://api.search.brave.com/res/v1/summarizer/search`

#### Tags

- Search API
- Summarizer
- AI

#### Properties

- [Documentation](https://api-dashboard.search.brave.com/app/documentation)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Search API - Local POIs

Local search endpoint returning point-of-interest details given IDs surfaced by web search results.

- **Human URL:** [https://api-dashboard.search.brave.com/app/documentation](https://api-dashboard.search.brave.com/app/documentation)
- **Base URL:** `https://api.search.brave.com/res/v1/local/pois`

#### Tags

- Search API
- Local
- POI

#### Properties

- [Documentation](https://api-dashboard.search.brave.com/app/documentation)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Search API - Local Descriptions

AI-generated descriptions for local points of interest, complementing the Local POIs endpoint.

- **Human URL:** [https://api-dashboard.search.brave.com/app/documentation](https://api-dashboard.search.brave.com/app/documentation)
- **Base URL:** `https://api.search.brave.com/res/v1/local/descriptions`

#### Tags

- Search API
- Local
- AI

#### Properties

- [Documentation](https://api-dashboard.search.brave.com/app/documentation)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Search MCP Server

Model Context Protocol server wrapping the Brave Search API so AI agents can ground answers in real-time web results.

- **Human URL:** [https://github.com/brave/brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server)
- **Base URL:** `https://github.com/brave/brave-search-mcp-server`

#### Tags

- MCP
- AI
- Search

#### Properties

- [Repository](https://github.com/brave/brave-search-mcp-server)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Leo AI

In-browser AI assistant offering chat, summarization, translation, and content generation grounded in the page or tab the user is viewing. Surfaced inside the browser; not a public REST API.

- **Human URL:** [https://brave.com/leo/](https://brave.com/leo/)
- **Base URL:** `https://brave.com/leo/`

#### Tags

- AI
- Assistant

#### Properties

- [Website](https://brave.com/leo/)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Talk

End-to-end encrypted video conferencing product, available free with premium tier for larger meetings.

- **Human URL:** [https://brave.com/talk/](https://brave.com/talk/)
- **Base URL:** `https://talk.brave.com/`

#### Tags

- Video
- Conferencing

#### Properties

- [Website](https://brave.com/talk/)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Rewards

Opt-in attention rewards program paying users in Basic Attention Token (BAT) for viewing privacy-preserving ads, and enabling tipping of verified creators.

- **Human URL:** [https://brave.com/rewards/](https://brave.com/rewards/)
- **Base URL:** `https://brave.com/rewards/`

#### Tags

- Rewards
- BAT
- Web3

#### Properties

- [Website](https://brave.com/rewards/)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Ads

Privacy-respecting advertising platform for advertisers that targets anonymized cohorts inside the Brave browser and on Brave Search.

- **Human URL:** [https://brave.com/brave-ads/](https://brave.com/brave-ads/)
- **Base URL:** `https://brave.com/brave-ads/`

#### Tags

- Advertising
- Privacy

#### Properties

- [Website](https://brave.com/brave-ads/)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Brave Wallet

Native multi-chain crypto wallet built into the Brave browser. Supports EVM and Solana networks; integrates with WalletConnect and dApps.

- **Human URL:** [https://brave.com/wallet/](https://brave.com/wallet/)
- **Base URL:** `https://brave.com/wallet/`

#### Tags

- Wallet
- Web3

#### Properties

- [Website](https://brave.com/wallet/)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)


#### Tags

- News
- Content

#### Properties

- [Website](https://brave.com/brave-news/)
- [Postman Collection](collections/brave-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brave-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://brave.com/)
- [Search](https://search.brave.com/)
- [Documentation](https://api-dashboard.search.brave.com/app/documentation)
- [Git Hub](https://github.com/brave)
- [LinkedIn](https://www.linkedin.com/company/brave-software-)
- [Twitter](https://twitter.com/brave)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
