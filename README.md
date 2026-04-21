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

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
