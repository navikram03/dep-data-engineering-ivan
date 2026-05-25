# Week 6 — Alternate Ingestion Paths (⚡ 3-Path Branching)

**Phase 2 — Data Collection &nbsp;|&nbsp; Milestone 2**

---

## This Week's Focus

Complete your ingestion method. Choose the path that fits your data source.

**Topics:**

- HTML structure, BeautifulSoup basics
- Extracting tables, links, and text
- Respect `robots.txt` / responsible scraping
- Cleaning strings during extraction
- When to use scraping vs manual download vs APIs
- Manual path: timestamped filenames + source URL log
- Timestamping raw files for reproducibility

---

## Resources

**Primary:** [Beautiful Soup Documentation](https://crummy.com/software/BeautifulSoup/bs4/doc)

**Optional:** [Real Python — Practical Intro to Web Scraping](https://realpython.com/python-web-scraping-practical-introduction)

---

## Task

Choose your ingestion path and complete it:

- **Path A — API:** Harden `ingest.py` with error handling and retries
- **Path B — Scraping:** Build a scraper that lands data in `/data/raw/`
- **Path C — Manual download:** Document timestamped raw save + source log

All three paths must produce the same output: a raw file in `/data/raw/` with a documented source URL and date.

---

## Deliverable

Alternative ingestion method documented and working.

**Milestone 2 — Data Ingestion Script** — submit this week.

**Estimated time:** 4–5 hours
