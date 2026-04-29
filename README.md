# google-play-api

turn google play scraper into a RESTful API

## Overview

| Field | Value |
|---|---|
| Repository | `google-play-api` |
| Type | Node.js project |
| Visibility | Public |
| Default branch | `main` |
| Primary language | JavaScript |

## What This Repo Contains

- JavaScript/TypeScript package metadata in `package.json`.

## Tech Stack

- Node.js
- Express

## Project Structure

- `.github/` - GitHub workflows and repo automation
- `lib/` - project files

## Quick Start

```bash
npm install
npm start
```

## Development Commands

| Command | Description |
|---|---|
| `npm start` | Runs the `start` script. |

## Notes

- This README was generated from repository metadata and committed project files.
- Secret values, local databases, and machine-specific artifacts are intentionally excluded.
- Verify commands against the current code before using them in production.

## Existing Documentation

Turns [google-play-scraper](https://github.com/facundoolano/google-play-scraper/) into a RESTful API.

To run locally:

```
npm install
npm start
```

## Example requests

The parameters for each endpoint are taken directly from google-play-scraper. For a full reference check its [documentation](https://github.com/facundoolano/google-play-scraper/#usage).

Get the top free apps (default list)
```http
GET /api/apps/
```

Get the top free apps with full detail

```http
GET /api/apps/?fullDetail=true
```

Get the top selling action games in russia

```http
GET /api/apps/?collection=topselling_paid&category=GAME_ACTION&country=ru
```

Get an app detail

```http
GET /api/apps/org.wikipedia/
```

Get an app detail in spanish

```http
GET /api/apps/org.wikipedia/?lang=es
```

Get app required permissions with full descriptions

```http
GET /api/apps/org.wikipedia/permissions/
```

Get app required permissions (short list)

```http
GET /api/apps/org.wikipedia/permissions/?short=true
```

Get app data safety information

```http
GET /api/apps/org.wikipedia/datasafety/
```

Get similar apps

```http
GET /api/apps/org.wikipedia/similar/
```

Get an app's reviews

```http
GET /api/apps/org.wikipedia/reviews/
```

Search apps

```http
GET /api/apps/?q=facebook
```

Get search suggestions for a partial term

```http
GET /api/apps/?suggest=face
```

Get apps by developer

```http
GET /api/developers/Wikimedia%20Foundation/
```

Get categories
```http
GET /api/categories/
```

<!-- AI_PROJECT_AUDIT_START -->

## AI Project Audit

Generated: 2026-04-29

### What This Project Does
- Google Play API or release automation project.
- GitHub visibility: PUBLIC.
- Default branch: `main`.
- Last pushed: 2026-04-27T19:05:00Z.

### Stack
- JavaScript
- Node.js

### Current Status
- Active repository on GitHub.
- 11 tracked files detected in the default branch.

### What Is Not Done / Needs Attention
- GitHub description is empty.
- No obvious automated tests were detected.
- No GitHub Actions CI workflow was detected.

### Repository Shape
- Main paths:
  - `.eslintrc (1)`
  - `.github/ (1)`
  - `.gitignore (1)`
  - `LICENSE (1)`
  - `README.md (1)`
  - `lib/ (1)`
  - `package-lock.json (1)`
  - `package.json (1)`
- Key files:
  - `package.json`
  - `README.md`

### Run / Develop
Likely useful commands, inferred from manifests:

```bash
npm run start
```

### Notes For Future Work
- Keep this README aligned with the actual local project state.
- Add concrete setup, test, deploy, and ownership notes when the project becomes active.

<!-- AI_PROJECT_AUDIT_END -->
