# Site Architecture

## Overview

The website is intentionally lightweight:

- plain static HTML in `index.html`
- plain shared CSS in `assets/main.css`
- no framework, bundler, or generated build output

## Design Direction

- Keep the site easy to deploy to GitHub Pages or any static host.
- Stay recognizably based on the upstream conference template's simple structure.
- Use a stronger visual identity than the upstream default while preserving maintainability.

## Current Structure

- `index.html`: landing page and all current content sections
- `assets/main.css`: typography, layout, responsive behavior, and visual theme

## Editing Guidance

- Prefer editing content directly in `index.html` while the site remains single-page.
- If the site grows into multiple pages, keep shared styles in `assets/main.css` and document the added routes in `docs/product-specs/workshop-website.md`.
- If external services are embedded later, document the dependency and failure mode in `docs/runbooks/README.md` or a dedicated runbook.
