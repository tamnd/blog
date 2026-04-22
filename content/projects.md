+++
title = "Projects"
menu = "main"
weight = 4
+++

A tour of things I've built — mostly open source, mostly on [GitHub](https://github.com/tamnd).

## Docs & learning indexes

Browsable catalogs generated from primary sources. Each one takes a messy, sprawling corpus and turns it into something you can actually navigate.

- **[mdn-index](https://github.com/tamnd/mdn-index)** — ★14. A complete index of all 14,000+ articles on MDN Web Docs, organized by technology.
- **[godev-index](https://github.com/tamnd/godev-index)** — ★8. A curated guide to everything on go.dev, organized for learners and practitioners.
- **[kernel-index](https://github.com/tamnd/kernel-index)** — ★6. Hand-curated index of every documentation page in the Linux kernel. 1,393 pages across 56 sections.
- **[cmu-database-group-videos-index](https://github.com/tamnd/cmu-database-group-videos-index)** — ★7. Every lecture and talk from the CMU Database Group YouTube channel. 585 videos, 35 playlists, 11 years of database systems education.
- **[dbdb-index](https://github.com/tamnd/dbdb-index)** — ★2. Every DBMS on dbdb.io, indexed. 1,071 systems with stats, charts, and full metadata.
- **[hn-daily-index](https://github.com/tamnd/hn-daily-index)** — ★2. Daily archive of the top 10 Hacker News stories, organized by date.
- **[3blue1brown-index](https://github.com/tamnd/3blue1brown-index)** — Every 3Blue1Brown video. 179 videos, 608M+ total views. Math, physics, and CS through stunning animations.
- **[khanacademy-index](https://github.com/tamnd/khanacademy-index)** — 4,400+ Khan Academy videos across math, science, computing, and more.
- **[awesome-index](https://github.com/tamnd/awesome-index)** — Auto-generated enriched index of `sindresorhus/awesome` with stars, last-update dates, commit counts.
- **[wstg-index](https://github.com/tamnd/wstg-index)** — OWASP Web Security Testing Guide, rendered from the official `checklist.json`.
- **[mastg-index](https://github.com/tamnd/mastg-index)** — OWASP Mobile Application Security Testing Guide, organized by MASVS control groups.
- **[go-scp-index](https://github.com/tamnd/go-scp-index)** — OWASP Go Secure Coding Practices Guide with chapter descriptions and Go code examples.

## Python runtime, written in Go

Trying to reach the CPython runtime from Go without linking libpython.

- **[goipy](https://github.com/tamnd/goipy)** — ★2. Pure-Go CPython 3.14 bytecode interpreter. Runs `.pyc` files without cgo or an embedded CPython.
- **[gopygo](https://github.com/tamnd/gopygo)** — Transpiles CPython 3.14 `.pyc` files into standalone Go programs.

## Data & systems

- **[hn-fdw](https://github.com/tamnd/hn-fdw)** — ★4. Query the full Hacker News archive from Postgres via `duckdb_fdw`, with zero copies. Row groups stream straight from the Hugging Face Parquet dataset on demand.

## Vietnamese translations

Technical documentation in Vietnamese. Most of these are living projects — pinned upstream, translated in the open.

**Beej's Guides** — Vietnamese versions of Beej Jorgensen's widely-loved programming guides.

- **[bgnet-vi](https://github.com/tamnd/bgnet-vi)** — ★2. Guide to Network Programming.
- **[bgc-vi](https://github.com/tamnd/bgc-vi)** — ★1. Guide to C.
- **[bgclr-vi](https://github.com/tamnd/bgclr-vi)** — ★1. Guide to the C Library Reference.
- **[bgipc-vi](https://github.com/tamnd/bgipc-vi)** — Guide to Interprocess Communication.
- **[bgnet0-vi](https://github.com/tamnd/bgnet0-vi)** — Guide to Network Concepts.
- **[bggit-vi](https://github.com/tamnd/bggit-vi)** — Guide to Git.
- **[bglcs-vi](https://github.com/tamnd/bglcs-vi)** — Guide to Learning Computer Science.
- **[beej-vi-docker](https://github.com/tamnd/beej-vi-docker)** — Shared TeX Live + pandoc build image used by all Beej guide repos above.

**Web platform**

- **[mdn-translated-content-vi](https://github.com/tamnd/mdn-translated-content-vi)** — ★3. Vietnamese translation of MDN Web Docs.
- **[mdn-worker](https://github.com/tamnd/mdn-worker)** — Cloudflare Worker that serves the Vietnamese MDN mirror. Built with rari + Fred.
- **[vi.react.dev](https://github.com/tamnd/vi.react.dev)** — Vietnamese translation of `react.dev`.

**Systems & languages**

- **[kernel-docs-vi](https://github.com/tamnd/kernel-docs-vi)** — Vietnamese translation of the Linux kernel `Documentation/` tree.
- **[kernel-worker](https://github.com/tamnd/kernel-worker)** — ★1. Cloudflare Worker serving the translated kernel docs at `kernel.go-mizu.dev`.
- **[ziglang-vi](https://github.com/tamnd/ziglang-vi)** — Vietnamese translation of `ziglang.org`.

**Python docs (PEP 545)**

- **[python-docs-vi](https://github.com/tamnd/python-docs-vi)** — ★1. Auto-synced from Transifex.
- **[python-docs-vi-manual](https://github.com/tamnd/python-docs-vi-manual)** — Manual-edit fork, for translations that don't flow through Transifex.
- **[python-docs-template](https://github.com/tamnd/python-docs-template)** — Starter template for PEP 545 Python docs translations in any language.

## Go libraries

Small packages. Some old, some still useful.

- **[httpclient](https://github.com/tamnd/httpclient)** — ★47. Simplified HTTP client for Go.
- **[spambot](https://github.com/tamnd/spambot)** — ★28. A spambot written in Go. (For research — please don't actually spam people.)
- **[dual](https://github.com/tamnd/dual)** — ★8. Dual numbers, for automatic differentiation.
- **[spintax](https://github.com/tamnd/spintax)** — ★8. Parser for spintax — the `{a|b|c}` text format used by automated article generators.
- **[gauth](https://github.com/tamnd/gauth)** — ★1. Clean authentication primitives for Go.

## Other

- **[voicewiki](https://github.com/tamnd/voicewiki)** — ★11. Experimental voice-driven interface for Wikipedia.
- **[Python-100-Days-English](https://github.com/tamnd/Python-100-Days-English)** — ★8. English port of the popular 100-day Python learning path.

---

Full list of repos (including forks I've hacked on): [github.com/tamnd](https://github.com/tamnd?tab=repositories).
