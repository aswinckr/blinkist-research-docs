# Gap 5: Perlego Case Study Attribution

## Gap Summary

| Field | Value |
|-------|-------|
| **Gap ID** | GAP-05 |
| **Gap Name** | Perlego Case Study Attribution |
| **Severity** | 🟠 SEVERE (sales narrative vulnerability) |
| **Core Issue** | Strongest proof of outcomes comes from Coaching, but used to sell core product |
| **Last Updated** | 2026-02-10 04:51 Berlin |

---

## The Claims

### Primary Claims

| Claim ID | Claim | Source | Confidence |
|----------|-------|--------|------------|
| CLM-OUT-005 | "+41 NPS improvement in one quarter" | Sales Deck Slide 23 | HIGH |
| CLM-OUT-006 | "Exceptional Leadership Growth" | Sales Deck Slide 23 | HIGH |
| CLM-IMP-002 | Blinkist transforms leaders | Implied by case study positioning | MEDIUM |

### Supporting Quote

**Speaker:** Katie, L&D Manager at Perlego
**Full Quote:** 
> "Jumping from -9 to +32 is a huge shift! We've seen significant growth in ratings for prompts like 'My manager is a great role model for me and our employees.'"

**Metric:**
| Metric | Before | After | Change | Timeframe |
|--------|--------|-------|--------|-----------|
| Leadership NPS | -9 | +32 | **+41 points** | 1 quarter |

---

## The Evidence Chain

### What the Deck Implies

```
┌─────────────────────────────────────┐
│      POSITIONING IN DECK            │
├─────────────────────────────────────┤
│ Slide 23: "Exceptional Leadership   │
│ Growth in one Quarter with Coaching"│
│                                     │
│ IMPLICATION:                        │
│ Buy Blinkist → Get +41 NPS results  │
└─────────────────────────────────────┘
```

### What Actually Happened

```
┌─────────────────────────────────────────────────────────────────┐
│                    ACTUAL VALUE CHAIN                            │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ┌──────────────────┐     ┌──────────────────┐     ┌─────────┐  │
│  │ Blinkist COACHING │ ──► │ Human Experts    │ ──► │ +41 NPS │  │
│  │ (€3K premium pilot)│    │ Lead Sessions    │     │ Result  │  │
│  └──────────────────┘     └──────────────────┘     └─────────┘  │
│                                                                  │
│  ┌──────────────────┐     ┌──────────────────┐     ┌─────────┐  │
│  │ Blinkist CONTENT │ ──► │ Self-Paced       │ ──► │ ???     │  │
│  │ (Core product)   │     │ Consumption      │     │ No data │  │
│  └──────────────────┘     └──────────────────┘     └─────────┘  │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

### Evidence Mapping

| Evidence ID | Evidence | Source | Implication |
|-------------|----------|--------|-------------|
| CS-003 | +41 NPS improvement (Perlego) | case-studies-deep-dive.md | ONLY verified outcome case study |
| E-WS-04 | Coaching is €3K premium pilot, not default | workshop-analysis.md | Outcome came from premium, not core |
| STAT-012 | 96% audio consumption | statistics-catalog.md | Core product = content consumption |
| STAT-017 | 91% spike after Live Sessions | statistics-catalog.md | Human moments drive engagement |
| STAT-016 | +41 NPS is the ONLY hard metric | statistics-catalog.md | No other outcome evidence exists |

---

## The Gap Analysis

### Gap 5A: Attribution Mismatch

**Narrative:** "Blinkist transforms leaders (+41 NPS)"
**Reality:** "Expert coaching transforms leaders; Blinkist content supports the coaching"

```
                 WHAT DECK IMPLIES          WHAT EVIDENCE SHOWS
                 
             ┌─────────────────────┐    ┌─────────────────────────────┐
             │                     │    │                             │
BUY THIS:    │  Core Product       │    │  Coaching Program           │
             │  (€13-83/seat)      │    │  (€3K premium pilot)        │
             │                     │    │                             │
             └──────────┬──────────┘    └──────────┬──────────────────┘
                        │                          │
                        │                          │
GET THIS:    ┌──────────▼──────────┐    ┌──────────▼──────────────────┐
             │                     │    │                             │
             │  +41 NPS Results    │    │  +41 NPS Results            │
             │                     │    │                             │
             └─────────────────────┘    └─────────────────────────────┘
```

### Gap 5B: Scalability Question

| Aspect | Coaching (Source of Evidence) | Core Product (What's Sold) |
|--------|-------------------------------|----------------------------|
| **Pricing** | €3K pilot (premium) | €13-83/seat |
| **Delivery** | Human experts, live sessions | Self-paced, on-demand |
| **Scalability** | Limited by human capacity | Unlimited (SaaS) |
| **Evidence** | ✅ +41 NPS (Perlego) | ❌ No outcome evidence |

### Gap 5C: Single Data Point Risk

**The Perlego Problem:**
- Perlego is Blinkist's **ONLY** case study with hard before/after metrics
- All other case studies are qualitative (quotes, sentiment, no numbers)
- This creates over-reliance on a single data point

| Case Study | Metric Type | Before/After? | Outcome Data? |
|------------|-------------|---------------|---------------|
| CS-001 (HAYS) | Qualitative | ❌ | ❌ |
| CS-002 (Amazon) | Qualitative | ❌ | ❌ |
| **CS-003 (Perlego)** | **Quantitative** | **✅** | **✅ (+41 NPS)** |
| CS-004 (Tim Cook) | Endorsement | ❌ | ❌ |
| CS-005 (Babbel) | Qualitative | ❌ | ❌ |
| CS-006 (AMBOSS) | Qualitative | ❌ | ❌ |
| CS-007 (Trustpilot) | Qualitative | ❌ | ❌ |
| CS-008 (Matillion) | Qualitative | ❌ | ❌ |

**Strategic Risk:** If Perlego case is challenged or becomes dated, Blinkist has ZERO backup outcome evidence.

---

## Competitive Context

### How Competitors Handle Case Studies

| Competitor | Case Study Approach | Quantitative Evidence | Coaching Component |
|------------|--------------------|-----------------------|-------------------|
| LinkedIn Learning | TEI studies, enterprise logos | Forrester 14-month ROI payback | No coaching |
| Coursera Business | Industry-specific outcomes | Academic certificate completion | No coaching |
| Cornerstone | Forrester TEI (443% ROI claim) | $6.2M workforce value | AI coaching only |
| CoachHub | Coaching-specific outcomes | 73% leadership improvement | Core product |
| Blinkist | Mixed (Perlego is coaching) | **Only Perlego (+41 NPS)** | Premium add-on |

### The Transparency Gap

**What CoachHub does:** Sells coaching → Shows coaching outcomes → Clear attribution
**What Blinkist does:** Sells content → Shows coaching outcomes → Attribution mismatch

---

## Implications

### For Sales Process

| Stage | Risk | Likelihood |
|-------|------|------------|
| Discovery | Customer assumes Perlego result is from core product | HIGH |
| Proposal | Customer expects +41 NPS-level outcomes | MEDIUM |
| Pilot | Core product delivers engagement, not transformation | HIGH |
| Post-Sale | Customer disappointed by outcome gap | MEDIUM |
| Renewal | Churn if expectations not met | MEDIUM |

### For Competitive Positioning

1. **Challenge from sophisticated buyers:** "What product created the Perlego result?"
2. **Attribution questions:** "Can we get those results with just the core subscription?"
3. **Pricing disconnect:** "Why is Coaching €3K extra if it's what creates value?"

### For Strategic Direction

This gap reinforces the **meta-pattern** across all gaps:
> The sales narrative is optimized for **scale** (content, AI, low price) but the evidence for **value** (outcomes, transformation) comes exclusively from **human-led interventions** (Coaching).

---

## Strategic Options

### Option A: Honest Attribution (Recommended)

**Approach:** Be explicit about what created the Perlego result

**New Positioning:**
> "Our expert-led Coaching programs deliver outcomes like Perlego's +41 NPS improvement — and our microlearning content extends that transformation beyond the session."

**Advantages:**
- Honest, defensible positioning
- Protects against buyer scrutiny
- Clarifies Coaching as the hero
- Sets appropriate expectations

**Disadvantages:**
- May reduce perceived value of core product alone
- Requires pricing/packaging strategy adjustment

### Option B: Build Parallel Evidence (Long-term)

**Approach:** Develop outcome evidence for core product specifically

**Actions:**
1. Implement pre/post skill assessments for content-only customers
2. Track manager-reported behavior change metrics
3. Develop 2-3 quantitative case studies from On-demand only
4. Commission Forrester/IDC TEI study for core product

**Advantages:**
- Creates defensible core product positioning
- Reduces over-reliance on single data point
- Enables honest "choose your level" messaging

**Disadvantages:**
- 12-18 months to develop credible data
- May reveal that core product has lower outcome impact (risk)

### Option C: Integrated Positioning (Recommended Hybrid)

**Approach:** Position entire Blinkist experience, not separating products

**New Messaging:**
> "Blinkist delivers transformation through a combination of world-class microlearning content and expert-led coaching — from first insight to lasting behavior change."

**Advantages:**
- Sidesteps attribution question
- Positions coaching as integral, not add-on
- Allows premium tier upselling naturally

**Disadvantages:**
- May confuse buyers expecting pure SaaS
- Requires sales training update

---

## Action Plan

### Week 1: Immediate (Slide Updates)

| Action | Owner | Priority |
|--------|-------|----------|
| Update Slide 23 to clearly state Coaching context | Marketing | P0 |
| Add footnote: "Results from Blinkist Coaching program" | Marketing | P0 |
| Brief sales team on honest attribution messaging | Enablement | P0 |

### Weeks 2-8: Near-term (Evidence Development)

| Action | Owner | Priority |
|--------|-------|----------|
| Develop 2 more quantitative case studies (Coaching) | Customer Success | P1 |
| Implement pre/post assessments for content-only pilots | Product | P1 |
| Start tracking outcome metrics for core product | Analytics | P1 |
| Draft honest attribution sales talk track | Enablement | P1 |

### Months 3-6: Strategic (Product-Market Fit)

| Action | Owner | Priority |
|--------|-------|----------|
| Develop core product outcome evidence program | Product | P2 |
| Commission independent ROI study (Forrester/IDC) | Marketing | P2 |
| Evaluate Coaching as default vs. premium tier | Product Strategy | P2 |
| Develop integrated positioning if warranted | Marketing | P2 |

---

## Evidence Catalog (This Gap)

| ID | Evidence | Source | Confidence |
|----|----------|--------|------------|
| GAP5-001 | Perlego is ONLY quantitative case study | case-studies-deep-dive.md | HIGH |
| GAP5-002 | +41 NPS came from Coaching (€3K pilot) | workshop-analysis.md, CS-003 | HIGH |
| GAP5-003 | 7/8 case studies are qualitative only | case-studies-deep-dive.md | HIGH |
| GAP5-004 | No other before/after metrics exist | statistics-catalog.md | HIGH |
| GAP5-005 | Deck implies core product creates outcome | Slide 23 positioning | HIGH |
| GAP5-006 | STAT-016 confirms +41 is sole outcome data | statistics-catalog.md | HIGH |
| GAP5-007 | 0/10 competitors have human coaching | COMP-CH-010 | HIGH |
| GAP5-008 | Coaching is €3K premium, not default | E-WS-04 | HIGH |
| GAP5-009 | Perlego is ~150 employees (not enterprise) | CS-003 analysis | MEDIUM |
| GAP5-010 | Coaching validates human-led transformation | E-LDT-02 | HIGH |

---

## Cross-Reference to Other Gaps

| Gap | Relationship to Gap 5 |
|-----|----------------------|
| Gap 1 (Flow of Work) | Perlego shows coaching (human) drives value, not "flow of work" |
| Gap 2 (Three Modes) | Perlego proves Coaching is hero, not On-demand |
| Gap 3 (Outcome Metrics) | Perlego is sole outcome evidence — reinforces measurement gap |
| Gap 4 (AI Differentiator) | Perlego proves human coaching beats AI for outcomes |
| Gap 6 (Prove Value) | Perlego is the ONLY "proof" — creates fragile foundation |

---

## Key Takeaways

1. **Perlego is Blinkist's strongest proof** — but it's from Coaching, not core product
2. **Attribution mismatch creates sales risk** — customers may expect outcomes from content alone
3. **Single data point fragility** — if Perlego is challenged, Blinkist has no backup
4. **Strategic validation:** Human coaching (not AI content) creates measurable transformation
5. **Recommended approach:** Honest attribution now, parallel evidence development ongoing

---

## Guardrail Verification

| Guardrail | Status | Notes |
|-----------|--------|-------|
| G1 (Evidence Traceability) | ✅ | 10 evidence IDs with sources |
| G3 (Strategic Coherence) | ✅ | Connects to other gaps and meta-pattern |
| G4 (Actionability) | ✅ | 3-phase action plan with owners |
| G6 (Clarity) | ✅ | Clear evidence chains and visualizations |

---

*Created: 2026-02-10 04:51 Berlin*
*Sources: case-studies-deep-dive.md, narrative-reality-gaps.md, workshop-analysis.md, statistics-catalog.md, coaching-human-elements-audit.md*
