# Monitoring The Situation

A curated index of open-source projects for building **situational awareness, geopolitical monitoring, and information-fusion dashboards** — the kind you'd expect to see in a control room, ops center, or newsroom video wall.

**Last Updated:** April 2026

## Scope

Most "dashboard" repos on GitHub fall into one of two buckets: infra/metrics visualisation (Grafana, Prometheus) or pure geovisualisation (maps, event plots), plus a long tail of generic RSS readers. This index deliberately excludes those and focuses on projects that sit at the **fusion** of news/OSINT content and visual situational-awareness layouts:

- Composite news dashboards (RSS / Atom / IPTV tiles, news grids)
- Geopolitical / crisis monitoring dashboards with map + feed overlays
- Video-wall / kiosk-friendly layouts with auto-rotation and alerting
- Threat-intel and OSINT platforms where the UI is part of the product
- Dashboard frameworks well-suited to building the above

Nice-to-haves that show up across the list: push/telegram alerts, IPTV/news-channel tiles, multi-source feed aggregation, and tileable/gridstack layouts.

**Not in scope:** generic APM/metrics dashboards, pure-map geovis libraries, or single-source RSS readers without a fusion angle.

---

## Table of Contents

- [Situational Awareness & Geopol Dashboards](#situational-awareness--geopol-dashboards)
- [Threat Intel & OSINT Platforms](#threat-intel--osint-platforms)
- [News Grids & Composite Feed Dashboards](#news-grids--composite-feed-dashboards)
- [Data Sources & Ingestion](#data-sources--ingestion)
- [Dashboard Frameworks & Admin Panels](#dashboard-frameworks--admin-panels)
- [UI Kits & Layout Primitives](#ui-kits--layout-primitives)
- [Common Operational Picture (COP)](#common-operational-picture-cop)

---

## Situational Awareness & Geopol Dashboards

Projects whose primary purpose is visualising a *situation* — typically combining news feeds, maps, and event tickers for ops-center / video-wall consumption.

### situational-awareness-dashboard

Geopolitical situational-awareness dashboard combining news, events, and map views.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/ErikVeland/situational-awareness-dashboard)

### situation-monitor (hipcityreg)

Live situation monitor aggregating news and events for at-a-glance awareness.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/hipcityreg/situation-monitor)

### situation-monitor (nikankad)

Alternate situation-monitor implementation — multi-feed news/event dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/nikankad/situation-monitor)

### situation-monitor (gabob23)

Another situation-monitor fork/variant — worth comparing against the others.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/gabob23/situation-monitor)

### worldmonitor

World-events monitoring dashboard with news and map layers.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/koala73/worldmonitor)

### worldview

Global news / world-view dashboard aggregating geopolitical signals.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Prathewsh/worldview)

### globalpulse

Global-pulse dashboard for world news and events.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/ntamero/globalpulse)

### radar

Geopolitical radar / situation dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Syntax-Error-1337/radar)

### Neuberg

Situational-awareness / geopolitical monitoring project.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/KoNananachan/Neuberg)

### NexaView

Multi-panel situational-awareness view.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Temavrix/NexaView)

### perception-with-intent

Intent-oriented perception / situational awareness dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/intent-solutions-io/perception-with-intent)

### deepscope

Deep situational-awareness scope / monitoring tool.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Countiblader/deepscope)

### sigint

SIGINT-style situational-awareness dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/iiTONELOC/sigint)

### missile-dashboard

Specialised conflict/missile-event monitoring dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/blcrosbie/missile-dashboard)

### Iran Conflict Dashboard

Targeted conflict dashboard — useful as a pattern for scoped geopol dashboards.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/SecondOrderEdge/Iran_Conflict_Dashboard)

### Sovereign Watch

Sovereign / geopolitical watch dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/d3mocide/Sovereign_Watch)

### blossom-terminal

Terminal-style situational-awareness / intel display.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/zakirkun/blossom-terminal)

---

## Threat Intel & OSINT Platforms

Larger platforms where the UI is a core part of the product — typically ingesting structured intel from many connectors.

### OpenCTI

Open-source Cyber Threat Intelligence platform — graph-based entity/event model with a rich web UI. Widely used as a backbone for intel fusion.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/OpenCTI-Platform/opencti)

### OpenCTI Connectors

Official connector library for OpenCTI — the ingestion side that feeds the dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/OpenCTI-Platform/connectors)

---

## News Grids & Composite Feed Dashboards

Tileable news-grid UIs and composite feed readers — the video-wall archetype.

### newsdash

Tileable news dashboard — drag-and-drop grid of RSS feeds, designed for kiosk-style viewing.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/buzz/newsdash)

### NewsAI

AI-augmented news aggregation dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Multiverse-of-Projects/NewsAI)

### news-dash

News dashboard with tiled feeds.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Tejeswar001/news-dash)

### Global News Intel Platform

News-intel dashboard combining feeds with analysis.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Mohith-akash/Global-News-Intel-Platform)

### news-alert

News-alerting dashboard with push/notification angle.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/tbrown034/news-alert)

---

## Data Sources & Ingestion

Feeds and ingestion layers — the raw material for any fusion dashboard.

### GDELT PyR

Python client for the GDELT global events database — the canonical source for machine-coded geopolitical events.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/linwoodc3/gdeltPyR)

### Folo (follow)

Next-generation feed reader and aggregator — a strong base if you want a modern RSS/Atom core.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/RSSNext/Folo)

### RSS-Bridge

Generates RSS feeds from sites that don't expose them — essential for bridging arbitrary news sources into a dashboard.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/RSS-Bridge/rss-bridge)

### changedetection.io

Watches web pages for changes and emits feeds/notifications — useful for scraping non-feed sources into a monitoring pipeline.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/dgtlmoon/changedetection.io)

### news-fetch

Python library for fetching and parsing news articles at scale.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/santhoshse7en/news-fetch)

### iptv-org/iptv

Curated IPTV channel lists — the canonical source for embedding live news channels (BBC World, Al Jazeera, France 24, etc.) as video tiles in a wall.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/iptv-org/iptv)

---

## Dashboard Frameworks & Admin Panels

General-purpose low-code / admin-panel frameworks that are well-suited to building a situational-awareness UI without starting from scratch. None are geopol-specific, but several are pragmatic foundations.

### Appsmith

Low-code internal-tools builder — widgets, data sources, dashboards.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/appsmithorg/appsmith)

### ToolJet

Open-source low-code platform for building internal dashboards and tools.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/ToolJet/ToolJet)

### ILLA Builder

Low-code dashboard/app builder alternative to Retool.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/illacloud/illa-builder)

### Redash

Query-and-visualise data dashboard — SQL-first, good for data panels inside a larger wall.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/getredash/redash)

### Plotly Dash

Python framework for building analytical web apps and dashboards — strong for custom data panels.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/plotly/dash)

### H2O Wave

Realtime Python web-app framework for ML/analytics dashboards.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/h2oai/wave)

### Vizro

McKinsey's low-code Plotly framework for production dashboards.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/mckinsey/vizro)

### Chartbrew

Open-source charting/dashboard tool — connects to APIs and databases.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/chartbrew/chartbrew)

### Refine

React meta-framework for admin panels, dashboards, and internal tools.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/refinedev/refine)

### Orchid Platform

Laravel admin/dashboard platform.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/orchidsoftware/platform)

### Administrate

Rails admin/dashboard framework by thoughtbot.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/thoughtbot/administrate)

### Gatus

Status/health dashboard — useful as an uptime panel inside a larger wall.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/TwiN/gatus)

### ARES

Multi-panel dashboard project — included as a design reference.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/moonsterr/ARES)

---

## UI Kits & Layout Primitives

Component libraries and layout engines that directly solve the video-wall / tile-grid problem.

### gridstack.js

Drag-and-drop responsive grid layout — the canonical JS primitive for tileable dashboards.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/gridstack/gridstack.js)

### Tabler

Clean, modern open-source dashboard UI kit built on Bootstrap.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/tabler/tabler)

### Ant Design Pro

Enterprise-class React dashboard scaffold built on Ant Design.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/ant-design/ant-design-pro)

### Blueprint

Palantir's React UI toolkit — purpose-built for data-dense, complex interfaces.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/palantir/blueprint)

### shadcn-admin

Shadcn/ui-based admin dashboard template.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/satnaing/shadcn-admin)

### Next Shadcn Dashboard Starter

Next.js + shadcn/ui dashboard starter.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Kiranism/next-shadcn-dashboard-starter)

### Vuestic Admin

Vue 3 admin/dashboard template.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/epicmaxco/vuestic-admin)

### Art Design Pro

Vue 3 admin dashboard template.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Daymychen/art-design-pro)

### Adminator

Responsive HTML admin dashboard template.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/puikinsh/Adminator-admin-dashboard)

---

## Common Operational Picture (COP)

Projects explicitly framed as COP / shared-ops-picture tools — the doctrinal term for the kind of fusion wall this index is about.

### UKSFTA-COP

UK Special Forces Task Association common-operational-picture project.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/UKSFTA/UKSFTA-COP)

---

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
