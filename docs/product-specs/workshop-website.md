# Workshop Website Spec

## Purpose

This repository hosts the public-facing website for the ATLAS workshop at CoRL 2026.

The first release is a static single-page site adapted from the structure of `mikepierce/conference-website-template`.

## Current Behavior

- `index.html` is the public entrypoint.
- The homepage contains:
  - workshop title and expansion of the ATLAS acronym
  - banner-level placeholder logistics copy for date and venue
  - overview and scope sections
  - schedule, submissions, and contact sections with placeholder copy
- Navigation is in-page anchor navigation with links for `Overview`, `Scope`, `Schedule`, `Submissions`, and `Contact`.
- Shared styling is defined in `assets/main.css`.

## Content Rules

- Do not invent workshop logistics that have not been confirmed.
- It is acceptable to publish placeholder text for:
  - date
  - venue
  - organizers and contact details
  - speakers
  - schedule structure and timing
  - submission instructions
- When those details become known, update the homepage and this spec if the information architecture changes.

## Near-Term Follow-Ups

- replace placeholder schedule copy with confirmed workshop format, speakers, and timing
- replace placeholder submissions copy with deadlines, requirements, and destination links
- replace placeholder contact copy with confirmed organizer names and contact channel
- add invited speakers or panelists once confirmed
