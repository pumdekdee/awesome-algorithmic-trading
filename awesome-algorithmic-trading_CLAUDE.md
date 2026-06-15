# Claude Project Context: awesome-algorithmic-trading

This file provides context for the **awesome-algorithmic-trading** repository, used as part of an AI trading-knowledge project.

## Project Overview
* **Name**: awesome-algorithmic-trading
* **Type**: Curated "awesome list" (Markdown only, no code)
* **Purpose**: A categorized index of algorithmic trading frameworks, libraries, broker APIs, books, papers, and courses across asset classes (equities, crypto, forex, futures, options).
* **License**: typically CC0 / unlicensed for the list content itself (individual linked projects have their own licenses)

## Core System Boundaries
* **No executable code**: this repo is a single (or few) `README.md`/`.md` file(s) organized into sections — there is no installable package, API, or entry point.
* **Living index**: links may become outdated (renamed orgs, archived repos, dead links) — treat entries as *starting points to verify*, not guaranteed-current resources.

## Repository Structure & Key Directories
* `/README.md` - The main curated list, typically organized into sections such as:
  * Frameworks & libraries (Python/other languages, by asset class)
  * Broker / exchange API wrappers
  * Backtesting tools
  * Data sources & data providers
  * Books, papers, and courses
  * Communities and blogs
* `/CONTRIBUTING.md` (if present) - Rules for what qualifies as "awesome" (stars, maintenance activity, etc.)

## Standard Operational Commands
* N/A — this is a reference document, not a runnable project. No install/build commands apply.

## AI Assistant Guidelines for this Project
1. **Use as a discovery index**: when a user asks "is there a library for X kind of trading task," scan this list's categories first to suggest candidate tools, then verify the candidate is still maintained before recommending it strongly.
2. **Don't assume freshness**: many "awesome list" entries point to abandoned projects — if the user plans to depend on a tool long-term, cross-check its last-commit date / open issues before recommending.
3. **No code generation from this repo**: don't attempt to "run" or "import" anything from this repo itself — only use it to point to other repos (some of which may already have their own CLAUDE.md in this knowledge project, e.g. freqtrade, ccxt, FinRL, nautilus_trader, backtrader, ta-lib-python, QuantLib, zipline, quantstats).
4. **Categorize by asset class**: when answering, group recommendations by the user's target market (stocks / crypto / forex / futures / options) since this list spans all of them.
