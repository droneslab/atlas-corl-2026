# Workshop Website Spec

## Purpose

This repository hosts the public-facing website for the ATLAS workshop at CoRL 2026.

The first release is a static single-page site adapted from the structure of `mikepierce/conference-website-template`.

## Current Behavior

- `index.html` is the public entrypoint.
- The homepage contains:
  - a hero banner with the ATLAS title rendered in a CSS-only gradient panel without a repository image asset
  - banner-level workshop logistics copy for November 9, 2026 and the Conference on Robot Learning
  - workshop title and expansion of the ATLAS acronym
  - overview and scope sections
  - a Program section with a placeholder schedule table from 09:20 to 16:25, including invited talk slots labeled `TBD` instead of speaker names
  - a Call for Papers section that invites concise 4 to 6 page papers aligned with the workshop themes
  - Call for Papers copy that stays high level and does not yet publish deadlines, formatting rules beyond page count, or submission destination links
  - contact section with organizer names and email addresses for Yash Turkar and Karthik Dantu
- Navigation is in-page anchor navigation with links for `Overview`, `Scope`, `Program`, `Call for Papers`, and `Contact`.
- Shared styling is defined in `assets/main.css`.

## Content Rules

- Do not invent workshop logistics that have not been confirmed.
- It is acceptable to publish placeholder text for:
  - venue
  - speakers
  - submission deadlines
  - submission destination links
- It is acceptable to publish concise Call for Papers guidance before the full submission workflow is confirmed.
- It is acceptable to publish a high-level Program template without speaker names or exact times while the final program is still being confirmed.
- When those details become known, update the homepage and this spec if the information architecture changes.

## Near-Term Follow-Ups

- replace the provisional invited-talks/posters Program template with confirmed workshop timing, speakers, and session structure
- expand the Call for Papers section with deadlines, formatting requirements beyond page count, and destination links once confirmed
- add invited speakers or panelists once confirmed
