# Brave (brave-browser)

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

### Brave News

Privacy-preserving news feed integrated into the browser's new tab page, sourced from a curated set of publisher feeds.

- **Human URL:** [https://brave.com/brave-news/](https://brave.com/brave-news/)
- **Base URL:** `https://brave.com/brave-news/`

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
