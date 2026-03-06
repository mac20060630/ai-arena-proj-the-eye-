# The eye

> **Real-time geopolitical intelligence dashboard using ai** — live conflict tracking, threat analysis, and global situational awareness in one unified interface.

---

## About the Project

**World Monitor** is an open-source, real-time global intelligence dashboard that aggregates live data from dozens of authoritative sources — conflicts, cyber threats, nuclear sites, internet outages, natural events, and more — and presents them on an interactive 3D globe. It provides analysts, researchers, journalists, and curious citizens with a single pane of glass for understanding what's happening across the world *right now*.

The platform layers structured geopolitical intelligence (conflict zones, Iran strike tracking, intel hotspot signals) with live feeds from defense publications, think tanks, and OSINT sources — all driven by real data, with no manual curation required.

---

## Problem Statement

In an era of information overload, understanding the global geopolitical landscape is increasingly difficult:

- **Fragmented sources**: Critical intelligence is spread across hundreds of news outlets, government feeds, defense journals, and live data APIs — requiring analysts to switch between dozens of tabs.
- **No real-time spatial context**: Reading a headline about a conflict gives no immediate sense of its geography, proximity to other flashpoints, or relationship to broader regional patterns.
- **High barrier to situational awareness**: Building a coherent picture of global events requires expertise, time, and access to expensive subscription services.
- **Signal vs. noise**: Most news aggregators surface the same mainstream stories, burying high-value intelligence signals from OSINT, defense analysts, and think tanks.

---

## Proposed Solution

World Monitor solves this by providing a **unified, real-time intelligence platform** that:

- **Centralises live data** from 50+ authoritative sources — Defense One, Bellingcat, RAND, USNI News, NASA EONET, IODA (internet outages), and more — into a single dashboard.
- **Maps every signal geospatially** on an interactive WebGL globe (powered by Deck.gl + MapLibre), giving instant spatial context to every event.
- **Curates high-signal layers** — including live Iran strike tracking, AI-powered intel hotspots, cyber threat overlays, nuclear site positions, and real-time trade route/waterway monitoring.
- **Streams live news** from Sky News, CNBC, and Euro News alongside curated intel feeds from defense publications and OSINT sources.
- **Runs in real time** — data auto-refreshes, the clock ticks in IST, and every layer updates without requiring a page reload.
