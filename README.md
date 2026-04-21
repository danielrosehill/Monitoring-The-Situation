# Monitoring The Situation

A curated index of open-source projects for building **command-center style news monitoring dashboards** — the kind you'd see in a government watch-floor, newsroom video wall, or crisis ops center tracking breaking events rather than server metrics.

**Last Updated:** April 2026

## Scope

The focus is narrow on purpose. Most "dashboard" repos on GitHub are either server/metrics dashboards (Grafana, APM) or homelab tile-boards showing weather + service status. This index excludes those and instead collects projects useful for building dashboards that **fuse newswires, social chatter, RSS/Atom, OSINT, and geopolitical event data** into a single situational picture.

**In scope:**
- Situational-awareness / geopolitical monitoring dashboards (frontend)
- News grids and composite feed dashboards (tiled RSS + IPTV + social)
- Information-fusion / OSINT / threat-intel platforms (backend)
- RSS / feed aggregation backends, bridging, and deduplication
- AI analysis layers for news clustering, entity extraction, and summarisation
- Dashboard frameworks and UI primitives genuinely suited to news video walls
- Digital-signage CMSes and kiosk/remote-management tooling
- Push / notification plumbing

**Out of scope:**
- Generic metrics / APM / infra dashboards (Grafana, Prometheus, Kibana)
- Homelab / server-status / service-launcher tile boards (Dashy, Homer, Homepage, Flame, Organizr, MagicMirror)
- Broad geospatial libraries without a news/event angle
- Exhaustive data-source catalogues — this isn't an OSINT link farm

---

## Table of Contents

**Frontend / Display Layer**
- [Situational Awareness & Geopol Dashboards](#situational-awareness--geopol-dashboards)
- [Hosted Live Situational Dashboards](#hosted-live-situational-dashboards)
- [News Grids & Composite Feed Dashboards](#news-grids--composite-feed-dashboards)
- [Dashboard Frameworks for Custom Builds](#dashboard-frameworks-for-custom-builds)
- [UI Kits & Layout Primitives](#ui-kits--layout-primitives)

**Backend / Fusion Layer**
- [Threat Intel & Information-Fusion Platforms](#threat-intel--information-fusion-platforms)
- [Crisis & Citizen-Report Platforms](#crisis--citizen-report-platforms)
- [RSS / Feed Aggregation Backends](#rss--feed-aggregation-backends)
- [Feed Synthesis & Bridging](#feed-synthesis--bridging)
- [News Extraction, Clustering & Deduplication](#news-extraction-clustering--deduplication)
- [AI Analysis Layers](#ai-analysis-layers)
- [Notifications & Push](#notifications--push)

**Display Infrastructure**
- [Digital Signage CMS (Self-Hostable)](#digital-signage-cms-self-hostable)
- [Kiosk Mode & Remote Device Management](#kiosk-mode--remote-device-management)
- [Live TV / IPTV Tiles](#live-tv--iptv-tiles)
- [Common Operational Picture (COP)](#common-operational-picture-cop)

**Commercial / SaaS Reference Stack**
- [Newswires & Primary Feeds](#newswires--primary-feeds)
- [Real-Time Event Detection (Gov / Newsroom Grade)](#real-time-event-detection-gov--newsroom-grade)
- [Media Monitoring & PR Intelligence](#media-monitoring--pr-intelligence)
- [Social Listening & Narrative Analytics](#social-listening--narrative-analytics)
- [Broadcast / TV Monitoring](#broadcast--tv-monitoring)
- [OSINT & Intel Fusion Platforms](#osint--intel-fusion-platforms)
- [Crisis & Duty-of-Care Intelligence](#crisis--duty-of-care-intelligence)
- [Geospatial & Satellite Layers](#geospatial--satellite-layers)
- [Video Wall / Control Room Hardware & CMS](#video-wall--control-room-hardware--cms)
- [Commercial Digital Signage](#commercial-digital-signage)
- [Mass Notification / Alerting](#mass-notification--alerting)

---

# Frontend / Display Layer

## Situational Awareness & Geopol Dashboards

Projects whose primary purpose is visualising a *situation* — typically combining news, events, and map views for ops-center / video-wall consumption.

### blossom-terminal

Terminal-style situational-awareness / intel display.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/zakirkun/blossom-terminal)

### deepscope

Deep situational-awareness scope / monitoring tool.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Countiblader/deepscope)

### globalpulse

Global-pulse dashboard for world news and events.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/ntamero/globalpulse)

### Iran Conflict Dashboard

Targeted conflict dashboard — useful as a pattern for scoped, event-specific geopol dashboards.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/SecondOrderEdge/Iran_Conflict_Dashboard)

### missile-dashboard

Specialised conflict / missile-event monitoring dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/blcrosbie/missile-dashboard)

### Neuberg

Situational-awareness / geopolitical monitoring project.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/KoNananachan/Neuberg)

### NexaView

Multi-panel situational-awareness view.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Temavrix/NexaView)

### perception-with-intent

Intent-oriented perception / situational-awareness dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/intent-solutions-io/perception-with-intent)

### radar

Geopolitical radar / situation dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Syntax-Error-1337/radar)

### sigint

SIGINT-style situational-awareness dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/iiTONELOC/sigint)

### situation-monitor (gabob23)

Situation-monitor variant — worth comparing side-by-side with the other forks in this section.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/gabob23/situation-monitor)

### situation-monitor (hipcityreg)

Live situation monitor aggregating news and events for at-a-glance awareness.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/hipcityreg/situation-monitor)

### situation-monitor (nikankad)

Alternate situation-monitor implementation.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/nikankad/situation-monitor)

### situational-awareness-dashboard

Geopolitical situational-awareness dashboard combining news, events, and map views.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/ErikVeland/situational-awareness-dashboard)

### Sovereign Watch

Sovereign / geopolitical watch dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/d3mocide/Sovereign_Watch)

### worldmonitor

World-events monitoring dashboard with news and map layers.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/koala73/worldmonitor)

### worldview

Global news / world-view dashboard aggregating geopolitical signals.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Prathewsh/worldview)

---

## Hosted Live Situational Dashboards

Free / open-access live dashboards already running in production — not GitHub repos but worth indexing here as reference implementations of the "what a watch-floor tile actually looks like" archetype. Many are OSINT-positioned, aggregate public feeds (news, flight/AIS, prediction markets, sentiment), and refresh on short intervals. Useful as design references and as live tiles to embed in your own wall.

### SitDeck

Broad OSINT situational-awareness dashboard — 180+ data feeds and 55+ widgets spanning conflicts, earthquakes, and markets. Freemium with AI-analyst tiers.

[![View Site](https://img.shields.io/badge/View-Site-green?style=flat)](https://sitdeck.com/)

### MediaThrive WatchTower

Real-time global news-intelligence dashboard pitched at newsrooms — breaking news, conflicts, markets, and cyber threats in one view.

[![View Site](https://img.shields.io/badge/View-Site-green?style=flat)](https://mediathrive.com/watchtower)

### World Monitor

Multilingual OSINT dashboard fusing news, markets, military / flight / AIS tracking, infrastructure, and geopolitical data. BYOK AI; Pro tier on waitlist.

[![View Site](https://img.shields.io/badge/View-Site-green?style=flat)](https://www.worldmonitor.app/)

### Iran Monitor (iranmonitor.org)

Iran-focused OSINT dashboard — news sentiment, X/Twitter feeds, flight radar, prediction markets, internet-connectivity metrics.

[![View Site](https://img.shields.io/badge/View-Site-green?style=flat)](https://www.iranmonitor.org/)

### StrikeRadar

Single-purpose risk gauge estimating US-strike-on-Iran probability from news, aviation, tankers, Polymarket, and the Pentagon Pizza Meter. 30-min refresh — a clean example of a one-question dashboard.

[![View Site](https://img.shields.io/badge/View-Site-green?style=flat)](https://usstrikeradar.com/)

### US-Iran Live

Iran–US conflict news-aggregation dashboard with live map; tracks sanctions, nuclear, and military developments. ~3-minute refresh.

[![View Site](https://img.shields.io/badge/View-Site-green?style=flat)](https://usairanlive.com/)

### IranWarRoom

Iran-conflict intelligence dashboard with vessel/aircraft tracking, defense-stock data, news feeds, and AI threat analysis. Multilingual, ad-supported.

[![View Site](https://img.shields.io/badge/View-Site-green?style=flat)](https://iranwarroom.com/)

### MissileStrikes

US–Israel–Iran missile-conflict dashboard — 17 tabs covering strike map, interceptor burn rates, arsenals, cost ratios, and supply-chain analytics.

[![View Site](https://img.shields.io/badge/View-Site-green?style=flat)](https://missilestrikes.com/ar/)

### Iran Monitor (iranmonitor.online)

Independent Iran OSINT dashboard built on Base44 — news sentiment, X feeds, flight radar, prediction markets, internet connectivity.

[![View Site](https://img.shields.io/badge/View-Site-green?style=flat)](https://iranmonitor.online/)

---

## News Grids & Composite Feed Dashboards

Tileable news-grid UIs and composite feed readers — the video-wall archetype.

### Global News Intel Platform

News-intel dashboard combining feeds with analysis layers.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Mohith-akash/Global-News-Intel-Platform)

### news-alert

News-alerting dashboard with a push/notification angle.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/tbrown034/news-alert)

### news-dash

News dashboard with tiled feeds.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Tejeswar001/news-dash)

### NewsAI

AI-augmented news aggregation dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Multiverse-of-Projects/NewsAI)

### newsdash

Tileable news dashboard — drag-and-drop grid of RSS feeds, designed for kiosk-style viewing. One of the clearest examples of the video-wall archetype.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/buzz/newsdash)

---

## Dashboard Frameworks for Custom Builds

Low-code and Python/JS frameworks useful when you're building a bespoke command-center UI rather than forking an existing project. General-purpose admin-panel frameworks have been deliberately trimmed — only the ones that map well onto event/feed-driven UIs are listed.

### Appsmith

Low-code internal-tools builder — widgets, data sources, custom dashboards.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/appsmithorg/appsmith)

### H2O Wave

Realtime Python web-app framework — event-driven, well-suited to live news panels.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/h2oai/wave)

### ILLA Builder

Low-code dashboard/app builder — Retool alternative.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/illacloud/illa-builder)

### Plotly Dash

Python framework for analytical web apps — strong for custom data panels alongside news tiles.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/plotly/dash)

### Refine

React meta-framework for admin panels and internal tools — flexible enough for custom command-center UIs.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/refinedev/refine)

### ToolJet

Open-source low-code platform for building internal dashboards.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/ToolJet/ToolJet)

### Vizro

McKinsey's low-code Plotly framework for production dashboards.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/mckinsey/vizro)

---

## UI Kits & Layout Primitives

Component libraries and layout engines that directly solve the video-wall / tile-grid problem.

### Blueprint

Palantir's React UI toolkit — purpose-built for data-dense, complex interfaces.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/palantir/blueprint)

### gridstack.js

Drag-and-drop responsive grid layout — the canonical JS primitive for tileable dashboards.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/gridstack/gridstack.js)

### Tabler

Clean, modern open-source dashboard UI kit — useful as a scaffold.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/tabler/tabler)

---

# Backend / Fusion Layer

## Threat Intel & Information-Fusion Platforms

Heavyweight platforms where the UI is part of the product — ingest structured and unstructured intel from many connectors and present it as a queryable picture.

### MediaCloud

Open-source platform for studying media ecosystems at scale — news ingestion, topic detection, source analysis. The most serious OSS project for media-monitoring backends.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/mediacloud)

### OpenCTI

Open-source Cyber Threat Intelligence platform — graph-based entity/event model with a rich web UI. Widely used as a backbone for intel fusion.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/OpenCTI-Platform/opencti)

### OpenCTI Connectors

Official connector library for OpenCTI — the ingestion side that feeds the dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/OpenCTI-Platform/connectors)

### SpiderFoot

OSINT automation platform — 200+ modules for footprinting, threat intel, and surface monitoring.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/smicallef/spiderfoot)

---

## Crisis & Citizen-Report Platforms

Purpose-built for fusing citizen reports, SMS, and newswires during crises — the doctrinal ancestors of modern news-monitoring dashboards.

### Sahana Eden

Humanitarian / disaster management platform with incident tracking, resource mapping, and situation reporting.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/sahana/eden)

### Ushahidi Platform

The canonical crisis-mapping platform — fuses citizen reports, social posts, and news onto a map. Used across election monitoring and disaster response.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/ushahidi/platform)

---

## RSS / Feed Aggregation Backends

Self-hostable feed servers — the plumbing beneath any news wall. Pick one as the canonical feed store, then render tiles against its API.

### CommaFeed

Self-hostable Google Reader-style aggregator (Java).

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Athou/commafeed)

### Folo

Next-generation feed reader and aggregator — modern UI, strong RSS/Atom core, useful as a base for feed-heavy apps.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/RSSNext/Folo)

### FreshRSS

Self-hosted RSS feed aggregator with a mature API — a common backend for custom feed UIs.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/FreshRSS/FreshRSS)

### Miniflux

Minimalist, performant self-hosted feed reader (Go) — clean API, good fit as a headless feed backend behind a custom wall.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/miniflux/v2)

### Selfoss

Multi-source aggregator — RSS, Twitter, and custom plugins merged into a unified stream.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/fossar/selfoss)

### Stringer

Anti-social, self-hosted RSS reader — simple Rails backend.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/swanson/stringer)

### yarr

Lightweight single-binary feed aggregator with a JSON API.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/nkanaev/yarr)

---

## Feed Synthesis & Bridging

Turn arbitrary web sources (sites without feeds, social posts, change-detection events) into consumable RSS/Atom that a feed backend can swallow. Essential for fusion.

### changedetection.io

Watches web pages for changes and emits feeds / webhooks — useful for non-feed sources that still need to appear on the wall.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/dgtlmoon/changedetection.io)

### RSS-Bridge

Generates RSS feeds from sites that don't expose them — essential glue for bridging arbitrary news sources into a dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/RSS-Bridge/rss-bridge)

### RSSHub

Everything-is-RSSable. Thousands of routes that convert social media, video, forums, and niche sites into RSS — the most powerful bridging layer for fusion dashboards.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/DIYgod/RSSHub)

---

## News Extraction, Clustering & Deduplication

Ingested feeds are noisy and duplicative. These libraries extract clean article content and collapse near-duplicate stories into single events — table-stakes for a serious news wall.

### datasketch

MinHash, LSH, HyperLogLog — the standard toolkit for near-duplicate detection over article text.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/ekzhu/datasketch)

### dedupe

Library for fuzzy matching, record linkage, and entity resolution — pair with article extraction to cluster stories across outlets.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/dedupeio/dedupe)

### newspaper3k

Python library for article extraction, NLP, and metadata — lightweight, widely used.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/codelucas/newspaper)

### news-please

End-to-end news crawler and extractor with structured output — the backbone for many news-monitoring pipelines.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/fhamborg/news-please)

### news-fetch

Python library for fetching and parsing news articles at scale.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/santhoshse7en/news-fetch)

---

## AI Analysis Layers

LLM / NLP layers that sit between raw ingestion and the display — entity extraction, geocoding, summarisation, topic clustering, and agentic research over the stream.

### Flair

Easy-to-use NLP framework with strong NER — good for extracting people, places, and organisations from news text.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/flairNLP/flair)

### GPT Researcher

Agentic research framework — give it a topic and it synthesises across sources, useful as an on-demand briefing layer over a news feed.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/assafelovic/gpt-researcher)

### Haystack

Production-grade framework for retrieval, RAG, and NLP pipelines — well-suited to semantic search and summarisation over a news corpus.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/deepset-ai/haystack)

### Perplexica

Open-source AI search engine — pair with your feed store to get AI-synthesised answers grounded in ingested news.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/ItzCrazyKns/Perplexica)

### Stanza

Stanford NLP toolkit — multilingual NER, parsing, and tokenisation, relevant where feeds span languages.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/stanfordnlp/stanza)

### txtai

All-in-one embeddings database — semantic search, clustering, and LLM workflows over text.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/neuml/txtai)

---

## Notifications & Push

Push-notification plumbing — a common "nice to have" for command-center dashboards that need to alert operators off-screen.

### Apprise

Unified notification library — one API, 90+ destinations (Telegram, Slack, Signal, SMS, push services).

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/caronc/apprise)

### Gotify

Self-hosted push notification server with mobile apps.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/gotify/server)

### ntfy

Self-hosted pub/sub push service — HTTP PUT/POST to send, mobile and CLI subscribers.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/binwiederhier/ntfy)

---

# Display Infrastructure

## Digital Signage CMS (Self-Hostable)

Dedicated digital-signage platforms — the right shape when a news wall needs to run 24/7 on dedicated displays with scheduled content, zones, and remote updates.

### Anthias

Formerly Screenly OSE — the original Raspberry Pi digital-signage OSS. Good baseline for single-display walls.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Screenly/Anthias)

### Concerto

University-origin signage platform — multi-screen, scheduled content zones.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/concerto/concerto)

### Xibo

The most feature-complete open-source digital-signage CMS — multi-zone layouts, scheduling, player management. Well-suited to news-wall deployments with many tiled regions.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/xibosignage/xibo-cms)

---

## Kiosk Mode & Remote Device Management

Running a dashboard on a wall-mounted display reliably is its own problem. These tools handle the kiosk OS, unattended boot, browser lockdown, and fleet-style remote management.

### balena

Container-based OS and fleet management for edge devices — widely used to deploy and remotely manage kiosk/signage displays.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/balena-io)

### Cog

Minimal single-"window" launcher built on WPE WebKit — the production choice for embedded/kiosk web rendering.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Igalia/cog)

### FullPageOS

Raspberry Pi OS image that boots directly into a fullscreen Chromium kiosk — the fastest path to a dedicated dashboard display.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/guysoft/FullPageOS)

---

## Live TV / IPTV Tiles

Embedding live news channels (BBC World, Al Jazeera, France 24, CNN International) as video tiles is a defining feature of real command-center walls.

### iptv-org/iptv

The canonical curated IPTV channel list — the source for live-TV tiles in a news wall.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/iptv-org/iptv)

---

## Common Operational Picture (COP)

Projects explicitly framed as COP / shared-ops-picture tools — the doctrinal term for the kind of fusion wall this index is about.

### UKSFTA-COP

UK Special Forces Task Association common-operational-picture project.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/UKSFTA/UKSFTA-COP)

---

# Commercial / SaaS Reference Stack

Everything above is open-source. But if you walked onto a foreign-ministry watch floor, a major-network newsroom, a corporate Global Security Operations Center (GSOC), or an NGO crisis cell, the screens would mostly be driven by **proprietary SaaS** — because the valuable bit is the licensed content (newswires, broadcast feeds, social firehose access) and the real-time event-detection models trained on it, not the UI.

This section catalogues the commercial layer so the OSS index above can be read as "what you'd self-build or augment with" rather than "what a professional shop actually uses end-to-end." Inclusion is descriptive, not endorsement; pricing is typically enterprise-quote and access often gated by sector (gov, Fortune 500, accredited media).

## Newswires & Primary Feeds

The licensed source material that ultimately populates most of the tiles. Direct ingestion (via API / NITF / NewsML / RSS with auth) is common on gov and newsroom walls.

- **[Reuters Connect](https://www.reutersagency.com/en/reuters-connect/)** — Reuters' modern delivery platform; text, video, pictures, graphics, plus partner agencies.
- **[Associated Press (AP) Newsroom / AP Hub](https://www.ap.org/)** — AP's wire, photo, and video delivery; deep penetration in US newsrooms and embassies.
- **[Agence France-Presse (AFP)](https://www.afp.com/en/agency/afp-services)** — AFP Forum / ImageForum; strong on global and francophone coverage.
- **[Bloomberg Terminal](https://www.bloomberg.com/professional/products/bloomberg-terminal/)** — The canonical financial-intel terminal; BN wire, TOPLive, and chat are heavily used by policy and markets desks.
- **[Dow Jones Newswires / Factiva](https://www.dowjones.com/professional/factiva/)** — Real-time wires plus Factiva's licensed archive of ~33,000 sources.
- **[LexisNexis Nexis Newsdesk](https://www.lexisnexis.com/en-us/professional/media-monitoring/nexis-newsdesk.page)** — Licensed news archive + real-time monitoring, common in gov / legal / policy shops.
- **[EBU News Exchange](https://www.ebu.ch/news-exchange)** — European Broadcasting Union's video-news exchange; a backbone feed for public broadcasters.
- **[Kyodo News](https://english.kyodonews.net/)**, **[Xinhua](http://www.xinhuanet.com/english/)**, **[TASS](https://tass.com/)** — Regional wires that watch-floors subscribe to for source-country framing.

## Real-Time Event Detection (Gov / Newsroom Grade)

First-alert products that sit *in front of* the wires — they ingest social, dark web, sensor, and wire data and surface breaking events with minutes-to-hours of lead time. This is the category where newsrooms and gov ops centers spend serious money.

- **[Dataminr Pulse / First Alert](https://www.dataminr.com/)** — The market leader for real-time alerting from public data. First Alert is the public-sector/news SKU; Pulse is the corporate-risk SKU. De facto standard on network-news assignment desks and many watch floors.
- **[Factal](https://www.factal.com/)** — Editor-verified breaking-event feed built for multinationals, NGOs, and newsrooms; strong signal-to-noise.
- **[Samdesk](https://samdesk.io/)** — AI-driven crisis detection from social; widely used by airlines, resorts, and corporate security.
- **[NewsWhip Spike](https://www.newswhip.com/)** — Predictive engagement signal — surfaces which stories are about to go viral, not just which are trending.
- **[Signal AI](https://www.signal-ai.com/)** — "Decision augmentation" platform; media + regulatory + reputational monitoring with entity graphs.
- **[Liferaft Navigator](https://liferaftinc.com/)** — OSINT / threat monitoring aimed at corporate GSOCs.

## Media Monitoring & PR Intelligence

The PR/comms-facing monitoring stack. Overlaps with the categories above but is explicitly framed around earned-media measurement, sentiment, and share of voice.

- **[Meltwater](https://www.meltwater.com/)** — Broad media intelligence suite — news, social, broadcast, influencer.
- **[Cision](https://www.cision.com/) / [CisionOne](https://www.cision.com/products/cisionone/)** — Monitoring + media database + distribution; heavyweight in corporate comms.
- **[Onclusive](https://onclusive.com/)** — Formed from Kantar Reputation Intelligence, PRgloo, and Critical Mention; full-stack PR analytics.
- **[Muck Rack](https://muckrack.com/)** — Journalist-database-first monitoring; strong with modern PR teams.
- **[Agility PR Solutions](https://www.agilitypr.com/)** — Mid-market monitoring + outreach.
- **[Notified (formerly PR Newswire)](https://www.notified.com/)** — Distribution + monitoring + IR comms.
- **[CARMA](https://carma.com/)** — Human-coded media analysis — still common where nuance/sentiment accuracy matters more than throughput.

## Social Listening & Narrative Analytics

Firehose-grade social monitoring — what watch floors use to track narratives, disinfo, and on-the-ground sentiment.

- **[Brandwatch (Cision)](https://www.brandwatch.com/)** — Consumer research + crisis + influencer; one of the two dominant players.
- **[Talkwalker (Hootsuite)](https://www.talkwalker.com/)** — The other one; strong image/video recognition and broadcast integration.
- **[Sprinklr Insights](https://www.sprinklr.com/products/insights/)** — Unified CX/social platform; used at enterprise scale.
- **[Meltwater Social (ex-Sysomos / Linkfluence)](https://www.meltwater.com/en/products/social-media-monitoring)** — Social tier of the Meltwater suite.
- **[Synthesio (Ipsos)](https://www.synthesio.com/)** — Research-oriented social listening.
- **[Pulsar](https://www.pulsarplatform.com/)** — Audience intelligence and narrative tracking; popular with comms strategy teams.
- **[NewsWhip](https://www.newswhip.com/)** — Listed again here for its cross-platform virality scoring.
- **[Graphika](https://www.graphika.com/)** — Network-graph analysis of online communities; used heavily on influence-operations work.
- **[Logically](https://www.logically.ai/)**, **[Blackbird.AI](https://www.blackbird.ai/)**, **[Alethea](https://www.alethea.com/)** — Disinfo / narrative-threat platforms — the "CT for information ops" tier, common in MFA and election-integrity contexts.

## Broadcast / TV Monitoring

Watching linear TV and radio is still a first-class requirement on any serious watch floor; these services index broadcast with ASR + OCR and expose clip search + alerts.

- **[TVEyes](https://tveyes.com/)** — The standard broadcast-monitoring service — searchable TV/radio transcripts across thousands of channels, real-time alerts, clip export.
- **[Critical Mention (Onclusive)](https://www.criticalmention.com/)** — Broadcast monitoring + earned-media analytics.
- **[SnapStream](https://www.snapstream.com/)** — On-prem/hybrid TV recording + search; used in newsrooms and political war rooms.
- **[Kantar Media](https://www.kantarmedia.com/)** — Broadcast intelligence at agency scale.

## OSINT & Intel Fusion Platforms

The commercial analogues to OpenCTI / MediaCloud — full fusion stacks, often ITAR-tier or gov-restricted.

- **[Palantir Gotham / Foundry / MetaConstellation](https://www.palantir.com/)** — The archetype of a gov-grade intel-fusion platform; common across defence, MFA-equivalents, and homeland security.
- **[Recorded Future](https://www.recordedfuture.com/)** — Temporal analytics over open + dark + technical sources; widely deployed in CTI and geopolitical-risk functions.
- **[Babel Street](https://www.babelstreet.com/)** — Multilingual OSINT + identity intelligence; heavy LE and gov footprint.
- **[Flashpoint](https://flashpoint.io/)** — Deep/dark-web intel + physical security convergence.
- **[Fivecast](https://www.fivecast.com/)** — OSINT platform with risk scoring; used across Five Eyes.
- **[PenLink (formerly Cobwebs)](https://www.penlink.com/)** — Web-intelligence + lawful-intercept analytics.
- **[Echosec (Flashpoint)](https://www.echosec.net/)** — Geospatial social / dark-web search.
- **[ShadowDragon](https://shadowdragon.io/)** — OSINT tradecraft tooling — SocialNet, Horizon.
- **[Maltego](https://www.maltego.com/)** — Graph-based investigation platform; commercial tiers with TI transforms.
- **[GDELT (reference, free)](https://www.gdeltproject.org/)** — Not SaaS, but the default commercial-grade event dataset referenced by nearly every platform above.

## Crisis & Duty-of-Care Intelligence

The travel-risk / employee-safety / crisis-ops tier — overlaps with event detection but oriented around assets and people, not narratives.

- **[Everbridge Visual Command Center + Risk Intelligence (ex-NC4)](https://www.everbridge.com/)** — The reference platform for corporate GSOCs; fuses risk events with asset/personnel locations.
- **[Crisis24 (GardaWorld) Horizon](https://crisis24.garda.com/)** — Analyst-written intel + real-time alerts; ex-iJET / WorldAware / Drum Cussac lineage.
- **[International SOS TravelTracker / Tracker](https://www.internationalsos.com/)** — Medical + security duty-of-care standard.
- **[Riskline](https://www.riskline.com/)**, **[Sitata](https://www.sitata.com/)**, **[Safeture](https://safeture.com/)**, **[AlertMedia Global Intelligence](https://www.alertmedia.com/)** — Mid-market duty-of-care feeds and platforms.
- **[BlueDot](https://bluedot.global/)** — Epidemic / biological-event intelligence — called the 2019 Wuhan outbreak before WHO.
- **[Control Risks Seerist / CORE](https://www.controlrisks.com/)** — Geopolitical-risk advisory with a productised feed.

## Geospatial & Satellite Layers

The map layer behind every "where is this happening" tile.

- **[Esri ArcGIS Online / ArcGIS Dashboards](https://www.esri.com/en-us/arcgis/products/arcgis-dashboards/overview)** — The dominant gov GIS stack; most COVID-era public dashboards (JHU, many MoH sites) ran on it.
- **[Mapbox](https://www.mapbox.com/)** — Commercial map tiles + Studio; default for custom branded maps.
- **[Google Maps Platform](https://mapsplatform.google.com/)** — Ubiquitous embeds; Premium/Enterprise tier for higher quotas.
- **[HERE](https://www.here.com/)**, **[TomTom Orbis](https://www.tomtom.com/products/orbis-maps/)** — Gov- and automotive-grade mapping alternatives.
- **[Planet Labs](https://www.planet.com/)** — Daily-refresh satellite imagery — the standard reference for monitoring physical ground-truth.
- **[Maxar](https://www.maxar.com/)** — High-resolution commercial satellite imagery.
- **[BlackSky](https://www.blacksky.com/)**, **[ICEYE](https://www.iceye.com/)** — Rapid-revisit optical and SAR respectively; increasingly on watch-floor map layers.
- **[HawkEye 360](https://www.he360.com/)** — RF geolocation — emitter tracking as a commercial product.
- **[Dataminr × Planet / Maxar integrations]** — Increasingly the pattern: event-detection product calls out to imagery provider for confirmation tiles.

## Video Wall / Control Room Hardware & CMS

The physical "large screens" you asked to work back from are driven by a small number of specialist control-room vendors. A dashboard isn't a video wall until something is driving the pixels across N displays with failover.

- **[Userful](https://www.userful.com/)** — Software-defined video-wall / control-room platform — common in security and ops centers.
- **[VuWall](https://vuwall.com/)** — AV-over-IP video-wall management + KVM.
- **[Haivision](https://www.haivision.com/) (incl. CineMassive, Kraken)** — Mission-critical AV + low-latency streaming; deep gov/mil footprint.
- **[Barco TransForm N / CMS / UniSee](https://www.barco.com/en/control-rooms)** — LCD / LED video walls and the networked CMS behind them.
- **[Christie Phoenix / Spyder / Terra](https://www.christiedigital.com/products/control-rooms/)** — Projection + AV-over-IP for very large rooms.
- **[RGB Spectrum](https://www.rgb.com/)**, **[Datapath](https://www.datapath.co.uk/)**, **[Extron](https://www.extron.com/)**, **[Crestron](https://www.crestron.com/)** — Video-wall processors, capture cards, and control systems.
- **[Jupiter Systems (Planar)](https://www.jupiter.com/)** — Canvas / Pana — long-running video-wall CMS.

## Commercial Digital Signage

When the requirement is "N identical news walls, centrally managed" rather than a bespoke ops center.

- **[BrightSign](https://www.brightsign.biz/)** — Purpose-built signage players — the most deployed commercial endpoint.
- **[Scala (STRATACACHE)](https://scala.com/)** — Enterprise signage CMS.
- **[Navori](https://www.navori.com/)**, **[Signagelive](https://signagelive.com/)**, **[Yodeck](https://www.yodeck.com/)** — Mid-market signage CMS with RSS/news widgets.
- **[Poppulo (formerly Four Winds Interactive)](https://www.poppulo.com/)** — Internal-comms + signage platform, common in corporate lobbies and EOCs.
- **[Screenly (commercial)](https://www.screenly.io/)** — Hosted tier above the Anthias OSS lineage.

## Mass Notification / Alerting

When an event crosses a threshold on the wall, these platforms push it out to people.

- **[Everbridge Mass Notification](https://www.everbridge.com/products/mass-notification/)** — Gov + enterprise standard for multi-channel alerting; often the downstream of Visual Command Center.
- **[AlertMedia](https://www.alertmedia.com/)** — Modern employee-safety + mass-comms platform.
- **[OnSolve](https://www.onsolve.com/)** — Critical-event management (ex-CodeRED, Send Word Now).
- **[Rave Mobile Safety (Motorola)](https://www.ravemobilesafety.com/)** — Heavy in public sector / higher-ed.
- **[Regroup Mass Notification](https://www.regroup.com/)** — Mid-market alternative.

---

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
