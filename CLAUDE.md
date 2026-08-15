# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

uipath-web-scraper is a portfolio project that will use UiPath to automate web data collection and aggregate the results into an Excel report.

## Development environment

- Python 3.13 (64bit), installed at `C:\Program Files\Python313`
- .NET SDK 8.0
- UiPath CLI and the Claude Code UiPath skills are installed
- Naming convention: hyphen-separated lowercase (e.g. `web-scraper`, `excel-report`)

## Current state

The repository currently contains only `README.md` and `.gitignore` — no UiPath project, source files, or build tooling have been added yet. There are no commands to build, lint, or test because no project exists yet.

The `.gitignore` anticipates a UiPath project (ignoring `.local/`, `.settings/`, `.objects/`, `.tmh/`) alongside possible Python (`.venv/`, `__pycache__/`) and .NET (`bin/`, `obj/`) components, but none of these have been created.

When code is added to this repository, this file should be updated with the actual project structure, dependencies, and the real commands used to build/run/test it.
