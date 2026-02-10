# Dependencies & Sequencing — Critical Path Analysis

*Phase 7: Recommendations — Task 121*
*Created: 2026-02-10 08:46 Berlin*
*Evidence Foundation: Recommendation Stack (10 prioritized actions) + 90-Day Action Plan*

---

## Executive Summary

This document maps the dependencies between all 10 recommendations, identifies the critical path, and defines what must happen first. Incorrect sequencing can cause cascading delays, wasted resources, or failed initiatives.

### Core Insight
**Positioning must come first.** Every other recommendation builds on the Human-Powered, AI-Enhanced positioning. If positioning isn't locked in Week 1-4, all downstream work risks misalignment.

### Critical Path
```
[Rec 3] 72% Methodology → [Rec 4] 91% Story → [Rec 1] Repositioning
                                                        ↓
                               [Rec 2] Coaching Hero ← [Rec 5] Tiered Products
                                        ↓
                               [Rec 6] Case Studies → [Rec 10] Enterprise Campaign
                                        ↓
                               [Rec 9] Accountability Platform
```

**Slack/Teams [Rec 8] and LinkedIn Hub [Rec 7] run in parallel — not on critical path but required for full value.**

---

## Dependency Matrix

### Full Dependency Map

| Recommendation | Depends On | Enables | Priority | Blocker Level |
|----------------|------------|---------|----------|---------------|
| 1. Reposition Human+AI | 3, 4 | ALL | P0 | CRITICAL |
| 2. Coaching Hero | 1, 5 | 6, 9 | P0 | CRITICAL |
| 3. 72% Methodology | None | 1, 4 | P0 | NONE |
| 4. 91% Activation Story | 3 | 1 | P0 | LOW |
| 5. Tiered Products | 1 | 2, 6 | P1 | MEDIUM |
| 6. Coaching Case Studies | 2 | 10 | P1 | LOW |
| 7. LinkedIn Hub Partnership | 1 | None | P1 | NONE (parallel) |
| 8. Slack/Teams Integration | 1 | None | P2 | NONE (parallel) |
| 9. Accountability Platform | 2 | None | P2 | MEDIUM |
| 10. Enterprise Campaign | 1, 6 | None | P2 | LOW |

### Blocker Levels Explained
- **CRITICAL:** Must complete before starting dependent work
- **MEDIUM:** Partial overlap possible, but core must be done
- **LOW:** Can start before completion, but needs alignment
- **NONE:** Can run fully in parallel

---

## Critical Path Analysis

### Phase 0: Evidence Fixes (Week 1, Days 1-2)
**MUST COMPLETE FIRST — No dependencies**

```
[Rec 3: 72% Methodology]
├── Effort: 2 days
├── Owner: Research
├── Blockers: None
├── Output: Documented methodology, sample size, timing
└── Unblocks: Rec 1, Rec 4, all sales conversations

Evidence: [GAP-C2] — This is the highest-risk claim lacking proof.
Without methodology, every enterprise sales call is vulnerable.
```

**Evidence IDs:** [STAT-014], [GAP-C2], [E-LDT-08]

### Phase 1: Proof Points (Week 1, Days 2-5)
**Depends on: Rec 3 complete**

```
[Rec 4: 91% Activation Story]
├── Effort: 3 days
├── Owner: Marketing
├── Blockers: Rec 3 (need credible metrics foundation)
├── Output: One-pager, visual, talk track
└── Unblocks: Rec 1 positioning (provides hero metric)

Evidence: [STAT-025] — 91% engagement spike is the proof that
Human + AI > AI alone. This metric makes the positioning defensible.
```

**Evidence IDs:** [STAT-025], [E-LDT-02], [Q-003]

### Phase 2: Positioning Lock (Weeks 1-4)
**Depends on: Rec 3 + Rec 4 complete**

```
[Rec 1: Reposition to Human-Powered, AI-Enhanced]
├── Effort: 4 weeks (testing + refinement)
├── Owner: Marketing/Leadership
├── Blockers: Rec 3 (can't claim metrics without proof)
│             Rec 4 (need hero metric for positioning)
├── Output: New positioning statement, deck, website
└── Unblocks: EVERYTHING ELSE

Evidence: [COMP-AI-001], [COMP-CH-010], [GAP-C3], [E-LDT-02]
```

⚠️ **CRITICAL DEPENDENCY:** If Rec 1 is not locked by Week 4, all downstream work (Rec 2, 5, 6, 8, 9, 10) must pause or risk misalignment.

### Phase 3: Product Foundation (Weeks 4-8)
**Depends on: Rec 1 positioning locked**

```
[Rec 5: Tiered Product Structure]          [Rec 2: Coaching as Hero]
├── Effort: 4 weeks                        ├── Effort: 6 months (full)
├── Owner: Product                         ├── Owner: Product/Talent
├── Blockers: Rec 1 (tiers must            ├── Blockers: Rec 1 (coaching must
│             reflect positioning)         │             fit narrative)
├── Output: 4-tier structure               │             Rec 5 (coaching needs tier)
│           (Self-Serve, Guided,           ├── Output: Coach network, programs,
│            Coached, Certified)           │           pilot with 10 clients
└── Unblocks: Rec 2 (coaching tier)        └── Unblocks: Rec 6 (need pilots for
                                                          case studies)
                                                         Rec 9 (need coaching to
                                                          track accountability)
```

**Parallel Dependencies:**
- Rec 2 depends on Rec 5 for tier structure
- Rec 5 depends on Rec 1 for positioning alignment
- Both can start in Week 5, but Rec 5 features must inform Rec 2 pricing

### Phase 4: Evidence Expansion (Weeks 5-12)
**Depends on: Rec 2 coaching pilot live**

```
[Rec 6: Coaching Case Studies]
├── Effort: 10 weeks
├── Owner: CS/Marketing
├── Blockers: Rec 2 (need coaching clients with outcomes)
├── Output: 3+ case studies with metrics
└── Unblocks: Rec 10 (case studies are campaign content)

Evidence: [Q-003], [GAP-H5] — Perlego cannot be the only proof.
Need 3+ coaching outcomes to establish pattern, not outlier.
```

### Phase 5: Platform Infrastructure (Weeks 6-13+)
**Depends on: Rec 2 coaching pilot live**

```
[Rec 9: Accountability Platform]
├── Effort: 6 months
├── Owner: Product/Engineering
├── Blockers: Rec 2 (need coaching to track)
├── Output: Coach/learner dashboards, nudges, commitment logs
└── Unblocks: Coaching scale (this enables 1:many)

Evidence: [E-LDT-02], [E-WS-04], [PREC-BU-002]
```

### Phase 6: Distribution (Weeks 4-13+)
**Parallel workstreams — not on critical path**

```
[Rec 7: LinkedIn Hub Partnership]     [Rec 8: Slack/Teams Integration]
├── Effort: 3 months                  ├── Effort: 6 months
├── Owner: BD                         ├── Owner: Engineering
├── Blockers: Rec 1 (pitch must       ├── Blockers: Rec 1 (integration
│             match positioning)      │             must match narrative)
├── Output: Partnership agreement     ├── Output: Native apps, GA launch
└── Unblocks: Distribution            └── Unblocks: "Flow of work" claim

Note: These are parallel tracks. Can start Week 4 after positioning.
LinkedIn Hub is BD-intensive, not engineering. Slack/Teams is engineering.
```

### Phase 7: Market Activation (Weeks 9-13+)
**Depends on: Rec 1 + Rec 6 complete**

```
[Rec 10: Enterprise Campaign]
├── Effort: 6 months
├── Owner: Marketing
├── Blockers: Rec 1 (campaign must match positioning)
│             Rec 6 (need case studies for content)
├── Output: Content series, analyst coverage, events
└── Unblocks: Perception shift from "consumer app"

Evidence: [GAP-PR-001], [CS-008], [COMP-CL-030]
```

---

## Sequencing Rules

### Must-Complete-Before Rules

| Before Starting... | You MUST Complete... | Reason |
|--------------------|----------------------|--------|
| Rec 1 (Positioning) | Rec 3 (72% Methodology) | Can't claim metrics without proof |
| Rec 1 (Positioning) | Rec 4 (91% Story) | Need hero metric for positioning |
| Rec 2 (Coaching Hero) | Rec 1 (Positioning) | Coaching must fit narrative |
| Rec 2 (Coaching Hero) | Rec 5 (Tiered Products) | Need tier structure for pricing |
| Rec 5 (Tiered Products) | Rec 1 (Positioning) | Tiers must reflect positioning |
| Rec 6 (Case Studies) | Rec 2 (Coaching Pilot) | Need pilots for outcome data |
| Rec 9 (Accountability) | Rec 2 (Coaching Pilot) | Need coaching to track |
| Rec 10 (Campaign) | Rec 1 (Positioning) | Campaign must match message |
| Rec 10 (Campaign) | Rec 6 (Case Studies) | Need content for campaign |

### Can-Start-Before-Complete Rules

| Can Start... | Before Completing... | Condition |
|--------------|----------------------|-----------|
| Rec 2 (Coaching) | Rec 5 (Tiers) | If pilot pricing is set |
| Rec 5 (Tiers) | Rec 1 (Positioning) | Only if aligned to Human+AI direction |
| Rec 7 (LinkedIn Hub) | Rec 1 (Positioning) | If pitch aligned to Human+AI |
| Rec 8 (Slack/Teams) | Rec 1 (Positioning) | Spec work can start; launch waits |
| Rec 10 (Campaign) | Rec 6 (Case Studies) | With existing cases; expand later |

### Parallel Workstreams

These can run simultaneously without dependencies on each other:

```
Workstream A: Evidence & Positioning
Rec 3 → Rec 4 → Rec 1 → Rec 5

Workstream B: Partnerships (after Rec 1)
Rec 7 (LinkedIn Hub) — BD-led, no engineering

Workstream C: Integrations (after Rec 1)
Rec 8 (Slack/Teams) — Engineering-led

Workstream D: Coaching (after Rec 1 + Rec 5)
Rec 2 → Rec 6 → Rec 9

Workstream E: Marketing (after Rec 1 + Rec 6)
Rec 10 (Campaign)
```

---

## Resource Conflict Analysis

### Engineering Bottleneck

| Week | Rec 8 (Slack/Teams) | Rec 9 (Accountability) | Conflict |
|------|---------------------|------------------------|----------|
| 5-6 | Start Slack | — | None |
| 7-8 | Slack (50%) | Start Accountability (spec only) | Low |
| 9-10 | Slack (75%) | Accountability (dev starts) | Medium |
| 11-12 | Slack complete | Accountability (50%) | None |
| 13+ | Teams (50%) | Accountability (75%) | Medium |

**Resolution:** Stagger Slack (priority) before Teams. Accountability platform can use separate squad or begin after Slack ships.

### Marketing Bottleneck

| Week | Rec 1 (Positioning) | Rec 6 (Case Studies) | Rec 10 (Campaign) | Conflict |
|------|---------------------|----------------------|-------------------|----------|
| 1-4 | Full effort | Start | — | Medium |
| 5-8 | Maintenance | Full effort | Strategy | Low |
| 9-13 | — | Complete | Full effort | Low |

**Resolution:** Case studies can use CS capacity for interviews. Marketing focuses on positioning Weeks 1-4, shifts to campaign Weeks 9+.

### BD Bottleneck

| Week | Rec 7 (LinkedIn Hub) | Other BD Work | Conflict |
|------|----------------------|---------------|----------|
| 4-13 | Active negotiation | Normal | Low |

**Resolution:** LinkedIn Hub is single BD priority. No conflict expected.

---

## Gantt-Style Timeline

```
Week:     1   2   3   4   5   6   7   8   9  10  11  12  13
          ├───┼───┼───┼───┼───┼───┼───┼───┼───┼───┼───┼───┤

Rec 3     ██░░                                              ← Day 1-2
Rec 4     ░░██                                              ← Week 1
Rec 1     ░░████████                                        ← Weeks 1-4
Rec 5         ░░░░████████                                  ← Weeks 4-8
Rec 2         ░░░░░░░░████████████████                      ← Weeks 5-13+
Rec 6             ░░░░░░░░░░████████████                    ← Weeks 5-12
Rec 7         ░░░░████████████████████████                  ← Weeks 4-13+
Rec 8         ░░░░░░░░████████████████████                  ← Weeks 5-13
Rec 9                 ░░░░░░░░░░████████████                ← Weeks 7-13+
Rec 10                        ░░░░░░████████                ← Weeks 9-13+

Legend: ██ = Active work   ░░ = Prep/dependent waiting
```

---

## Sequencing Failures to Avoid

### Anti-Pattern 1: Starting Coaching Before Positioning
**Risk:** Coaching product positioned on AI → contradicts Human+AI message
**Symptom:** Sales confusion, messaging inconsistency
**Prevention:** Lock positioning (Rec 1) before launching coaching pilot (Rec 2)

### Anti-Pattern 2: Building Slack Before Use Case Clarity
**Risk:** Integration built for "content push" when market wants "learning moments"
**Symptom:** Low adoption, feature doesn't match need
**Prevention:** Finalize positioning and specify Slack use cases before sprint 1

### Anti-Pattern 3: Case Studies Before Coaching Outcomes
**Risk:** Case studies don't include coaching metrics → weak proof
**Symptom:** "Another Perlego" syndrome — one data point, not pattern
**Prevention:** Wait for Rec 2 pilot results before finalizing Rec 6 stories

### Anti-Pattern 4: Campaign Before Evidence
**Risk:** Campaign makes claims that can't be supported
**Symptom:** Enterprise buyers ask for proof; none available
**Prevention:** Complete Rec 6 (case studies) before scaling Rec 10

### Anti-Pattern 5: Accountability Platform Before Coaching Scale
**Risk:** Building platform for coaching that doesn't exist at scale
**Symptom:** Over-engineered features, low utilization
**Prevention:** Prove coaching model works (Rec 2 pilot) before investing in Rec 9

---

## Critical Decision Points

### Decision Point 1: Week 4 — Positioning Lock
**Gate:** Leadership approves final positioning statement
**Go Criteria:**
- [ ] 3+ positioning test calls completed with positive feedback (≥80%)
- [ ] 72% methodology fully documented
- [ ] 91% Activation Effect story complete
- [ ] Sales team aligned on messaging

**If Not Met:** Extend positioning phase by 2 weeks; delay Rec 5, 7, 8, 10

### Decision Point 2: Week 8 — Coaching Pilot Go/No-Go
**Gate:** First 4 weeks of coaching pilot data reviewed
**Go Criteria:**
- [ ] 10 pilot clients active
- [ ] 5+ coaches performing
- [ ] Early NPS/satisfaction signals positive
- [ ] No major operational failures

**If Not Met:** Pause expansion (Rec 6, 9); iterate on coaching model

### Decision Point 3: Week 10 — Slack MVP Go/No-Go
**Gate:** Slack MVP tested with 10 clients
**Go Criteria:**
- [ ] MVP feature complete
- [ ] 10 client pilots active
- [ ] Usage data shows daily engagement
- [ ] No major technical issues

**If Not Met:** Delay GA launch; extend pilot by 2 weeks

### Decision Point 4: Week 12 — Scale Readiness
**Gate:** Full review before 90-day completion
**Go Criteria:**
- [ ] 3+ coaching case studies with metrics
- [ ] 15+ coaching clients active
- [ ] Slack GA-ready
- [ ] Campaign generating leads

**If Not Met:** Adjust Days 91-180 roadmap; identify blockers

---

## Summary: What Must Happen First

### Absolute Prerequisites (Week 1)
1. **Document 72% methodology** [Rec 3] — No sales call is safe without this
2. **Create 91% Activation story** [Rec 4] — Hero metric for positioning

### Positioning Lock (Week 4)
3. **Lock Human-Powered, AI-Enhanced positioning** [Rec 1] — Everything else builds on this

### Foundation for Scale (Week 8)
4. **Define tiered products** [Rec 5] — Enables coaching pricing
5. **Launch coaching pilot** [Rec 2] — Generates case study data

### Evidence for Campaign (Week 12)
6. **Complete 3+ coaching case studies** [Rec 6] — Content for enterprise campaign

### Parallel Tracks (Can Start Week 4)
7. LinkedIn Hub partnership [Rec 7] — BD-led, independent
8. Slack/Teams integration [Rec 8] — Engineering-led, independent

### Dependent on Coaching (Week 9+)
9. Accountability platform [Rec 9] — Needs coaching to track
10. Enterprise campaign [Rec 10] — Needs positioning + case studies

---

## Guardrails Verification

| Guardrail | Status | Notes |
|-----------|--------|-------|
| G1: Evidence Traceability | ✅ Pass | Dependencies linked to evidence IDs |
| G3: Strategic Coherence | ✅ Pass | All sequencing supports Human+AI archetype |
| G4: Actionability | ✅ Pass | Clear rules, decision points, anti-patterns |
| G6: Clarity | ✅ Pass | Visual timeline, dependency matrix |

---

*Document created: 2026-02-10 08:46 Berlin*
*Task 121 of 164*
*Analyst: Kai (Sunlight Research)*
*Dependencies mapped: 10 recommendations*
*Critical path length: 13 weeks*
