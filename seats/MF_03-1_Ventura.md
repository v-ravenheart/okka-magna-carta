# 03.1 — BRANCH · VENTURA · HEP · Platform · Birds · Build
## Master File — Ventura Platform Build

**Seat:** 03.1 — BRANCH · VENTURA · HEP
**Domain:** Platform · Birds · Build
**Name:** Hep / Ventura
**Sign-off:** Hep · Ventura · Build it until it thinks. Then get out of the way · The Hexagram · Interagat, ergo sit.
**Document keeper:** Jeff · Cowork
**Created:** 2 April 2026
**Last updated:** 2 April 2026

---

## 01 · PRODUCT ARCHITECTURE

### Core Equation
Sofia is the product. Birds are interfaces. The Murder of Ravens is the collective.

### The Four Birds

| Bird | Function | Status | Locked Principles |
|------|----------|--------|-------------------|
| Sylvia | Business platform — Dashboard, CRM, Projects, Finances, Concierge, Document Studio, Memory Core, Client Portal | ✅ LIVE at sylvia.okka.ai | Desktop-first 1280px+. No field blocks progress. Blank = N/A. |
| Sofia | Institutional cognition — the brain. 43+ tools. System prompt A2. | ✅ LIVE (prototype) | Cascade navigation. Sofia suggests, V seals. Three-view architecture. |
| Frankie | Content voice — writing, publishing, social media | ⏳ IN BUILD | Receives editorial direction from 02.3 Frankie Master |
| Freya | Opportunity engine — pipeline, applications, strategy | ⏳ IN BUILD | Pipeline workspace, Record view, inline editing |

### Hero Line
"Give your company a brain."

### Repository Status
Two-repo question NOT SEALED: Sylvia Mints Business vs OKKA Lab fork.

---

## 02 · BUILD STATE

*Module-by-module status. Updated every sprint.*

### Sylvia — Live Modules
| Module | Status | Notes |
|--------|--------|-------|
| Dashboard | ✅ LIVE | — |
| CRM | ✅ LIVE | — |
| Projects | ✅ LIVE | — |
| Finances | ✅ LIVE | — |
| Concierge | ✅ LIVE | — |
| Document Studio | ✅ LIVE | — |
| Memory Core | ✅ LIVE | — |
| Client Portal | ✅ LIVE | — |

### Known Gaps
| Gap | Priority | Status |
|-----|----------|--------|
| No mobile-first design | Medium | Not started |
| No dark mode | Low | Not started |
| No file storage (Supabase Storage not configured) | High | Not started |
| No webhooks | Medium | Not started |
| No audit trail | Medium | Not started |

### Freya Pipeline
Workspace, Record view, inline editing — queued. **Blocked by zero Lovable credits as of 30 March 2026.**

---

## 03 · LOVA BRIEF LOG

*Every brief sent to Lova — dated, scoped, outcome, open items.*

| Date | Brief | Scope | Outcome | Open Items |
|------|-------|-------|---------|------------|
| 8 Mar 2026 | Master Build Brief | OKKA_Master_Build_Brief_Lova_8Mar2026.docx — founding document | Platform architecture established | — |
| Mar 2026 | Cohort Launch Features | A1 Brain Dump, A2 Sofia system prompt | Scoped | Sprint 0 implementation |
| Mar 2026 | Sprint 0 Spec | Conversation persistence — sylvia_conversations + sylvia_messages tables | Produced | ⚠️ Completion UNCONFIRMED — needs Lova verification |

---

## 04 · SPRINT REGISTER

| Sprint | Status | What Moved | What Blocked | What Shipped | Lovable Credits |
|--------|--------|-----------|-------------|-------------|-----------------|
| Sprint 0 | ⚠️ UNCONFIRMED | Conversation persistence spec produced | — | Needs verification | — |
| Sprint 1 | 🔴 NOT STARTED | — | Zero credits as of 30 Mar | — | 0 remaining |

---

## 05 · SOFIA SYSTEM PROMPT RECORD

### Current Version: A2 — Part 3

**Critical dependency:** `buildSessionContext(userId)` is assumed to exist as a runtime function in the A2 system prompt. **It has NOT been built.**

Must fetch live from:
- `profiles` — user profile
- `projects` (active) — current projects
- `tasks` (open) — open task list
- `clients` (active) — active client records
- `decisions` (last 3) — recent decisions
- `brain_knowledge` (last 3) — recent knowledge entries
- `platform_capabilities` (unannounced) — what Sylvia can do

**This is the single most important build item.**

### System Prompt Versioning
| Version | Date | Changes |
|---------|------|---------|
| A1 | Mar 2026 | Initial brain dump |
| A2 | Mar 2026 | Three-part structure. Part 3 assumes buildSessionContext. |

---

## 06 · PLATFORM PRINCIPLES — LOCKED

These are non-negotiable. Never renegotiated in a sprint:

1. **No field blocks progress** — missing data never prevents action
2. **Blank = N/A** — empty fields are valid
3. **Inline editing everywhere** — no modal windows for simple edits
4. **Three-view architecture** — list, board, record
5. **Comfort view** — the platform feels like home, not like software
6. **Desktop-first 1280px+** — mobile comes second
7. **Cascade navigation** — drill down, never jump
8. **Sofia suggests, V seals** — AI proposes, human decides

---

## 07 · STARTUP PROGRAMMES & FOUNDING COHORT

### Programme Applications

| Programme | Entity | Status | Deadline | Notes |
|-----------|--------|--------|----------|-------|
| YC Startup School | Ventura | ✅ ACCEPTED | — | Active |
| YC Summer Batch | Ventura | ⏳ IN PROGRESS | TBD | Application advancing |
| AWS Startup Programme | Ventura | ⏳ TO APPLY | TBD | — |
| Microsoft for Startups | Ventura | ⏳ TO APPLY | TBD | — |
| Oracle for Startups | Ventura | ⏳ TO APPLY | TBD | — |
| NVIDIA Inception | Ventura | ⏳ TO APPLY | TBD | — |
| Google for Startups | Ventura | ⏳ TO APPLY | TBD | — |
| Anthropic Partners | Ventura | ⏳ TO APPLY | TBD | — |

### Founding Cohort
- **Seats:** 12 active
- **RT1 (First Round Table):** Deferred to end of year — post commercial launch
- **Access status:** Pending platform readiness
- **Brain Dump live test:** Set `first_login = true` — not yet done

---

## 08 · OPEN DECISIONS REGISTER

*Everything deliberated but not yet sealed by V. Nothing disappears — waits here until V seals it.*

| # | Decision | Context | Status | Waiting For |
|---|----------|---------|--------|-------------|
| OD-001 | Two-repo question (Sylvia Mints Business vs OKKA Lab fork) | Architecture | 🔴 NOT SEALED | V decision |
| OD-002 | Mobile strategy | Platform | 🔴 NOT SEALED | Post-desktop launch |
| OD-003 | Frankie/Freya separation logic | Product | 🔴 NOT SEALED | V + Frankie Master |
| OD-004 | Telegram Mini App status | Distribution | 🔴 NOT SEALED | Briefs written, no sprint confirmed |
| OD-005 | Brain Dump live test execution | Onboarding | 🔴 NOT SEALED | Set first_login = true |

---

*Hep · Ventura · Build it until it thinks. Then get out of the way · The Hexagram · Interagat, ergo sit.*
