# The Liberating River™ Content Catalog

This repository contains the public content catalog for **The Liberating River™ Podcast**.

It is part of the **Creator Content Operating System (CCOS Method™)** — a structured system designed to organize, classify, and distribute content across platforms.

---

## What This Repository Contains

- `TLR_Catalog.csv`  
  A continuously updated dataset of all content including:

  - Podcast Episodes (Audio + Video)
  - YouTube Shorts (The Book of Flo)
  - Podcast Clips
  - Special Videos

---

## How This Works

This catalog is automatically generated and maintained through an internal system:

**Content Sources**
- YouTube (Videos + Shorts)
- Podbean (Podcast Audio)

↓ ingestion + normalization

**Content Intelligence Layer**
- Structured classification (Format, Series, Media Type, etc.)

↓ automation

**Data Transport Layer**
- GitHub Actions (automated updates)

↓ distribution

**Public Interface**
- Website catalog (Squarespace integration)

---

## Update Frequency

The catalog is updated automatically via GitHub Actions.

---

## Column Structure

| Column | Description |
|------|--------|
| Title | Content title |
| Publish Date | Original publish date |
| Format | Content type (Podcast Video, Short, Audio, etc.) |
| Media Type | Longform / Shortform / Clip |
| Series | Content series (e.g. The Liberating River, The Book of Flo) |
| Month | Derived publish month |
| Episode Number | Podcast episode number (if applicable) |
| Episode Part | Episode part (if applicable) |
| Primary Link | Main content link |
| YouTube URL | YouTube version |
| Duration | Content duration |
| Podbean Link | Podcast page |
| Podbean Embeddable Link | Audio player source |
| Video ID | YouTube video identifier |

---

## Purpose

This repository exists to:

- Provide a structured, machine-readable catalog of content
- Power the public website experience
- Enable filtering, discovery, and reuse of content
- Serve as the distribution layer of the CCOS Method™

---

## About

**The Liberating River™** is a podcast exploring:

- Spiritual alignment
- Wealth and financial awareness
- Identity, decision-making, and personal clarity

---

## Built With

- Python (Playwright scraping + processing)
- GitHub Actions (automation)
- CSV-based catalog system
- Notion (internal intelligence layer)
- Squarespace (frontend display)

---

## Maintained By

LiberatingLiving, LLC  
https://www.LiberatingLiving.com

---

## Note

This repository is part of a larger proprietary system (CCOS Method™).  
The structure and automation are designed for scalability and multi-platform distribution.
