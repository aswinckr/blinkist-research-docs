# Decision Tree — If X Then Y Recommendations

*Phase 7: Decision Support — Task 126*
*Created: 2026-02-10 09:15 Berlin*
*Evidence Foundation: Cross-referenced from forced-choices.md, recommendation-stack.md, 4 archetype files*

---

## Executive Summary

This decision tree maps **conditional pathways** from strategic choices to specific recommendations. Use it to:
1. Understand which recommendations apply given your strategic direction
2. See dependencies between choices
3. Navigate trade-offs based on current capabilities

**Format:** `IF [condition] → THEN [recommendations]`

---

## Master Decision Tree

```
START
│
├─► Decision 1: IDENTITY — Who are you?
│   │
│   ├─► IF "AI-First" chosen
│   │   │
│   │   ├─► THEN: Recommendation #8 (Slack/Teams Integration) — CRITICAL
│   │   ├─► THEN: Skip Recommendation #2 (Coaching as Hero)
│   │   ├─► THEN: Recommendation #3 (72% Methodology) — CRITICAL
│   │   ├─► WARNING: Evidence contradicts this path [COMP-AI-001]
│   │   └─► Archetype: AI Scale Leader
│   │
│   └─► IF "Human-First" chosen ✓ RECOMMENDED
│       │
│       ├─► THEN: Recommendation #1 (Human-Powered Positioning) — CRITICAL
│       ├─► THEN: Recommendation #2 (Coaching as Hero) — CRITICAL
│       ├─► THEN: Recommendation #6 (Coaching Case Studies) — HIGH
│       ├─► THEN: Recommendation #9 (Accountability Platform) — MEDIUM
│       └─► Archetype: Human-Led Transformation or Hybrid
│
├─► Decision 2: SCALE — Breadth or Depth?
│   │
│   ├─► IF "Breadth" (millions of learners, light touch)
│   │   │
│   │   ├─► THEN: Recommendation #8 (Slack/Teams) — enable scale
│   │   ├─► THEN: Recommendation #7 (LinkedIn Hub Partnership) — distribution
│   │   ├─► THEN: Skip Recommendation #2 (Coaching) — doesn't scale
│   │   └─► WARNING: "Information-focused learning is dying" [E-LDT-04]
│   │
│   └─► IF "Depth → Breadth" (thousands deep, then scale) ✓ RECOMMENDED
│       │
│       ├─► THEN: Recommendation #2 (Coaching as Hero) — CRITICAL
│       ├─► THEN: Recommendation #6 (3+ Coaching Case Studies) — prove depth
│       ├─► THEN: Recommendation #4 (91% Activation Story) — depth metric
│       ├─► THEN: Recommendation #9 (Accountability Platform) — enable depth
│       └─► LATER: Expand to breadth after proving transformation
│
├─► Decision 3: REVENUE MODEL — Volume or Premium?
│   │
│   ├─► IF "Volume" (€13/seat, maximize seats)
│   │   │
│   │   ├─► THEN: Skip Recommendation #2 (Coaching) — margin killer
│   │   ├─► THEN: Recommendation #8 (Slack/Teams) — enable frictionless adoption
│   │   ├─► THEN: Recommendation #7 (LinkedIn Partnership) — distribution
│   │   ├─► RISK: Margin erosion, commodity positioning
│   │   └─► Archetype: AI Scale Leader
│   │
│   ├─► IF "Premium" (€150+/seat, maximize value)
│   │   │
│   │   ├─► THEN: Recommendation #2 (Coaching as Hero) — CRITICAL
│   │   ├─► THEN: Recommendation #5 (Tiered Product) — capture premium segment
│   │   ├─► THEN: Recommendation #9 (Accountability Platform) — justify premium
│   │   ├─► THEN: Recommendation #10 (Enterprise Campaign) — reach premium buyers
│   │   └─► Archetype: Human-Led Transformation
│   │
│   └─► IF "Tiered" (both volume + premium) ✓ RECOMMENDED
│       │
│       ├─► THEN: Recommendation #5 (Tiered Product Structure) — CRITICAL
│       ├─► THEN: Recommendation #2 (Coaching) — hero for premium tier
│       ├─► THEN: Recommendation #8 (Slack/Teams) — enable volume tier
│       ├─► MARKETING: Lead with premium, volume follows
│       └─► Archetype: Hybrid
│
├─► Decision 4: CORE PRODUCT — Content Library or Activation Platform?
│   │
│   ├─► IF "Content Library" (value = access to knowledge)
│   │   │
│   │   ├─► THEN: Recommendation #7 (LinkedIn Partnership) — content distribution
│   │   ├─► THEN: Skip Recommendation #2 (Coaching) — off-brand
│   │   ├─► THEN: Skip Recommendation #9 (Accountability) — not needed
│   │   ├─► WARNING: Competing with LinkedIn (24K courses), Udemy (30K), Go1 (80K)
│   │   └─► Archetype: AI Scale Leader
│   │
│   └─► IF "Activation Platform" (value = knowledge into action) ✓ RECOMMENDED
│       │
│       ├─► THEN: Recommendation #2 (Coaching as Hero) — CRITICAL
│       ├─► THEN: Recommendation #4 (91% Activation Story) — CRITICAL
│       ├─► THEN: Recommendation #9 (Accountability Platform) — HIGH
│       ├─► THEN: Recommendation #6 (Coaching Case Studies) — prove activation
│       ├─► REFRAME: "Content = Preparation, Coaching = Activation"
│       └─► Archetype: Human-Led or Hybrid
│
├─► Decision 5: GO-TO-MARKET — Self-Serve or Enterprise Sales?
│   │
│   ├─► IF "Self-Serve" (product-led, credit card capture)
│   │   │
│   │   ├─► THEN: Skip Recommendation #2 (Coaching) — doesn't fit self-serve
│   │   ├─► THEN: Recommendation #8 (Slack/Teams) — friction-free experience
│   │   ├─► THEN: Create SMB landing page and checkout flow
│   │   └─► Archetype: AI Scale Leader (SMB segment)
│   │
│   └─► IF "Enterprise → SMB" (sales-led first, self-serve later) ✓ RECOMMENDED
│       │
│       ├─► THEN: Recommendation #2 (Coaching) — consultative sale
│       ├─► THEN: Recommendation #6 (Case Studies) — enterprise proof
│       ├─► THEN: Recommendation #10 (Enterprise Campaign) — reach target
│       ├─► THEN: Recommendation #7 (LinkedIn Partnership) — enterprise access
│       ├─► PHASE 2: Build self-serve using enterprise proof points
│       └─► Archetype: Human-Led or Hybrid
│
└─► Decision 6: DIFFERENTIATION — Features or Outcomes?
    │
    ├─► IF "Features" (we have AI, 8K Blinks, analytics)
    │   │
    │   ├─► WARNING: Feature claims are contradicted [GAP-C1, GAP-C3]
    │   ├─► WARNING: Competitors can replicate features
    │   ├─► THEN: Recommendation #8 (Slack/Teams) — add feature
    │   ├─► THEN: Skip Recommendation #4 (91% Story) — outcome-focused
    │   └─► HIGH RISK: No defensible position
    │
    └─► IF "Outcomes" (we create 91% activation, +41 NPS) ✓ RECOMMENDED
        │
        ├─► THEN: Recommendation #3 (72% Methodology) — CRITICAL (prove claims)
        ├─► THEN: Recommendation #4 (91% Activation Story) — CRITICAL
        ├─► THEN: Recommendation #6 (Coaching Case Studies) — outcome proof
        ├─► THEN: Recommendation #2 (Coaching) — outcomes require humans
        └─► Archetype: Human-Led or Hybrid
```

---

## Conditional Recommendation Matrix

### IF you choose the Evidence-Recommended Path (all 6 choices aligned):

| Decision | Recommended Choice | Key Recommendations |
|----------|-------------------|---------------------|
| Identity | Human-First | #1, #2, #6, #9 |
| Scale | Depth → Breadth | #2, #4, #6, #9 |
| Revenue | Tiered | #5, #2, #8 |
| Product | Activation Platform | #2, #4, #9, #6 |
| GTM | Enterprise → SMB | #2, #6, #10, #7 |
| Differentiation | Outcomes | #3, #4, #6, #2 |

**Resulting Priority Stack:**
1. **#2 Coaching as Hero** — appears in 5/6 paths = MANDATORY
2. **#6 Coaching Case Studies** — appears in 4/6 paths = CRITICAL
3. **#4 91% Activation Story** — appears in 3/6 paths = HIGH
4. **#9 Accountability Platform** — appears in 3/6 paths = HIGH
5. **#1 Human-Powered Positioning** — appears in 1/6 but foundational = CRITICAL
6. **#3 72% Methodology** — appears in 1/6 but quick win = HIGH
7. **#5 Tiered Product** — appears in 1/6 but revenue-enabling = MEDIUM
8. **#10 Enterprise Campaign** — appears in 1/6 = MEDIUM

---

## Scenario-Based Decision Trees

### Scenario A: "We want to stay AI-first but differentiate"

```
IF staying AI-first BUT want differentiation:
│
├─► PROBLEM: 10/10 competitors have AI [COMP-AI-001]
│
├─► OPTION 1: Niche AI advantage
│   ├─► THEN: Double-down on 15-minute audio format (unique)
│   ├─► THEN: Recommendation #8 (Slack/Teams) — AI in flow of work
│   ├─► THEN: Build proprietary AI for curation (not recommendations)
│   └─► RISK: Still commodity, hard to defend
│
└─► OPTION 2: AI + Human Hybrid (recommended)
    ├─► THEN: Recommendation #1 (Reposition to Human-Powered, AI-Enhanced)
    ├─► THEN: Recommendation #2 (Coaching as Hero)
    ├─► This IS differentiated AI positioning
    └─► Evidence: "AI makes human-led learning MORE valuable" [E-LDT-02]
```

### Scenario B: "We can't afford to build coaching infrastructure"

```
IF coaching investment not possible:
│
├─► OPTION 1: Partner instead of build
│   ├─► THEN: Partner with CoachHub (Berlin-based) [COMP-CH-040]
│   ├─► THEN: White-label coaching, Blinkist provides content
│   ├─► THEN: Skip Recommendation #9 (Accountability Platform)
│   └─► Lower margin but faster to market
│
├─► OPTION 2: Cohort model (1:many coaching)
│   ├─► THEN: Hire 5-10 in-house coaches
│   ├─► THEN: 1:50 ratio instead of 1:1
│   ├─► THEN: Recommendation #4 (91% Story) — Live Sessions ARE coaching
│   └─► Lower cost, still human differentiation
│
└─► OPTION 3: Peer coaching platform
    ├─► THEN: Build technology for peer accountability
    ├─► THEN: Recommendation #9 (Accountability Platform)
    ├─► THEN: Customers coach each other, Blinkist facilitates
    └─► No coach payroll, still human connection
```

### Scenario C: "Our sales team is used to selling content"

```
IF sales team trained on content, not outcomes:
│
├─► IMMEDIATE ACTIONS:
│   ├─► Recommendation #3 (Document 72% Methodology) — quick win
│   ├─► Recommendation #4 (91% Activation Story) — new talk track
│   └─► Recommendation #6 (3+ Case Studies) — proof for sales
│
├─► THEN: Retrain sales team (Week 4-8)
│   ├─► New deck with outcome messaging
│   ├─► New objection handling for "how do you measure?"
│   └─► New demo flow: show activation, not just content
│
└─► THEN: Recommendation #10 (Enterprise Campaign)
    └─► Marketing supports new sales narrative
```

### Scenario D: "We need revenue quickly"

```
IF short-term revenue pressure:
│
├─► QUICK WINS (Week 1-4):
│   ├─► Recommendation #3 (72% Methodology) — €3-5M/year, 2 days work
│   ├─► Recommendation #4 (91% Story) — €2-4M/year, 2 weeks work
│   └─► Total: €5-9M/year for minimal investment
│
├─► MEDIUM-TERM (Month 1-3):
│   ├─► Recommendation #6 (Case Studies) — enable larger deals
│   ├─► Recommendation #1 (Repositioning) — better close rates
│   └─► Total: €7-14M/year for €150K investment
│
└─► DO NOT (revenue killers):
    ├─► Skip Recommendation #5 (Tiered) — too slow for quick revenue
    ├─► Skip Recommendation #8 (Slack/Teams) — 6 month build
    └─► Skip Recommendation #9 (Accountability) — 6 month build
```

### Scenario E: "We're losing deals to LinkedIn Learning"

```
IF losing to LinkedIn Learning:
│
├─► DIAGNOSE: What's their objection?
│
├─► IF "LinkedIn has more courses":
│   ├─► REFRAME: "We have CURATED content, not content overload"
│   ├─► PROOF: [COMP-CL-024] Competitors have freshness problems
│   ├─► THEN: Recommendation #4 (91% Activation) — "our 8K beat their 24K"
│   └─► [COMP-CL-020] ONLY audio-first, 15-minute format
│
├─► IF "LinkedIn has AI":
│   ├─► REFRAME: "Everyone has AI. We have HUMANS."
│   ├─► PROOF: [COMP-AI-001] 10/10 competitors have AI
│   ├─► THEN: Recommendation #1 (Human-Powered positioning)
│   └─► [COMP-CH-010] 0/10 have human coaching
│
├─► IF "LinkedIn is trusted brand":
│   ├─► THEN: Recommendation #10 (Enterprise Campaign)
│   ├─► THEN: Recommendation #6 (Case Studies) — social proof
│   └─► [Q-003] Perlego +41 NPS is stronger than any LinkedIn proof
│
└─► IF "LinkedIn integrates with our LMS":
    ├─► GAP: Blinkist has ~10 integrations vs 45 [COMP-INT-005]
    ├─► THEN: Recommendation #7 (LinkedIn Hub Partnership) — ironically
    └─► THEN: Recommendation #8 (Slack/Teams) — common integration
```

### Scenario F: "We want to pursue the Platform Pivot archetype"

```
IF Platform Pivot strategy:
│
├─► WHAT IT MEANS:
│   ├─► Become aggregator like Go1 (80K courses from 250+ providers)
│   ├─► OR become ecosystem like Degreed (800+ integrations)
│   └─► Content becomes commodity, platform is value
│
├─► RECOMMENDATIONS THAT APPLY:
│   ├─► Recommendation #7 (LinkedIn Hub Partnership) — aggregate content
│   ├─► Recommendation #8 (Slack/Teams) — platform integration
│   └─► Skip Recommendation #2 (Coaching) — not platform play
│
├─► RECOMMENDATIONS THAT DON'T APPLY:
│   ├─► Skip #1 (Human positioning) — platform is tech-first
│   ├─► Skip #2 (Coaching as Hero) — not scalable platform model
│   ├─► Skip #9 (Accountability) — too custom for platform
│   └─► Skip #6 (Case Studies) — platform proof is different
│
└─► WARNING: Evidence doesn't support this path
    ├─► Go1 already has Blinkist in Premium Pro [COMP-GO1-001]
    ├─► Blinkist has 8K vs Go1's 80K — can't out-aggregate
    └─► Evidence points to Human-Led or Hybrid instead
```

---

## Decision Dependencies

Some decisions unlock or block others:

### Dependency Chain 1: Identity → Product → Recommendations

```
IF Identity = Human-First
└─► THEN Product = Activation Platform (mandatory)
    └─► THEN Recommendations #2, #4, #6, #9 (unlocked)
        └─► THEN GTM = Enterprise (mandatory for high-touch)
```

### Dependency Chain 2: Revenue → Scale → Capabilities

```
IF Revenue = Premium
└─► THEN Scale = Depth first (mandatory)
    └─► THEN Coaching infrastructure needed
        └─► THEN Recommendation #2 + #9 (dependencies)
```

### Dependency Chain 3: Differentiation → Evidence → Credibility

```
IF Differentiation = Outcomes
└─► THEN Recommendation #3 (72% Methodology) = CRITICAL
    └─► WITHOUT THIS: Claims collapse under scrutiny
        └─► Recommendation #4 + #6 depend on #3 foundation
```

---

## Anti-Patterns: IF You See These, Stop

| IF You See This | STOP Because |
|-----------------|--------------|
| Choosing AI-First AND Coaching as Hero | Contradiction: Either AI or Human leads |
| Choosing Breadth AND Premium | Contradiction: Breadth = volume pricing |
| Choosing Self-Serve AND Coaching | Contradiction: Coaching requires sales engagement |
| Choosing Features AND claiming outcomes | Contradiction: Feature claims are contradicted |
| Skipping #3 (72% Methodology) AND claiming ROI | Credibility risk: Can't defend claims |
| Choosing "both" on Identity | Paralysis: Must pick one to lead |

---

## Quick Reference: Archetype → Recommendations

| Archetype | Primary Recommendations | Skip These |
|-----------|------------------------|------------|
| **AI Scale Leader** | #7, #8, #3 | #2, #6, #9 |
| **Human-Led Transformation** | #1, #2, #4, #6, #9 | #8 (lower priority) |
| **Hybrid (AI + Human)** ✓ | #1, #2, #3, #4, #5, #6, #9 | None — phased approach |
| **Platform Pivot** | #7, #8 | #1, #2, #6, #9 |

---

## Evidence Cross-Reference

| Evidence ID | What It Proves | Recommendations It Supports |
|-------------|----------------|----------------------------|
| [COMP-AI-001] | AI is commoditized (10/10) | #1, #2 (human differentiation) |
| [COMP-CH-010] | 0/10 have human coaching | #2, #6, #9 (coaching investments) |
| [Q-003] | +41 NPS from coaching | #2, #4, #6 (outcome proof) |
| [STAT-025] | 91% activation spike | #4 (tell this story) |
| [GAP-C2] | 72% lacks methodology | #3 (document it) |
| [E-LDT-04] | Info-learning dying | #2, #4 (activation focus) |
| [COMP-CH-040] | CoachHub validates Berlin market | #2 (coaching investment safe) |
| [GAP-C1] | Flow of work contradicted | #8 OR reposition away |

---

## Implementation: Using This Decision Tree

### Step 1: Score Current Position
For each of the 6 decisions, identify where Blinkist currently sits (not where it wants to be).

### Step 2: Identify Gaps
Compare current position to evidence-recommended position. Gaps are priorities.

### Step 3: Trace Recommendation Path
Use the decision tree to identify which recommendations apply given your choices.

### Step 4: Check Dependencies
Ensure foundational recommendations (#3, #1) happen before dependent ones (#4, #6).

### Step 5: Monitor Anti-Patterns
If you're trying to "do both" on any decision, force a choice.

---

## Guardrails Verification

| Guardrail | Status | Notes |
|-----------|--------|-------|
| G1: Evidence Traceability | ✅ Pass | 15+ evidence IDs cross-referenced |
| G3: Strategic Coherence | ✅ Pass | Decision tree aligns to 4 archetypes |
| G4: Actionability | ✅ Pass | Clear if-then paths with specific recommendations |
| G6: Clarity | ✅ Pass | Tree format, tables, scenarios |

---

*Document created: 2026-02-10 09:15 Berlin*
*Task 126 of 164*
*Evidence IDs referenced: 15+*
*Decision paths documented: 6 primary + 6 scenarios*
