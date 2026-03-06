# ThisIsIt — Product Document

**Version:** 1.0
**Date:** March 2026
**Status:** Concept / Pre-Development

---

## Vision

A social media platform where all content is deleted every 24 hours. No archives. No permanence. No algorithm. Just today.

**Tagline:** *"This is it."*

ThisIsIt is Instagram rebuilt around a single constraint: everything resets. Posts, comments, likes, DMs — all of it disappears at the 24-hour mark. What remains are relationships (your follow graph) and your identity (your profile). Everything else is today-only.

---

## Why Now

### The Problem with Permanent Social Media

1. **Performance anxiety** — every post is a permanent portfolio piece. People self-censor because the internet never forgets.
2. **Content hoarding** — 60% of users draft posts they never publish. The stakes feel too high.
3. **Algorithmic manipulation** — feeds are ranked by engagement, not relevance. Old content resurfaces out of context. The algorithm decides what you see, not you.
4. **Surveillance fatigue** — users know their data trains algorithms, targets ads, and builds profiles they never consented to. 72% of users feel platforms know "too much" about them.
5. **Digital footprint anxiety** — 78% of Gen Z report concern about their permanent online presence.
6. **Vanity metrics** — engagement is driven by likes and follower counts, not genuine human connection.

### The Opportunity

- BeReal proved massive demand for authentic, time-limited sharing (50M+ users at peak)
- Instagram Stories (24hr content) are the most-used feature on the platform — users already prefer ephemeral formats
- No platform has made ephemerality the *entire* product — it's always a feature within a permanent platform
- $200B+ global social media market with room for new paradigms
- Gen Z wants to share *more*, not less — just without consequences
- **Privacy by architecture** — if the data doesn't exist, it can't be tracked, sold, subpoenaed, or breached. This isn't a policy promise, it's a structural guarantee.

---

## Core Product

### The 24-Hour Cycle

Every piece of content — posts, comments, likes, DMs — is permanently deleted at the 24-hour mark from when it was created. Not hidden. Not archived. Deleted from servers. Verifiably, with third-party audits.

### What Persists

- **Account identity** — username, avatar, bio
- **Follow graph** — who you follow and who follows you
- **Follower/following counts** — social proof persists, content doesn't
- **Account settings and preferences**

### What Resets Every 24 Hours

- All posts (photo, video, text, live)
- All comments on all posts
- All likes and reactions
- All direct messages
- All story/highlight content
- Discover/trending rankings
- All engagement metrics on content

---

## Core Features

### 1. Full-Screen Feed
The main feed is full-screen, swipe-between-posts — like TikTok/Reels, not Instagram. Each post fills the entire screen. You swipe up to move to the next post from someone you follow.

- **Content-first** — no chrome, no borders, no list. The post IS the screen.
- **Overlay UI** — username, caption, and countdown timer overlay the bottom. Action rail (like, comment, repost, share) floats on the right.
- **Following / For You tabs** — toggle between chronological (people you follow) and repost-ranked (trending from today).
- **Countdown always visible** — every post shows its remaining time. The urgency is baked into the experience.

### 2. Daily Broadcast
Post photos, videos, text, or go live. No limit on posts per day. Share your day as it happens — raw, real, and pressure-free.

### 3. Follow Graph
Follow friends and creators. Chronological by default. No algorithmic ranking. No engagement-bait sorting.

### 4. Ephemeral Reactions
Like, comment, and react. But when the post goes, so do all interactions. No comment history. No like count accumulation over time. Engagement is in-the-moment.

### 5. Reposts
See something great? Repost it to your feed. The repost still deletes at 24 hours — no contradiction with the core promise. Reposts serve three purposes:

- **Discovery signal** — repost count is how content trends. No algorithm needed. The community curates Discover organically.
- **Creator discovery** — high-repost creators surface naturally. Reposts answer the question "who should I follow?" without an algorithm deciding for you.
- **Social currency** — a repost is a public endorsement. It's more meaningful than a like because you're putting it on *your* feed.

### 6. Discover Today
Trending content ranked by reposts, not by an algorithm. The most-reposted content today surfaces here. No viral content from last week. Everything on Discover is happening right now. Trends reset daily.

### 7. No Screenshots
Built-in screenshot detection notifies the poster. DRM-protected video playback. The content is meant to be experienced, not captured.

### 8. No Algorithm, No Tracking
If the data doesn't exist, it can't be tracked. No behavioral profiling, no ad targeting from your content, no engagement-bait ranking. Your feed is chronological — just today's posts from people you chose to follow.

### 9. Privacy by Architecture
This isn't a privacy policy — it's a technical guarantee. Content is deleted from servers. There's nothing to subpoena, nothing to breach, nothing to sell. Third-party audited deletion verification.

### 10. Public & Private Channels
Every user has two broadcast modes:

- **Public channel** — your daily broadcast to the world. Visible to followers and discoverable on the Explore tab.
- **Private channel** — invite-only. For family, close friends, or tight groups. Same 24-hour rule, different audience.

You choose per-post which channel it goes to. Some moments are for everyone. Some are just for your people.

**Why this matters:** Private channels unlock the millennial parent market. Share your kid's first steps with grandma — not the internet. The content still deletes at 24 hours, so you're not building a permanent digital footprint for a child who never consented to one. It's sharing without archiving.

---

## Target Audience

### Primary: Gen Z (18-27) — Launch Target

The early adopter base. They already prefer ephemeral formats and are the most likely to try new platforms.

- Already prefer ephemeral formats (Stories usage > Feed posts on Instagram)
- Highest digital footprint anxiety of any generation (78% report concern)
- Want to post more but self-censor because permanence feels risky
- Burnt out on algorithmic feeds and "personal brand" culture
- Drove early adoption of BeReal, TikTok, and Threads
- **Primary use:** Public channel. Daily broadcast. Creator subscriptions.

### Expansion: Millennial Parents (28-38) — Post-Launch Growth

The bigger market with higher willingness to pay, but requires different messaging.

- Share photos/videos of their kids constantly but increasingly worry about building a digital footprint their child never consented to
- Want to share moments with family — not archive them on the public internet forever
- Private channels are the killer feature for this demographic
- Less interested in public broadcast, highly motivated by intimate sharing with close circle
- Higher willingness to pay for privacy-first products
- **Primary use:** Private channels. Family sharing. Ephemeral moments with grandparents, siblings, close friends.

### The Messaging Split

| Audience | Message | Feature hook |
|---|---|---|
| Gen Z | "Post without thinking twice" | Public channel, no algorithm, creator subs |
| Millennial parents | "Share moments, not a permanent record" | Private channels, family sharing, screenshot protection |

### Not the Target (And That's Fine)

- People who post once a month (don't have the problem we solve)
- People who use Instagram as a scrapbook (want permanence)
- Influencers who depend on old content going viral (need libraries)
- 35+ light social media users (low posting frequency)

Building for these users would dilute the product. They don't have the problem. That's okay.

---

## Trust & Transparency

### The Legal Hold System

When law enforcement serves a valid legal request, we may be required to preserve specific account data beyond 24 hours. Our approach: radical transparency about when and why data is ever preserved.

**Account Status Model:**

| Status | Description |
|---|---|
| `active` | Normal operation. Content deletes at 24 hours. |
| `legal_hold` | Content preserved beyond 24 hours due to legal request. User notified when legally permitted. |
| `suspended` | Account access restricted. Used when gag order prevents disclosure of hold reason. |

**How It Works:**

1. **Legal request received** — valid subpoena, court order, or preservation request served on ThisIsIt.
2. **Account flagged** — the 24-hour deletion job skips this account's content.
3. **User notification (when allowed)** — "Your account is paused. Your content is being preserved under a legal request. Contact support for more information."
4. **Gag order scenario** — if the court order includes a non-disclosure provision (18 U.S.C. 2705(b)), we cannot notify the user. The account shows as "suspended" without further detail.
5. **Gag order expiry** — when the non-disclosure period ends, we notify the user retroactively about the hold.
6. **Hold released** — content deletion resumes. Account returns to `active`.

**The Signal Principle:**

Like Signal, our architecture means a subpoena on a normal account returns at most 24 hours of content. That's it. There's nothing else to hand over. The less you store, the less you can be compelled to produce.

### Quarterly Transparency Report

Published publicly every quarter. No spin. Just numbers:

- Total legal hold requests received
- Requests complied with vs. challenged
- Requests that included gag orders
- Total accounts affected
- Average hold duration
- Accounts notified after gag order expiry
- Third-party deletion audit results

**Target benchmark:** "We received 3 hold requests this quarter. 0 accounts were held without user notification."

---

## Competitive Landscape

| | Full Feed | All Ephemeral | No Algorithm | No Data Tracking | No Ad Targeting | Unlimited Posts |
|---|---|---|---|---|---|---|
| Instagram | Yes | No | No | No | No | Yes |
| Snapchat | No | No | No | No | No | Yes |
| BeReal | No | Yes | Yes | No | No | No |
| TikTok | Yes | No | No | No | No | Yes |
| **ThisIsIt** | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** |

**Key insight:** No one owns "fully ephemeral social." Existing platforms treat ephemerality as a feature and tracking as the business. We delete the content — and the leverage that comes with it.

---

## Business Model

### 1. ThisIsIt+ (Subscription — $4.99/mo)
- Extended post formats (longer video, higher resolution)
- Custom countdown themes and profile customization
- Priority placement in Discover during posting hours
- Repost analytics (see who reposted your content and where it spread)

**Why no "save" feature:** We considered "Encore" — saving 1 post per week to a private archive. We killed it. Any save mechanism either becomes a loophole that undermines the core promise, or a content moderation liability (private archives become unmoderated storage). Reposts solve the "this was valuable" signal without breaking ephemerality.

### 2. Promoted Moments (Advertising)
- Brands sponsor 24-hour campaigns that feel native to the platform
- Ephemeral ads create natural urgency — limited-time brand content that disappears
- No behavioral targeting. Ads are contextual (time of day, trending topics, geography) — not profile-based
- This is the advertising model for the post-tracking era

### 3. Data Promise (Trust as Moat)
- No ad targeting from deleted content
- Privacy-first model is the marketing itself
- Trust is the moat — once users believe it, switching costs are emotional, not technical
- Third-party audited deletion. Published audit results in transparency reports.

---

## Creator Economy

Scarcity is the monetization engine. If you miss it, it's gone. That's not a limitation — it's what makes creators valuable on ThisIsIt.

**The core insight:** The incentive to subscribe isn't "access a library." It's **"don't miss tomorrow."**

### Why Creators Post

- **Zero pressure** — content disappears, so there's no permanent portfolio to curate. Post raw, post often, post without overthinking.
- **Built-in urgency** — followers know content is fleeting, so engagement per post is higher. No competing with your own back catalog.
- **Subscriber revenue** — creators earn recurring income from subscriber-only daily drops. The subscription isn't for a library — it's for access to tomorrow.
- **Persistent reputation** — subscriber count, streak days, and total earnings persist even when content doesn't. Your track record grows while your content stays fresh.

### Why Users Subscribe

- **Exclusive daily drops** — subscriber-only posts that only subscribers see for 24 hours. Miss it? Gone forever. That's the value.
- **Golden Hour** — live events hosted by creators, visible only to subscribers. Can't be replayed, can't be screenshotted. Appointment content — think private concert, not YouTube video.
- **Inner circle access** — subscriber-only comments and reactions on creator posts. A tighter community, not a bigger one.
- **FOMO is real** — when your friend talks about what a creator posted yesterday and you missed it, that drives subscriptions more than any marketing ever could.

### Why NOT Persistent Content

We considered Patreon-style persistent content vaults for creators. We rejected it because:

1. **It violates the core promise.** If creators have permanent content, the platform's identity fractures. Users will ask "I thought everything deletes?" Trust erodes.
2. **It creates a two-tier system.** Free users get ephemeral content, paid users get permanent content. That's just Instagram with a paywall.
3. **Scarcity drives more value than permanence.** A video you can rewatch anytime has low urgency. A video that disappears in 18 hours has high urgency. The constraint is the feature.

### Creator Revenue Model

- **Revenue split:** 80/20 creator-favored
- **Creators set their own subscription price**
- **No lock-in contracts**
- **Payouts monthly**
- **Creator metrics that persist:** subscriber count, consecutive-day posting streak, total earnings, engagement rate

### What Creators Keep (Even When Content Deletes)

| Persists | Deletes at 24h |
|---|---|
| Subscriber count | Individual posts |
| Total earnings | Comments on posts |
| Posting streak | Like/reaction counts |
| Engagement rate (rolling avg) | Subscriber-only drops |
| Total repost count (lifetime) | Golden Hour recordings |
| Profile and bio | Reposts of your content |
| Follower count | DMs |

---

## Legal Considerations

### Non-Negotiable (Pre-Launch)

| Requirement | Details |
|---|---|
| **CSAM Detection & Reporting** | Federal law. Must report to NCMEC. Integrate PhotoDNA or Thorn's Safer for hash-matching. Section 230 does NOT protect here. |
| **Incorporation** | LLC minimum, C-Corp preferred. Never run a social platform as sole proprietor. |
| **Terms of Service + Privacy Policy** | Required in every jurisdiction. Must explain data collection, retention (or lack thereof), and deletion practices. |
| **Age Gating (COPPA)** | Must block users under 13. FTC updated COPPA rules effective April 2026. Date-of-birth gate at minimum. |
| **Content Reporting Flow** | Apple App Store requires this for UGC apps. Users must be able to flag content, and the platform must act on reports. |

### At Scale

| Requirement | Trigger |
|---|---|
| **EU Digital Services Act** | Any EU users. Content moderation, transparency reports, illegal content removal. |
| **State-level minor protection** | Louisiana (2025), Minnesota (2026), California (2027) — parental consent for under-16. |
| **GDPR** | Any EU users. Account data (email, username) still counts even if content is deleted. |
| **Law enforcement preservation** | Must be able to implement legal holds when served with valid court orders. |
| **Moderation at scale** | The most expensive line item. AI moderation plus human review for escalations. |
| **Insurance** | Cyber liability / E&O insurance. ~$1-3k/year early stage. |

### The Ephemeral Advantage

Most legal risk in social media comes from *retained data* — breaches, subpoenas, GDPR violations, ad-targeting lawsuits. By deleting content at 24 hours:

- Data breach liability is minimized (can't breach what doesn't exist)
- GDPR "right to be forgotten" is built into the product
- Ad-targeting lawsuits are moot (no behavioral profiles)
- Subpoena responses are minimal (at most 24 hours of content)

---

## Roadmap

### Phase 1 — Q3 2026: Private Beta
- iOS app launch, invite-only
- Core features: feed, camera, profile, follow graph
- 10k users across 3 target markets (LA, NYC, London)
- Validate: retention rates, daily post frequency, DAU/MAU

### Phase 2 — Q4 2026: Public Launch
- Open registration
- Android app + web companion
- Discover tab, DMs, screenshot detection
- CSAM detection integration
- Target: 500k users, 40% DAU/MAU ratio

### Phase 3 — Q1 2027: Monetization
- ThisIsIt+ subscription launch
- Creator tools beta
- First brand partnerships (Promoted Moments)
- First quarterly transparency report
- Target: 2M users, $1M ARR

### Phase 4 — Q2 2027: Scale
- Live video and group broadcasts
- International expansion (EU compliance)
- Promoted Moments ad platform GA
- Contract moderation team
- Target: 10M users, $10M ARR

---

## Technical Architecture (High-Level)

### Deletion System
- Content stored with `created_at` timestamp and `expires_at` (created_at + 24h)
- Background job runs continuously, deleting expired content
- Deletion is from all storage layers: database, CDN/object storage, cache
- `account_status` field gates deletion: `active` accounts delete normally, `legal_hold` accounts are skipped
- Third-party audit trail verifies deletion compliance

### Feed
- Chronological. No ranking algorithm.
- Query: "all posts from followed accounts where expires_at > now(), ordered by created_at DESC"
- Simple. Fast. No ML pipeline. No engagement scoring.

### Privacy
- Minimal data collection: email, username, hashed password
- No behavioral tracking, no analytics profiles, no cross-platform pixels
- Contextual ad serving only (time, geography, trending topics)
- Content encryption at rest, TLS in transit

---

## Open Questions

- **Timezone handling:** Does content expire 24h from creation, or does the whole platform reset at a fixed time (midnight UTC)? Per-post timers are more flexible; global reset creates a shared cultural moment.
- **DM retention:** Should DMs follow the same 24h rule, or should they have a separate (longer) window? Users expect messages to persist longer than feed posts.
- **Memories/Recap:** Should the app show you a private "On This Day" style recap of your past posting patterns (without the actual content)? e.g., "You posted 6 times on this day last year." Nostalgia without data retention.
- **Verification:** How to handle identity verification for creators/public figures when the content itself is ephemeral?
- **Abuse prevention:** How to handle harassment reports when the evidence auto-deletes? Need to snapshot reported content before deletion timer runs out.

---

*ThisIsIt. Every day is a fresh start.*
