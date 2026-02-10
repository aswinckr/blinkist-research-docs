# Data Gaps — Claims Lacking Proof

*Comprehensive catalog of evidence gaps requiring investigation*
*Created: 2026-02-10 00:36 Berlin*
*Task 12 of 164*

---

## Purpose

This document identifies all claims in Blinkist's B2B materials that lack adequate evidence. Each gap is:
- Linked to specific claim IDs
- Rated by risk level (impact on sales narrative)
- Assessed for fixability
- Paired with recommended actions

Use this as the investigation priority list for strengthening the evidence base.

---

## Gap Classification

| Category | Definition | Action Required |
|----------|------------|-----------------|
| **CRITICAL** | Core to sales narrative, no/contradicted evidence | Immediate resolution or reframe |
| **HIGH** | Important claim, weak evidence | Short-term investigation |
| **MEDIUM** | Supporting claim, incomplete evidence | Document when possible |
| **LOW** | Peripheral claim, minor gap | Nice to have |

---

## SECTION 1: CRITICAL GAPS (Immediate Attention Required)

### GAP-C1: Core Tagline Has No Evidence
**Claim:** "Learning that shows up where it's needed" (CLM-OUT-001)
**Status:** NONE — No supporting evidence, actively contradicted
**Risk Level:** 🔴 CRITICAL

| Aspect | Finding |
|--------|---------|
| **Location** | Slide 1 (opening tagline), repeated throughout |
| **Evidence Found** | None |
| **Contradicting Data** | STAT-011 (67% usage outside 9-5), CS-008 (commuting, pets, weekends) |
| **Business Impact** | Core positioning doesn't match product reality |
| **Gap Type** | Messaging-Reality Misalignment |

**Evidence Chain:**
```
CLM-OUT-001 ("Learning shows up where needed")
    └── ❓ NO supporting evidence found
        └── ❌ STAT-011: 67% use outside 9-5 hours
            └── ❌ CS-008: "commuting, walking pets, weekends"
                └── ❌ CONCLUSION: Positioning contradicts usage patterns
```

**Recommended Actions:**
| Priority | Action | Effort | Expected Impact |
|----------|--------|--------|-----------------|
| 1 | **Reframe positioning** to "Learning that fits your life" | Low | Aligns with actual usage |
| 2 | **Build workflow integrations** (Slack, Teams, HRIS) | High | Creates truth to current claim |
| 3 | **Collect "moment of need" stories** from users | Medium | Narrative evidence |

---

### GAP-C2: 72% Implementation Rate — No Methodology
**Claim:** 72% of learners apply insights to daily work (CLM-MET-011)
**Status:** WEAK — Metric stated but measurement methodology undocumented
**Risk Level:** 🔴 CRITICAL

| Aspect | Finding |
|--------|---------|
| **Location** | Slide 22 (Business Results section) |
| **Evidence Found** | STAT-014 (metric only), CS-007 (qualitative Trustpilot reference) |
| **Methodology** | ❓ Unknown — Survey? Behavioral data? Self-report? |
| **Business Impact** | Key ROI proof — buyers will ask "how do you know?" |
| **Gap Type** | Methodology Documentation |

**Evidence Chain:**
```
CLM-MET-011 (72% implementation)
    └── STAT-014 (number stated) ⚠️ No method
        └── ❓ How defined? (What counts as "apply"?)
        └── ❓ How measured? (Survey, tracking, observation?)
        └── ❓ Sample size and timing?
            └── CS-007 (Trustpilot quote) ⚠️ Qualitative only
                └── E-LDT-08 (industry struggles with this) ⚠️
```

**Recommended Actions:**
| Priority | Action | Effort | Expected Impact |
|----------|--------|--------|-----------------|
| 1 | **Document methodology** — What survey question? When asked? | Low | Instant credibility |
| 2 | **Add sample size and timeframe** | Low | Statistical validity |
| 3 | **Create application tracking** in product | High | Real behavioral data |
| 4 | **Benchmark against industry** | Medium | Comparative proof |

---

### GAP-C3: AI as Differentiator — Contradicted by Market
**Claim:** AI-powered pathways create competitive differentiation (CLM-POS-008)
**Status:** CONTRADICTED — Market evidence shows AI is commoditizing
**Risk Level:** 🔴 CRITICAL

| Aspect | Finding |
|--------|---------|
| **Location** | Slide 8, throughout deck |
| **Evidence Found** | None for differentiation |
| **Contradicting Data** | E-WS-01 (AI commoditizing), E-LDT-11 (personalization = table-stakes) |
| **Business Impact** | Positioning on a depreciating asset |
| **Gap Type** | Strategic Misalignment |

**Evidence Chain:**
```
CLM-POS-008 (AI as differentiator)
    └── ❓ NO documentation of unique AI features
        └── ❌ E-WS-01: "AI is rapidly commoditizing learning content"
            └── ❌ E-LDT-11: "Personalization is table-stakes, not differentiator"
                └── ⚠️ E-VID-01: "AI alone insufficient — need AI + community"
```

**Recommended Actions:**
| Priority | Action | Effort | Expected Impact |
|----------|--------|--------|-----------------|
| 1 | **Shift to "AI + Human" positioning** | Medium | Aligns with workshop strategy |
| 2 | **Document unique AI features** if any exist | Low | Proof or clarity on actual capabilities |
| 3 | **Emphasize human coaching as moat** | Low | Defensible differentiation |
| 4 | **Remove generic AI claims** from deck | Low | Reduces vulnerability |

---

### GAP-C4: Business Impact Analytics — Unproven
**Claim:** Analytics track business impact (CLM-PRD-007)
**Status:** WEAK — Claimed but not demonstrated
**Risk Level:** 🔴 CRITICAL

| Aspect | Finding |
|--------|---------|
| **Location** | Slides 9, 16 |
| **Evidence Found** | None — no screenshots, no feature documentation |
| **Industry Context** | E-LDT-06 (measurement is industry-wide problem) |
| **Business Impact** | Core buyer need: "prove value, protect budget" |
| **Gap Type** | Feature Documentation |

**Evidence Chain:**
```
CLM-PRD-007 (Analytics track business impact)
    └── SRC-01 Slide 9 (claim made) ⚠️ No proof
        └── ❓ What metrics are tracked?
        └── ❓ How is "business impact" defined?
        └── ❓ What does the dashboard look like?
            └── E-LDT-06: Industry struggles with this measurement
```

**Related Claims:**
- CLM-PRD-005: Analytics for engagement (MEDIUM evidence)
- CLM-PRD-006: Analytics track skill application (LOW evidence)
- CLM-OUT-004: "Prove value and protect budget" (LOW evidence)

**Recommended Actions:**
| Priority | Action | Effort | Expected Impact |
|----------|--------|--------|-----------------|
| 1 | **Screenshot analytics dashboard** | Low | Visual proof |
| 2 | **Document tracked metrics** — what's measurable | Low | Honest capability statement |
| 3 | **Create ROI calculator** for prospects | Medium | Quantitative proof tool |
| 4 | **Collect testimonials on reporting value** | Medium | Qualitative validation |

---

## SECTION 2: HIGH-PRIORITY GAPS (Short-Term Investigation)

### GAP-H1: 3x Engagement Benchmark — No Source
**Claim:** 3x typical L&D benchmarks (CLM-MET-004)
**Status:** WEAK — No external benchmark cited
**Risk Level:** 🟡 HIGH

| Aspect | Finding |
|--------|---------|
| **Location** | Slide 7 |
| **Evidence Found** | None — "typical benchmarks" undefined |
| **Business Impact** | Key differentiator claim without proof |
| **Gap Type** | External Validation |

**What's Needed:**
- Industry benchmark source (analyst report, survey)
- Definition of what "engagement" means for comparison
- Methodology for Blinkist's measurement

**Recommended Actions:**
| Priority | Action | Effort | Expected Impact |
|----------|--------|--------|-----------------|
| 1 | **Find industry benchmark report** (Brandon Hall, Josh Bersin, etc.) | Medium | External validation |
| 2 | **Define "engagement" for comparison** | Low | Clarity on claim |
| 3 | **If no source exists, revise claim** to relative improvement | Low | Defensible positioning |

---

### GAP-H2: "Prove Value, Protect Budget" — Unproven Capability
**Claim:** Support L&D leaders to prove value and protect budget (CLM-OUT-004)
**Status:** WEAK — Core buyer need, minimal evidence
**Risk Level:** 🟡 HIGH

| Aspect | Finding |
|--------|---------|
| **Location** | Slide 9 (primary message) |
| **Evidence Found** | Limited — Perlego NPS improvement only |
| **Industry Context** | E-LDT-04: ROI measurement is industry-wide struggle |
| **Business Impact** | Speaks directly to buyer pain, but no proof |
| **Gap Type** | Outcome Evidence |

**Evidence Chain:**
```
CLM-OUT-004 ("Prove value and protect budget")
    └── ❓ No ROI case studies
    └── ❓ No cost savings data
    └── ❓ No budget protection examples
        └── CS-003 (Perlego NPS) ⚠️ Engagement, not budget
```

**Recommended Actions:**
| Priority | Action | Effort | Expected Impact |
|----------|--------|--------|-----------------|
| 1 | **Collect budget protection story** from customer | Medium | Direct proof |
| 2 | **Document what reports customers share** with execs | Low | Workflow evidence |
| 3 | **Create budget impact calculator** | Medium | Self-serve proof tool |

---

### GAP-H3: "Ensure Learnings Are Applied" — Mechanism Unclear
**Claim:** Support you to ensure learnings are applied (CLM-OUT-005)
**Status:** WEAK — How this happens is undefined
**Risk Level:** 🟡 HIGH

| Aspect | Finding |
|--------|---------|
| **Location** | Slide 15 |
| **Evidence Found** | E-WS-02 (workshop mentions application focus), but mechanism unclear |
| **Business Impact** | Key differentiator from "content dump" competitors |
| **Gap Type** | Mechanism Documentation |

**What's Missing:**
- What product features drive application?
- What's the role of Action Plans (CLM-PRD-017)?
- How do coaches help with application?
- What data shows application happens?

**Recommended Actions:**
| Priority | Action | Effort | Expected Impact |
|----------|--------|--------|-----------------|
| 1 | **Document Action Plans feature** with screenshots | Low | Mechanism proof |
| 2 | **Collect coach-to-application stories** | Medium | Narrative evidence |
| 3 | **Create application tracking metrics** | High | Behavioral data |

---

### GAP-H4: Three Modes "Equally Developed" — Contradicted
**Claim:** (Implicit) Three modes are equally mature (CLM-IMP-001)
**Status:** CONTRADICTED — Evidence suggests On-demand dominates
**Risk Level:** 🟡 HIGH

| Aspect | Finding |
|--------|---------|
| **Location** | Slide 11 (equal visual weight) |
| **Evidence Found** | None for parity |
| **Contradicting Data** | STAT-012 (96% audio = On-demand), E-WS-03 (coaching emerging) |
| **Business Impact** | Sets expectations that may not be met |
| **Gap Type** | Product Maturity Disclosure |

**Evidence Chain:**
```
CLM-IMP-001 (Equal modes)
    └── Slide 11 (visual implication)
        └── ❌ STAT-012: 96% audio consumption
            └── ❌ E-WS-03: Workshop indicates coaching is new/emerging
                └── CONCLUSION: Modes are NOT equally developed
```

**Recommended Actions:**
| Priority | Action | Effort | Expected Impact |
|----------|--------|--------|-----------------|
| 1 | **Disclose mode maturity honestly** | Low | Trust building |
| 2 | **Position Guided/Coached as "new and growing"** | Low | Manages expectations |
| 3 | **Track mode adoption** for future evidence | Medium | Trend data |

---

### GAP-H5: Perlego Results as Standard — Single Case
**Claim:** (Implicit) Coaching outcomes like Perlego are standard (CLM-IMP-002)
**Status:** WEAK — Only one coaching case study with metrics
**Risk Level:** 🟡 HIGH

| Aspect | Finding |
|--------|---------|
| **Location** | Slide 23 (Perlego case) |
| **Evidence Found** | Only CS-003 (Perlego +41 NPS) |
| **Business Impact** | Buyers may expect similar results |
| **Gap Type** | Case Study Diversity |

**What's Missing:**
- Additional coaching outcome cases (2-3 minimum)
- Range of results (realistic expectations)
- Larger company examples

**Recommended Actions:**
| Priority | Action | Effort | Expected Impact |
|----------|--------|--------|-----------------|
| 1 | **Develop 2-3 more coaching case studies** | High | Reduces single-case risk |
| 2 | **Document range of outcomes** (best/typical) | Medium | Realistic expectations |
| 3 | **Get enterprise-scale coaching data** | High | Enterprise credibility |

---

## SECTION 3: MEDIUM-PRIORITY GAPS

### GAP-M1: Industry Adoption Baseline (~20%)
**Claim:** Industry adoption average is ~20% (CLM-MET-006)
**Status:** WEAK — No source cited for baseline
**Risk Level:** 🟠 MEDIUM

**Needed:** Industry report citing LMS/LXP adoption rates
**Action:** Research Brandon Hall, Josh Bersin, or ATD reports

---

### GAP-M2: "Save Hours in Admin"
**Claim:** Save hours in admin and curating content (CLM-OUT-003)
**Status:** WEAK — No quantification
**Risk Level:** 🟠 MEDIUM

**Needed:** Customer quote with time savings estimate
**Action:** Survey customers on time savings

---

### GAP-M3: Analytics for Skill Application
**Claim:** Analytics track skill application (CLM-PRD-006)
**Status:** WEAK — How measured?
**Risk Level:** 🟠 MEDIUM

**Needed:** Feature documentation, example reports
**Action:** Screenshot application tracking features

---

### GAP-M4: Success Plan Co-Creation
**Claim:** Success plan co-creation with customers (CLM-PRD-021)
**Status:** LOW — Vague service promise
**Risk Level:** 🟠 MEDIUM

**Needed:** Example success plan, process documentation
**Action:** Share anonymized success plan template

---

### GAP-M5: Reports for Executive Team
**Claim:** Reports suitable for executive team (CLM-PRD-022)
**Status:** WEAK — Limited proof
**Risk Level:** 🟠 MEDIUM

**Needed:** Sample executive report, customer testimonial
**Action:** Create example executive summary report

---

## SECTION 4: LOW-PRIORITY GAPS

### GAP-L1: "Modern Solution to Learning"
**Claim:** CLM-POS-002 — Marketing language only
**Status:** NONE — Pure positioning
**Risk Level:** 🟢 LOW
**Action:** Remove or substantiate with specific features

### GAP-L2: "We Handle the Complexity"
**Claim:** CLM-POS-006 — Vague service promise
**Status:** NONE — No proof
**Risk Level:** 🟢 LOW
**Action:** Substantiate with implementation/support details

### GAP-L3: Culture/Engagement Quote (Unnamed)
**Claim:** CLM-TST-005 — Unnamed testimonial
**Status:** MEDIUM — No attribution
**Risk Level:** 🟢 LOW
**Action:** Get permission to name speaker/company

### GAP-L4: "Flexible Learning Ecosystem"
**Claim:** CLM-PRD-002 — Marketing term
**Status:** NONE — Contradicted by 96% audio focus
**Risk Level:** 🟢 LOW
**Action:** Revise or remove

### GAP-L5: High Costs to Buy Skills
**Claim:** CLM-IND-008 — Industry problem, no specifics
**Status:** LOW
**Risk Level:** 🟢 LOW
**Action:** Find industry data on skills hiring costs

### GAP-L6: Inefficient L&D Spend
**Claim:** CLM-IND-009 — No specifics
**Status:** LOW
**Risk Level:** 🟢 LOW
**Action:** Find industry data on L&D ROI

---

## SUMMARY MATRIX

### Gap Count by Priority

| Priority | Count | % of Gaps |
|----------|-------|-----------|
| CRITICAL | 4 | 20% |
| HIGH | 5 | 25% |
| MEDIUM | 5 | 25% |
| LOW | 6 | 30% |
| **TOTAL** | **20** | 100% |

### Gap Count by Type

| Gap Type | Count | Examples |
|----------|-------|----------|
| Messaging-Reality Misalignment | 3 | Core tagline, AI differentiation, Three modes |
| Methodology Documentation | 2 | 72% implementation, 3x benchmark |
| Feature Documentation | 3 | Analytics, application tracking |
| External Validation | 2 | Industry benchmarks |
| Case Study Diversity | 2 | Perlego single case, coaching outcomes |
| Outcome Evidence | 3 | Budget protection, time savings |
| Strategic Misalignment | 2 | AI positioning, mode parity |
| Vague Promises | 3 | Success plans, handling complexity |

### Claims Affected by Gaps

| Category | Total Claims | With Gaps | Gap Rate |
|----------|--------------|-----------|----------|
| Metric | 21 | 4 | 19% |
| Product | 22 | 6 | 27% |
| Outcome | 13 | 8 | 62% |
| Positioning | 9 | 3 | 33% |
| Industry | 12 | 2 | 17% |
| Testimonial | 5 | 1 | 20% |
| Implicit | 6 | 4 | 67% |
| **TOTAL** | **88** | **28** | **32%** |

---

## INVESTIGATION ACTION PLAN

### Week 1 (Immediate)
| Action | Owner | Gap(s) Addressed | Deliverable |
|--------|-------|------------------|-------------|
| Document 72% implementation methodology | Product/Research | GAP-C2 | Methodology doc |
| Screenshot analytics dashboard | Product | GAP-C4 | Feature visuals |
| Draft revised positioning (away from AI-only) | Marketing | GAP-C3 | Messaging options |

### Week 2-4 (Short-Term)
| Action | Owner | Gap(s) Addressed | Deliverable |
|--------|-------|------------------|-------------|
| Find industry engagement benchmark | Research | GAP-H1 | Source citation |
| Collect budget protection customer story | Customer Success | GAP-H2 | Case study |
| Document Action Plans feature | Product | GAP-H3 | Feature documentation |
| Develop 1 additional coaching case study | Customer Success | GAP-H5 | Case study |

### Month 2+ (Strategic)
| Action | Owner | Gap(s) Addressed | Deliverable |
|--------|-------|------------------|-------------|
| Build workflow integrations (Slack/Teams) | Engineering | GAP-C1 | Product feature |
| Create ROI calculator | Marketing | GAP-H2, GAP-C4 | Interactive tool |
| Application tracking in product | Engineering | GAP-H3, GAP-C2 | Product feature |
| Enterprise coaching case studies (2+) | Customer Success | GAP-H5 | Case studies |

---

## CROSS-REFERENCE: GAPS TO STRATEGIC GAPS

| Data Gap | Links To | Implication |
|----------|----------|-------------|
| GAP-C1 (Core tagline) | Gap 1 (Flow of Work) | Fundamental positioning issue |
| GAP-C2 (72% implementation) | Gap 6 (Prove Business Impact) | ROI claim weakness |
| GAP-C3 (AI differentiation) | Gap 4 (AI as Liability) | Strategic direction unclear |
| GAP-C4 (Business impact analytics) | Gap 6 (Prove Business Impact) | Measurement capability gap |
| GAP-H1 (3x benchmark) | Gap 3 (Outcomes vs Engagement) | Proof of differentiation |
| GAP-H4 (Three modes parity) | Gap 2 (Three Modes) | Product maturity disclosure |
| GAP-H5 (Perlego single case) | Gap 5 (Perlego Attribution) | Case study diversity |

---

## GUARDRAILS VERIFICATION

| Guardrail | Status | Notes |
|-----------|--------|-------|
| G1: Evidence Traceability | ✅ Pass | All gaps linked to claim IDs |
| G1: Contradicting Evidence | ✅ Pass | Contradictions explicitly noted |
| G4: Actionability | ✅ Pass | Specific actions with owners |
| G6: Clarity & Readability | ✅ Pass | Prioritized, structured format |

---

*Created: 2026-02-10 00:36 Berlin*
*Task 12 of 164 complete*
*Analyst: Kai (Sunlight Research)*
*Total Gaps Identified: 20*
*Critical Gaps: 4*
*Claims Affected: 28 (32% of all claims)*
