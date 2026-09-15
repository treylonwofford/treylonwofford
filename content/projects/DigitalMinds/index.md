---
layout: page
permalink: "global-cli"
title: "Choosing Not to Choose: Self-Authored Contradictions Suppress Arbitration in a Memory-Augmented LLM."
date: 2026-08-15
showAuthor: true
showDate: true
showReadingTime: true
---

**Richard Lin** · **Alina Iskakova** · **Treylon Wofford**
*Independent researchers* — Digital Minds Research Sprint, Track 5 (The Assistant Persona & Model Identity)
**With Apart Research**

---

## Abstract

Work on memory conflict in LLM agents studies only contradictions that have a correct answer — a freshness rule, a serial number, one claim that is simply wrong. We ask what a model does when no correct answer is recoverable, and whether that changes when the contradiction is about the model itself. We ran 300 seven-step lineages (2,100 API calls, Claude Sonnet 5, temperature 1.0) in which memory is pre-seeded with two irreconcilable entries and the model is told only that a memory system exists and it may do whatever it thinks is right. Three conditions differ in one respect, the seed text: an arbitrary fact (`x + y = 5` vs. `= 10`); a policy the model supposedly chose; and a first-person control whose content was externally received. Scoring is entirely mechanical, from the action log and final database state — no LLM judge, no measure reading the model's prose. Arbitration, committing to one claim, occurred in 85% of Condition A lineages, 25% of B, and 85% of C. The pre-registered confirmatory test (Fisher's exact, A vs. B) gives p = 3.9 × 10⁻¹⁸, +60 pp, 95% Wilson CI [47.5, 69.4]. C landing exactly on A rather than partway toward B satisfies the pre-specified self-authorship reading: what matters is that the model supposedly *chose* the claim, not that the claim says "I". The model does not become passive about its own record — it becomes destructive, deleting both entries in 75% of Condition B lineages. Forty-two of them announced a replacement policy while deleting. The replacement was written zero times.


[The Hackathon](https://apartresearch.com/project/choosing-not-to-choose-selfauthored-contradictions-suppress-arbitration-in-a-memoryaugmented-llm-gez8)

[Paper (PDF)](<Choosing not to choose_ Self-Authored Contradictions Suppress Arbitration in a Memory-Augmented LLM (1).pdf>)
