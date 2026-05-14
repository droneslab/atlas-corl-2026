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
  - an Overview section framing the workshop around active image formation, multimodal sensing control, and learning methods that convert better observations into better embodied behavior
  - a Scope section introduced as ideas, plus an explicit in-scope constraint tying generic vision/generative work to a robot sensing/control loop
  - a Program section describing a focused half-day format with invited talks, contributed posters or lightning talks, and a placeholder note that timing and session structure are pending confirmation
  - an Invited Speakers section with compact speaker cards (small headshot + name + affiliation) that link to external official profile pages and use external hosted headshot images
  - a Call for Papers section inviting **2-page extended abstracts (excluding references)**, with a placeholder note that deadlines and submission link are pending confirmation
  - an Organizers section using photo cards with names and affiliations
  - a Contact section with the shared Yash Turkar workshop contact email
- Navigation is in-page anchor navigation with links for `Overview`, `Scope`, `Program`, `Speakers`, `Call for Papers`, `Organizers`, and `Contact`.
- Shared styling is defined in `assets/main.css`.

## Content Rules

- Do not invent workshop logistics that have not been confirmed.
- It is acceptable to publish placeholder text for:
  - venue
  - speakers
  - submission deadlines
  - submission destination links
- It is acceptable to publish concise Call for Papers guidance before the full submission workflow is confirmed.
- It is acceptable to publish a high-level Program template without exact times while the final program is still being confirmed.
- If external profile or image URLs are used for speakers, prefer official pages and keep the markup resilient (e.g., links open in a new tab, images are responsive).
- When those details become known, update the homepage and this spec if the information architecture changes.

## Near-Term Follow-Ups

- replace the current half-day Program placeholder with confirmed workshop timing and final session structure once organizers confirm
- fill in Call for Papers deadline(s) and submission link once finalized
- optionally add 1–2 sentence bios for invited speakers once approved (currently limited to name + affiliation + external profile link)
