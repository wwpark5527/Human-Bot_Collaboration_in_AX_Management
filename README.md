# Human–Bot Collaboration in AX Management

**A machine-structured knowledge vault derived from the book _AX Management: How Humans and Bots Collaborate_ by Won-Woo Park.**

*Every concept in the book is turned into a verifiable reasoning path — Identity → Goal → Task → Knowledge → Method → Skill — so that a management idea becomes a derivation, not just a definition.*

- Author of the source book: **Won-Woo Park**
- Corpus: _AX Management: How Humans and Bots Collaborate_ (AX = AI Transformation)
- Run: `20260719_164605` · 369 concepts closed into skills

---

> **A skill in an AX organization is not a list of abilities — it is a path.** This repository takes each idea in the book and reconstructs *why* it is needed and *how* it becomes an operable skill.

This vault applies the **Identity-driven Skill Derivation Knowledge Chain** to an entire management book. Rather than storing the book as prose, it extracts each named concept, role, structure, method, index, and principle, and derives each one along a semantic chain into a concrete skill. The result is a graph you can query, verify, and reason over — where every link is the *result* of a validation, not a guess.

## The Source Book

The book studies how humans and **bots** (collaborative, governance-embedded AI) coexist and work together as an organization undergoes **AX (AI Transformation)** — the shift, beyond DX (Digital Transformation), in which AI enters the core of an organization's judgment, roles, authority, and accountability structures.

| Part | Theme | Representative concepts |
|---|---|---|
| **Part 1** | The Human–Bot coexisting, collaborating **AX organization** | AX, DX, Organizational AX, AX Organization, Personal AX; the augmented bot / augmented human |
| **Part 2** | Talent, competencies, roles, leadership · **bot socialization & HBRM** | survival vs. leadership competencies; HBRM (Human–Bot Resource Management); AH/AB augmentation indicators |
| **Part 3** | **Team Role Balance (TRB)** | Belbin's 9 team roles, team role vs. functional role, team-role balance |
| **Part 4** | **Common & Governance Context and the Knowledge Chain** · inclusive transition, AX & ESG | common context, governance context, local/network environments, predictive-intelligence stack, ESG |

## The Method — Identity to Skill

The minimal unit of knowledge is a single typed link. Chained together, they form a reasoning path from an identity to the skill it requires:

```
Identity → Goal → Task → Knowledge → Method → Skill
```

Each of the 369 concepts is closed into a **6-file derivation**:

| File | Role |
|---|---|
| `_identity/<NAME>.md` | the concept: definition, decision criteria, output, source evidence, provenance |
| `_goal/…_goal.md` | the goal the identity defines |
| `_task/…_task.md` | the task the goal requires |
| `_knowledge/…_knowledge.md` | the knowledge the task requires |
| `_method/…_method.md` | the method the knowledge is applied through |
| `_skill/<NAME>/SKILL.md` | the terminal skill the method develops |

A completed chain is not a mere connection but a structural record that *this skill was justifiably derived from this concept in the book*.

## The 369 Concepts

Extracted from the book and classified by inherent kind:

| Type | Count | Meaning |
|---|---|---|
| CONCEPT | 145 | a named idea |
| STRUCTURE | 131 | a named structural arrangement |
| METHOD | 36 | a named way of doing |
| INDEX | 27 | a measurement indicator |
| ROLE | 25 | a named role |
| PRINCIPLE | 5 | a standing principle |
| **Total** | **369** | 317 fragmented children · 52 standalone |

Concepts are ordered by **WalkOrder**, the sequence of the knowledge chain that follows the book's own progression.

## Repository Layout

| Folder | Contents |
|---|---|
| `_identity/` | the 369 concept definitions (one file per concept) |
| `_goal/` `_task/` `_knowledge/` `_method/` `_skill/` | the derivation chain from each identity to its skill |
| `_artifact/` | the build record — per-concept closure artifacts + the pipeline-stage artifacts (Stage 1–5), harvest notes, handoffs, and superseded runs |
| `_input/` | the source book, split into chapter documents |
| `_entity/` | realization records and composition entities (agent · workflow · composite · edge · sequence · etc.) |
| `_rule/` `_deploy/` `_validation/` `_source/` `_memory/` | governance, deployment, validation, sourcing, and memory surfaces |
| `pdf/` | the book PDFs (EN / KR) |

## How It Was Built — The Pipeline

The vault was produced by a staged, source-grounded pipeline, each stage leaving an auditable artifact under `_artifact/`:

1. **Stage 1 — Source-linked extraction.** Read each chapter; extract candidate concepts with verbatim evidence, source lines, and a structural role.
2. **Stage 2 — Identity fragmentation.** Settle each candidate into a single identity (keep / split / collapse), with the 9 required fields.
3. **Stage 3 — Knowledge-chain ordering.** Place every identity in a single WalkOrder that respects the book's sequence and dependencies.
4. **Stage 4 — Concept-to-skill closure.** For each candidate, mint the 6-file chain and gate it on 12 PASS conditions (link closure, interlock, conformance) before sealing.
5. **Stage 5 — Feedback.** Ledger, patch seeds, and the next-run seed packet.

Every derived fact (a required skill, a link) is *computed from the chain* and grounded in the book — no free-floating assertions.

## A Note on Language

The concepts originate in the Korean book; the vault is being provided in English. Concept identifiers, IDs, links, and source-document paths are kept verbatim (a path may still contain the original Korean filename), while definitions, criteria, evidence quotes, and prose are rendered in English.

## Companion Work

This vault operationalizes a family of ontology papers on AI-augmented (AX) organizations:

- **Identity-driven Skill Derivation Knowledge Chain** — the base Identity→Skill ontology
- **Knowledge-Chain Deployment Index (KCDI)** — measuring whether a validated skill actually operated in the field
- **Principle–Rule Projection & the GovernedSkill** — governing a derived skill for safe execution
- **Principle–Rule Projection and Traceable Execution** — context assignment, flow, step execution, and dependency handoff in multi-agent operation

---

*The knowledge chain is not a format for storing a book, but a grammar for expressing and validating how each of its ideas is justifiably derived into an operable skill for an organization where humans and bots collaborate.*
