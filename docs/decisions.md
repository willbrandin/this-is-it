# ThisIsIt — Key Product Decisions

Ephemeral social media. All content deletes every 24 hours. These are the decisions that define the product and why we made them.

---

## 1. Full-Screen Swipe Feed Over Instagram-Style Scroll

**Decision:** Each post fills the entire screen (TikTok/Reels style). Swipe up to advance to the next post.

**Alternatives considered:** Traditional scroll feed (Instagram/Twitter style), paginated grid, hybrid scroll with "tap to expand."

**Why this was chosen:** Scroll feeds encourage skimming — you blow past content at speed, giving each post a fraction of a second. A swipe feed forces you to be present with each moment. You either engage or you deliberately move on. This matches the core product philosophy: be in the now.

**What it enables:** Higher per-post engagement, a more intentional consumption pattern, and a UX that reinforces the product's ephemerality message — every post is worth your full attention because it won't be here tomorrow.

---

## 2. Reposts as Discovery Signal, Not an Algorithm

**Decision:** Repost count is the primary signal driving Trending/Discover. No algorithmic ranking.

**Alternatives considered:** ML-powered recommendation engine, like-count ranking, engagement-time weighting, editorial curation.

**Why this was chosen:** Three reasons. (a) The community curates what trends organically — no black box deciding what you see. (b) High-repost creators surface naturally for follow recommendations without needing behavioral tracking. (c) A repost is more meaningful than a like because you're putting it on YOUR feed — it costs social capital.

**What it enables:** Transparent discovery mechanics, zero need for behavioral tracking infrastructure, community-driven content curation, and a natural creator growth path that users can actually understand.

---

## 3. Killed "Encore" (Save 1 Post Per Week)

**Decision:** No save mechanism of any kind. The Encore feature (save one post per week from deletion) was designed, evaluated, and cut.

**Alternatives considered:** Encore (1 save/week), Favorites vault, screenshot-friendly export, subscriber-only saves.

**Why this was chosen:** Any save mechanism either (a) becomes a loophole that undermines the core 24h promise — "everything deletes" stops being true — or (b) creates a content moderation liability by enabling unmoderated private storage that could become a hidden content vault. Reposts already solve the "this was valuable" signal without breaking ephemerality. The repost says "this mattered" while still letting the content expire.

**What it enables:** An uncompromised product promise. "Everything deletes in 24 hours" is absolute, not "everything deletes unless you save it." This simplicity is the trust foundation.

---

## 4. No Micro-Payments or Tipping

**Decision:** Subscription model only. No tipping, no micro-payments, no pay-per-view posts.

**Alternatives considered:** Tipping (a la Twitch), pay-per-view locked posts, virtual currency/coins, hybrid tip + subscription.

**Why this was chosen:** Tipping is friction-heavy for users and the payouts are tiny — nobody builds a career on $0.50 tips. It also creates a transactional vibe that conflicts with the product's tone. Subscriptions (subscriber-only drops + Golden Hour access) create recurring revenue for creators and align incentives: creators want to post consistently, subscribers want to keep showing up.

**What it enables:** Predictable creator income, cleaner UX (no tip jars cluttering every post), and a business model where creator success = platform success.

---

## 5. Public + Private Channels

**Decision:** Every user has two broadcast modes. Public = daily broadcast to the world. Private = invite-only for family/close friends. Same 24-hour deletion applies to both.

**Alternatives considered:** Public-only (add private later), Close Friends list (Instagram model), separate private app/feature.

**Why this was chosen:** Private channels unlock the millennial parent market — share kids' moments with grandma without building a permanent digital footprint. This is a massive unmet need. Parents want to share but are increasingly uncomfortable with permanent photo libraries on social platforms.

**What it enables:** A second major audience segment (millennial parents, 28-38) beyond the Gen Z launch cohort. Family sharing use case with the same ephemeral guarantee. Two distinct growth vectors from a single product mechanic.

---

## 6. Privacy by Architecture, Not by Policy

**Decision:** No algorithm, no behavioral tracking, no ad targeting derived from content. Structural guarantees, not policy promises.

**Alternatives considered:** Standard privacy policy with opt-outs, anonymized tracking, "privacy-focused" marketing with standard ad tech behind it.

**Why this was chosen:** If data doesn't exist, it can't be tracked, sold, subpoenaed, or breached. A privacy policy is a promise that can be broken. An architecture that never collects the data in the first place is a guarantee. Every competitor in the space makes privacy promises — we make privacy structural.

**What it enables:** The key differentiator in any competitive comparison. Defensible positioning that competitors cannot replicate without rebuilding their entire ad-funded business model. Genuine trust with privacy-conscious users.

---

## 7. Transparency Over Secrecy for Legal Holds

**Decision:** When law enforcement requires data preservation, notify the user when legally permitted. Publish quarterly transparency reports with exact numbers. When under a gag order, show a generic "suspended" state; notify the user retroactively when the gag lifts.

**Alternatives considered:** Silent compliance (industry standard), warrant canary, no-cooperation policy (legally untenable).

**Why this was chosen:** Modeled after Signal's approach. Users deserve to know when their data is being accessed by third parties. Transparency reports build institutional trust. The gag order handling is a pragmatic middle ground — comply with the law, but never hide from users longer than legally required.

**What it enables:** Trust with privacy-conscious users and press. A defensible public record. Alignment between what we say (privacy-first) and what we do when tested.

---

## 8. Target Audience Split

**Decision:** Primary launch audience is Gen Z (18-27) via public channels and creator subscriptions. Expansion audience is millennial parents (28-38) via private channels and family sharing.

**Explicitly not targeting:** 35+ light social media users, scrapbook/memory-keeping users, influencers dependent on content libraries.

**Alternatives considered:** Broad launch targeting all demographics, creator-first launch (invite-only for creators), teen-focused (under 18).

**Why this was chosen:** Gen Z is the beachhead — they already live in ephemeral content (Stories, Snaps), understand the format, and drive social platform adoption. Millennial parents are the expansion wedge with a distinct use case (private family sharing) that doesn't compete with the Gen Z value prop.

**What it enables:** Focused launch marketing, two sequential growth phases with different value propositions, and clear product priorities (don't build features for audiences we're not targeting).

---

## 9. Creator Economy Built on Scarcity

**Decision:** Subscription value is "don't miss tomorrow," not "access a library." Subscriber-only daily drops (still ephemeral, still 24h). Golden Hour live events with no replay. 80/20 revenue split favoring creators. Creator metrics (subscriber count, streak, earnings) persist even when content doesn't.

**Alternatives considered:** Content library access model, ad revenue sharing, brand deal marketplace, freemium with premium filters/tools.

**Why this was chosen:** The scarcity model turns ephemerality from a limitation into the monetization engine. FOMO drives subscription retention. No replay on Golden Hour makes live attendance valuable. 80/20 split is best-in-class and a strong creator acquisition tool.

**What it enables:** A creator economy where the platform's core mechanic (24h deletion) directly drives revenue instead of fighting against it. Persistent creator metrics solve the "but my stats disappear" objection without breaking ephemerality.

---

## 10. Chronological Feed with Following / For You Tabs

**Decision:** Following tab = strict chronological from accounts you follow. For You tab = repost-ranked trending content from today only. No ML-powered algorithmic feed.

**Alternatives considered:** Single algorithmic feed, reverse-chronological only (no discovery tab), interest-based topic feeds.

**Why this was chosen:** This is both a product decision and a privacy/trust decision. Chronological feeds are predictable — users understand why they see what they see. The For You tab uses reposts (a transparent, public signal) rather than hidden engagement metrics or behavioral profiling. This directly supports the "privacy by architecture" principle.

**What it enables:** User trust in the feed mechanics, zero behavioral tracking infrastructure, a clear mental model for users ("Following is my people, For You is today's best"), and consistency with the broader privacy positioning.
