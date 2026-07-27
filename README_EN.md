# Legal Exam Prep Skill

> An OpenClaw Skill that helps law-school students pass the **National Unified Legal Professional Qualification Examination (China Bar Exam / 法考)**.
> Built around **lookup + practice**, with **authoritative, traceable** content. Covers both the objective and subjective stages across all 18 subjects.
> Because the Ministry of Justice stopped publishing real questions after 2018, this Skill fills the practice gap with statute-based syllabus + trend-driven mock questions.

[中文 README →](./README.md)

---

## Why this Skill

The China Bar Exam is notoriously difficult. Key challenges and how this Skill addresses them:

| Challenge | Detail | Skill's Response |
|-----------|--------|------------------|
| Two-stage exam | Objective (300 pts, valid 2 yrs) → Subjective (180 pts: case / document / essay) | Full coverage of both stages |
| 18 subjects | Vol.1 (9) + Vol.2 (9), uneven weighting | Searchable by volume / subject / system |
| No official questions | MOJ stopped releasing real Q&A after 2018; only unofficial "recall" versions exist | Trend-driven mocks + pre-2018/recall, clearly labeled by source |
| Annual statute changes | 2024 new Company Law, 2023 Amendment XII to Criminal Law, new Admin. Reconsideration Law | New-law-first; each point cites the latest effective version |
| High authority bar | One wrong statute breaks many points | Layered traceability (L1–L5), every claim cited |

This Skill centers on **lookup + practice**, helping candidates study systematically, drill precisely, and trace every source — even without official past papers.

---

## Four Core Modules

### 1 · Knowledge Lookup
Search by subject / topic / statute / point and get a "knowledge card":
- Core elements (quick recall) + legal effect
- Statute basis (L1–L4 levels + specific articles)
- Common confusions + memory aids
- Linked real / mock questions

**Triggers**: *"What are the elements of bona fide acquisition?"* · *"Defensive counterplea under Art.20 Criminal Law"*

### 2 · Objective Practice
Generate / call single, multiple, and indefinite-choice questions, each with:
- Stem + answer + option-by-option analysis
- Point mapping (which statute)
- Error analysis (trap identification)
- Strategy hints

**Triggers**: *"Give me an objective single-choice Q on the new Company Law, with analysis"*

### 3 · Subjective Training
Train the three subjective question types:
- **Case analysis**: Conclusion + Statute + Analysis + Restate, with scoring points
- **Legal document**: complaint / answer /代理词 / judgment format framework
- **Essay**: Xi Jinping Thought on Rule of Law / jurisprudence "total–divide–total" structure

**Triggers**: *"Write a worked civil-contract case-analysis exemplar"*

### 4 · Mock Generation
Syllabus + new-statute + trend-driven mocks in five flavors:
- New-statute questions · Cross-subject · Trap · Hot-case · Cognitive-progression

> ⚠️ All mocks are **explicitly labeled `【Mock · Not Real】`** and never presented as official.

---

## Authoritativeness

Every output cites its source, following a layered standard (see `references/authoritative-sources.md`):

| Level | Source | Example |
|-------|--------|---------|
| L1 | Statutes (NPC & Standing Committee) | Civil Code, Criminal Law, Company Law (2024) |
| L2 | Judicial & legislative interpretations | SPC/S PP interpretations, Self-Defense Guidance |
| L3 | Administrative regulations & rules | State Council regs, ministry rules |
| L4 | MOJ Syllabus + Law Press textbooks (9-vol set) | Scope & emphasis |
| L5 | SPC guiding &公报 cases | Subjective case material |
| L6 | Scholarly consensus (auxiliary only) | Hard-case perspective |

> **Currency first**: New law supersedes old. Revised statutes are always cited at their latest effective version with enactment date.

### Integrity boundary
- No official questions after 2018; only unofficial "recall" versions exist.
- Generated questions are **explicitly labeled `【Mock · Not Real】`** and **never** presented as official.
- Real / recall / mock are **clearly distinguished** by source tag.
- Anything unverifiable is marked `【To Verify】` with a pointer to the latest official source.

---

## Repository Layout

```
legal-exam-prep/
├── SKILL.md
├── references/   (8 docs)
├── templates/    (8 templates)
├── examples/     (4 worked examples)
└── docs/images/  (12 flowcharts: 7 architecture + 5 demo)
```

## Flowcharts

### Architecture
| Image | Content |
|-------|---------|
| `system-overview-en.svg` | System overview: 4 modules + traceability base |
| `exam-structure-en.svg` | Exam structure: objective → subjective |
| `question-types-en.svg` | Question types distribution |
| `knowledge-query-en.svg` | Knowledge-point lookup flow |
| `practice-loop-en.svg` | Practice loop: drill → analyze → diagnose → consolidate |
| `mock-generation-en.svg` | Mock-question generation (clearly non-real) |
| `study-workflow-en.svg` | Full study workflow |

### Demos (how to actually use it)
| Image | Demonstrates |
|-------|--------------|
| `demo-knowledge-lookup.svg` | From one question to one traceable knowledge card |
| `demo-objective-practice.svg` | Objective drill → answer → analysis → error log → review loop |
| `demo-subjective-training.svg` | Subjective 5-step method |
| `demo-mock-question.svg` | Generate one mock question end-to-end |
| `demo-end-to-end.svg` | A candidate's one-day prep flow |

---

## Quick Start

1. **Lookup**: ask *"elements of bona fide acquisition"* → get a card with statute basis.
2. **Practice**: *"an objective Q on the new Company Law, with analysis"*.
3. **Subjective**: *"a worked civil-contract case-analysis exemplar"*.
4. **Plan**: *"a 12-month zero-base study plan"*.
5. **Mock exam**: *"a 100-Q Vol.2 objective mock paper"* for timed self-test.

> Tip: you can always ask to *"cite the statute"* or *"use the 2024 new law"* to trigger traceability.

## 18 Subjects

**Vol.1 (100 Q / 150 pts)**: Xi Jinping Thought on Rule of Law, Jurisprudence, Constitutional Law, Chinese Legal History, Public Int'l Law, Judicial System & Ethics, Criminal Law, Criminal Procedure, Administrative Law.

**Vol.2 (100 Q / 150 pts)**: Civil Law, IP, Commercial Law, Economic Law, Environment Law, Labor Law, Private Int'l Law, Int'l Economic Law, Civil Procedure (with arbitration).

The subjective paper draws from the above, emphasizing Criminal/Civil/Commercial/Administrative/Civil-Procedure Law plus one essay (rule-of-law thought).

## FAQ

**Q1: Does this provide official real questions?** No, and it does not claim to. Post-2018 MOJ stopped releasing them; we use pre-2018 / recall (tagged) / self-generated mocks (tagged non-real).

**Q2: Are mocks as hard as real questions?** Mocks train thinking and gap-finding per syllabus/trends; they are not equivalent to real difficulty or direction. Defer to official materials.

**Q3: Do statutes go stale?** Yes. We follow new-law-first, but laws change; always defer to the latest NPC/MOJ text.

**Q4: Can it write my full subjective answer?** It can produce a worked exemplar with scoring points, but we recommend you handwrite first, then compare.

## Important Disclaimer

- This Skill is a **study aid**; all content is generated from public syllabi and legal texts.
- It does **not provide or claim** any official exam questions or model answers.
- Mock questions are for practice only and are not affiliated with the Ministry of Justice.
- Always defer to official MOJ announcements and the latest laws.

## License & Citation

MIT License — see [LICENSE](./LICENSE). Citation: see [CITATION.cff](./CITATION.cff).
