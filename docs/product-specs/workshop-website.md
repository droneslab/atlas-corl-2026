# Workshop Website Spec

## Purpose

This repository hosts the public-facing website for the Active Sensing and Learning for Robot Perception workshop at CoRL 2026.

The first release is a static single-page site adapted from the structure of `mikepierce/conference-website-template`.

## Current Behavior

- `index.html` is the public entrypoint.
- The homepage contains:
  - a hero banner with the workshop title rendered in a CSS-only gradient panel without a repository image asset
  - banner-level workshop logistics copy for November 9, 2026 and the Conference on Robot Learning
  - an Overview section framing active perception around computational imaging, generative AI, embodied decision making, controllable acquisition, multimodal robot sensing, and robot learning
  - a Scope section covering active image formation, active sensing formation beyond cameras, counterfactual sensing models, policies for choosing how to sense, and task-grounded evaluation
  - a Program section with a planned half-day schedule covering welcome remarks, four invited talks, a poster session, lightning talks, benchmark discussions, and closing remarks
  - an Active Illumination Benchmark section describing the fixed-trajectory simulation benchmark, participant control of robot-mounted illumination, open SLAM-based evaluation, and its first-iteration framing as an open community resource rather than a ranked competition
  - an Invited Speakers section with compact speaker cards in a 2-by-2 desktop grid (small headshot + name + affiliation) that link to external official profile pages and use external hosted headshot images
  - a Call for Papers section inviting **1-2 page extended abstracts (excluding references)**, noting that submissions are non-archival and accepted papers will be presented as posters with a subset selected for lightning talks
  - an Organizers section using photo cards with names and affiliations
  - a Contact section with the shared Yash Turkar workshop contact email
- Navigation is in-page anchor navigation with links for `Overview`, `Scope`, `Program`, `Benchmark`, `Speakers`, `Call for Papers`, `Organizers`, and `Contact`.
- Shared styling is defined in `assets/main.css`.

## Content Rules

- Do not invent workshop logistics that have not been confirmed.
- It is acceptable to publish placeholder text for:
  - venue
  - speakers
  - submission deadlines
  - submission destination links
- It is acceptable to publish concise Call for Papers guidance before the full submission workflow is confirmed.
- It is acceptable to publish the planned half-day Program schedule while final logistics are still being confirmed.
- It is acceptable to publish a concise public-facing benchmark summary, but do not add proposal-only resource, room, leaderboard, or evaluation logistics unless they are confirmed for public release.
- If external profile or image URLs are used for speakers, prefer official pages and keep the markup resilient (e.g., links open in a new tab, images are responsive).
- When those details become known, update the homepage and this spec if the information architecture changes.

## Near-Term Follow-Ups

- fill in Call for Papers deadline(s) and submission link once finalized
- optionally add 1–2 sentence bios for invited speakers once approved (currently limited to name + affiliation + external profile link)
