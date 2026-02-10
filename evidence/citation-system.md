# Evidence Citation System — Blinkist Comprehensive Report

*Unified reference system for all evidence throughout the report*
*Created: 2026-02-10 00:41 Berlin*

---

## Purpose

This document establishes a **unified citation system** that enables:
1. Every claim in the final report to link to verifiable evidence
2. Consistent referencing across all 9 phases
3. Easy cross-referencing between related evidence types
4. Quick verification for any assertion

---

## Master Citation Format

### Standard Citation Syntax

In-text citations use square brackets with evidence ID:

```
"Blinkist achieves 68% Month-1 adoption" [STAT-008]
```

For multiple sources:
```
"AI is commoditizing content delivery" [E-WS-01, E-LDT-04]
```

For claims with confidence notes:
```
"72% implementation rate" [STAT-014; LOW confidence, methodology unclear]
```

---

## Evidence ID Taxonomy

### Tier 1: Primary Sources (P-xxx)

Original documents analyzed. **Highest reliability.**

| ID | Source | Type | Location |
|----|--------|------|----------|
| **P-1** | Blinkist B2B Sales Deck | PDF, 28 slides | `assets/original-deck.pdf` |
| **P-2** | L&D Trends Report (Offbeat 37 Secrets) | PDF, 159 pages | `assets/offbeat-37-ld-secrets-2025.pdf` |
| **P-3** | Workshop Proposal | PDF, 2 pages | `assets/workshop-proposal.pdf` |

Usage: `[P-1:S15]` = Primary source 1, Slide 15

---

### Tier 2: Statistics (STAT-xxx)

Quantitative claims from all sources. 42 statistics cataloged.

| ID Range | Category | Count |
|----------|----------|-------|
| STAT-001 to STAT-006 | Company Scale | 6 |
| STAT-007 to STAT-013 | Engagement & Adoption | 7 |
| STAT-014 to STAT-018 | Impact & Outcomes | 5 |
| STAT-019 to STAT-024 | Pricing | 6 |
| STAT-025 to STAT-028 | Operational | 4 |
| STAT-029 to STAT-031 | Time-Based | 3 |
| STAT-032 to STAT-035 | Derived/Implicit | 4 |
| STAT-036 to STAT-037 | External Validation | 2 |
| STAT-038 to STAT-042 | Missing/Needed | 5 |

Usage: `[STAT-014]` or with context `[STAT-014; 72% implementation]`

Full catalog: `evidence/statistics-catalog.md`

---

### Tier 3: Claims (CLM-xxx-yyy)

Marketing/positioning claims. 88 claims cataloged.

| Category | Code | Example ID | Count |
|----------|------|------------|-------|
| Metric | MET | CLM-MET-001 | 21 |
| Product | PRD | CLM-PRD-001 | 22 |
| Outcome | OUT | CLM-OUT-001 | 13 |
| Positioning | POS | CLM-POS-001 | 9 |
| Industry | IND | CLM-IND-001 | 12 |
| Testimonial | TST | CLM-TST-001 | 5 |
| Implicit | IMP | CLM-IMP-001 | 6 |

Usage: `[CLM-OUT-001]` = Core tagline "Learning shows up where needed"

Full catalog: `evidence/claim-inventory.md`

---

### Tier 4: Thematic Evidence (E-xxx-yy)

Evidence extracted by theme/source.

| Prefix | Source | ID Range | Count |
|--------|--------|----------|-------|
| E-WS | Workshop Analysis | E-WS-01 to E-WS-06 | 6 |
| E-LDT | L&D Trends Report | E-LDT-01 to E-LDT-20 | 20 |
| E-VID | YouTube Video (L&D Disrupt Ep92) | E-VID-01 to E-VID-09 | 9 |
| E-CS | Case Studies | E-CS-01 to E-CS-08 | 8 |

Usage: `[E-LDT-04]` = L&D Trends finding #4: "Information-focused learning is dying"

Full catalogs:
- `evidence/workshop-analysis.md`
- `evidence/ld-trends-top-20-findings.md`
- `evidence/video-analysis-ld-disrupt-ep92.md`
- `evidence/case-studies-deep-dive.md`

---

### Tier 5: Quotes (Q-xxx)

Customer/expert quotes. 7 quotes cataloged.

| ID | Speaker | Company | Strength |
|----|---------|---------|----------|
| Q-001 | Friedrich Menz | HAYS | HIGH |
| Q-002 | Lloyd Wilky | Amazon | HIGH |
| Q-003 | Katie | Perlego | HIGH |
| Q-004 | Tim Cook | Apple | HIGH |
| Q-005-007 | Various/Unnamed | — | MEDIUM-LOW |

Usage: `[Q-003]` = Perlego testimonial

Full catalog: `evidence/quote-bank.md`

---

### Tier 6: Data Gaps (GAP-x-yy)

Identified evidence gaps by priority.

| Priority | Code | ID Range | Count |
|----------|------|----------|-------|
| Critical | C | GAP-C-01 to GAP-C-04 | 4 |
| High | H | GAP-H-01 to GAP-H-05 | 5 |
| Medium | M | GAP-M-01 to GAP-M-05 | 5 |
| Low | L | GAP-L-01 to GAP-L-06 | 6 |

Usage: `[GAP-C-01]` = Critical gap: Core tagline has no evidence

Full catalog: `evidence/data-gaps.md`

---

### Tier 7: Competitor Evidence (COMP-xxx-yy)

Evidence from competitor research. (Phase 2 — to be populated)

| Prefix | Competitor | ID Range |
|--------|------------|----------|
| COMP-LI | LinkedIn Learning | COMP-LI-01+ |
| COMP-CO | Coursera for Business | COMP-CO-01+ |
| COMP-UD | Udemy Business | COMP-UD-01+ |
| COMP-DG | Degreed | COMP-DG-01+ |
| COMP-GO | Go1 | COMP-GO-01+ |
| COMP-SK | Skillsoft | COMP-SK-01+ |
| COMP-36 | 360Learning | COMP-36-01+ |
| COMP-DO | Docebo | COMP-DO-01+ |
| COMP-CS | Cornerstone OnDemand | COMP-CS-01+ |
| COMP-XX | Emerging Players | COMP-XX-01+ |

Usage: `[COMP-LI-03]` = LinkedIn Learning evidence point #3

Full catalog: `competitors/` directory (Phase 2)

---

### Tier 8: External Sources (EXT-xxx)

Web research, public sources. (Ongoing)

| Prefix | Source Type | Example |
|--------|-------------|---------|
| EXT-G2 | G2 Reviews | EXT-G2-001 |
| EXT-CAP | Capterra Reviews | EXT-CAP-001 |
| EXT-CB | Crunchbase Data | EXT-CB-001 |
| EXT-LI | LinkedIn Company Pages | EXT-LI-001 |
| EXT-WEB | Competitor Websites | EXT-WEB-001 |
| EXT-NEWS | News/Press | EXT-NEWS-001 |
| EXT-MKT | Market Reports | EXT-MKT-001 |

Usage: `[EXT-G2-015]` = G2 review evidence #15

---

## Evidence Strength Ratings

Every evidence ID carries a confidence rating:

| Rating | Symbol | Criteria |
|--------|--------|----------|
| **HIGH** | ★★★ | Multiple sources, externally verifiable, clear methodology |
| **MEDIUM** | ★★☆ | Single source, internal data, plausible but unverified |
| **LOW** | ★☆☆ | No source cited, methodology unclear, potentially conflated |
| **NONE** | ☆☆☆ | Aspirational statement, contradicted, or no supporting data |
| **CONTRADICTED** | ⚠️ | Evidence exists that contradicts this claim |

---

## Cross-Reference Matrix

### Claim → Evidence Mapping

Every claim is linked to supporting evidence:

```
CLM-OUT-001 ("Learning shows up where needed")
├── Supporting: [none found]
├── Contradicting: [STAT-011; 67% usage outside work hours]
├── Confidence: NONE ⚠️
└── Gap Ref: GAP-C-01
```

Full mapping: `evidence/claim-evidence-map.md`

---

### Gap → Claim → Evidence Chain

Each gap traces through the full evidence chain:

```
GAP-C-02: 72% Implementation Rate
├── Claim: CLM-MET-011 [STAT-014]
├── Evidence: Internal data only
├── Methodology: Unknown
├── Confidence: LOW ★☆☆
└── Recommendation: Document survey methodology or remove claim
```

Full mapping: `evidence/data-gaps.md`

---

## Citation Templates for Report Sections

### For Strong Claims (HIGH confidence)
```markdown
Blinkist serves over 40 million users worldwide [STAT-002; ★★★], 
with a 4.7-star app store rating [STAT-003; externally verifiable].
```

### For Contested Claims (CONTRADICTED)
```markdown
The tagline "Learning that shows up where it's needed" [CLM-OUT-001] 
is contradicted by usage data showing 67% of engagement occurs 
outside work hours [STAT-011; ⚠️ contradiction].
```

### For Gap Identification
```markdown
**Evidence Gap:** The 72% implementation rate [STAT-014; GAP-C-02] 
lacks documented methodology. This claim is central to proving 
business impact but cannot be independently verified.
```

### For Recommendations
```markdown
**Recommendation:** Shift from AI-only positioning [CLM-POS-008] 
to Human+AI differentiation. Evidence: AI commoditization 
[E-WS-01, E-LDT-04, E-VID-08], human elements create defensible 
moat [E-WS-05, E-LDT-02; ★★★].
```

---

## Quick Reference: Evidence Counts

| Category | Prefix | Count | File |
|----------|--------|-------|------|
| Primary Sources | P-xxx | 3 | source-inventory.md |
| Statistics | STAT-xxx | 42 | statistics-catalog.md |
| Claims | CLM-xxx | 88 | claim-inventory.md |
| Workshop Evidence | E-WS-xx | 6 | workshop-analysis.md |
| L&D Trends Evidence | E-LDT-xx | 20 | ld-trends-top-20-findings.md |
| Video Evidence | E-VID-xx | 9 | video-analysis-ld-disrupt-ep92.md |
| Case Study Evidence | E-CS-xx | 8 | case-studies-deep-dive.md |
| Quotes | Q-xxx | 7 | quote-bank.md |
| Data Gaps | GAP-x-xx | 20 | data-gaps.md |
| Competitor Evidence | COMP-xxx | TBD | competitors/ |
| External Sources | EXT-xxx | TBD | ongoing |

**Total Evidence IDs (current):** 203+

---

## Master Evidence Index

For the final report, all evidence will be indexed in:
- `appendix/sources.md` — Full bibliography with URLs
- `appendix/evidence-index.md` — Alphabetical ID lookup
- Interactive webapp — Clickable evidence links

---

## Usage Guidelines

### When to Cite
1. **Every statistic** — must have STAT-xxx reference
2. **Every claim** — must have CLM-xxx or source reference
3. **Every recommendation** — must have evidence chain
4. **Every gap** — must have GAP-x-xx and related claims

### When NOT to Cite
1. **General observations** obvious from context
2. **Methodology explanations** (cite only the data)
3. **Future projections** (mark as analyst opinion)

### Verification Before Citing
- [ ] ID exists in relevant catalog
- [ ] Confidence rating is appropriate
- [ ] Contradicting evidence is noted if present
- [ ] URL works (for external sources)

---

## Guardrails Verification

| Guardrail | Status | Notes |
|-----------|--------|-------|
| G1: Evidence Traceability | ✅ Pass | Unified system with 200+ evidence IDs |
| G1: Source Accuracy | ✅ Pass | Confidence ratings on all evidence |
| G6: Clarity & Readability | ✅ Pass | Consistent format, easy lookup |

---

*This citation system enables G1 (Evidence Traceability) compliance throughout the comprehensive report.*

---

## Appendix: ID Format Summary

| Type | Format | Example | File Location |
|------|--------|---------|---------------|
| Primary Source | P-# | P-1 | source-inventory.md |
| Statistic | STAT-### | STAT-014 | statistics-catalog.md |
| Claim | CLM-XXX-### | CLM-OUT-001 | claim-inventory.md |
| Evidence (Workshop) | E-WS-## | E-WS-01 | workshop-analysis.md |
| Evidence (L&D Trends) | E-LDT-## | E-LDT-04 | ld-trends-top-20-findings.md |
| Evidence (Video) | E-VID-## | E-VID-08 | video-analysis-ld-disrupt-ep92.md |
| Evidence (Case Study) | E-CS-## | E-CS-01 | case-studies-deep-dive.md |
| Quote | Q-### | Q-003 | quote-bank.md |
| Gap | GAP-X-## | GAP-C-01 | data-gaps.md |
| Competitor | COMP-XX-## | COMP-LI-01 | competitors/*.md |
| External | EXT-XXX-### | EXT-G2-001 | appendix/sources.md |
