# ThisIsIt

Ephemeral social media app — all content deletes every 24 hours. Pre-development concept repo.

## Repo Structure

- `product-brief.html` — Visual product brief with hi-fi mockups
- `product.md` — Full product document (vision, features, audience, business model, legal, roadmap)
- `prototypes.html` — Interactive UI prototype playground (Feed, Capture, Profile, Discover screens)

All HTML files are self-contained single files (inline CSS/JS, Google Fonts CDN). No build tools or frameworks.

## Core Product Decisions

- **Full-screen swipe feed** (TikTok/Reels style), not scroll feed
- **Reposts for discovery** — repost count is the organic trending signal; no algorithm
- **Public + Private channels** — private channels target family/close friends (millennial parent expansion)
- **No save/archive features** — no loopholes to the 24-hour rule
- **No micro-payments/tipping** — monetization is subscriber-only drops and Golden Hour live events
- **Creator economy:** subscriber-only ephemeral drops, Golden Hour live events, 80/20 revenue split
- **Privacy by architecture:** no algorithm, no tracking, no ad targeting from content, chronological feed
- **Transparency:** legal hold with user notification, quarterly transparency reports
- **Screenshot detection + DRM-protected video**

## Target Audience

- Primary: Gen Z (18-27)
- Expansion: Millennial parents (28-38) via private channels

## Design System

- **Theme:** Dark — `#08080a` background, `#f0a500` amber/gold accent
- **Fonts:** Syne (display), DM Sans (body), JetBrains Mono (mono/technical)
- **Texture:** Grain overlay
- **Core UI motif:** Countdown timers on every screen showing time remaining

## Technical Notes

- Phone mockups in prototypes are pure CSS (no images)
- Countdown timers use `setInterval` counting down to midnight
- Fonts loaded via Google Fonts CDN
