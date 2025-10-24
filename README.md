# OKKY Service Specification (Docs Repo)

This repository manages **planning, UX, operations, and policy** specifications for the current OKKY web service (https://okky.kr/), 
and serves as the baseline for **future feature improvements and service redesign plans**.

---

## Goals
- Track the **current state** of OKKY (IA, policies, operations) as the single source of truth.
- Propose and review **Change Proposals (RFCs)** via Issues/PRs.
- Keep a clear **decision history** and **changelog**.

---

## Repository Structure

```
OKKY-doc/
 ├─ README.md
 ├─ 00_Guidelines/
 │   ├─ CONTRIBUTING.md
 │   ├─ NAMING_RULES.md
 │   └─ TEMPLATES/
 │      ├─ TEMPLATE_SpecDoc.md
 │      ├─ TEMPLATE_RFC.md
 │      ├─ TEMPLATE_UXFlow.md
 │      └─ TEMPLATE_Policy.md
 ├─ 01_Current_State/                 # Baseline docs describing today's OKKY
 │   ├─ IA/
 │   │  └─ Menu_Hierarchy_Code.md
 │   ├─ Policies_Snapshot/
 │   │  └─ README.md
 │   ├─ Operations_Snapshot/
 │   │  └─ Roles_and_Permissions.md
 │   └─ UX_Snapshot/
 │      └─ UX_Principles.md
 ├─ 02_Change_Proposals/              # RFCs for changes (one folder per proposal)
 │   └─ README.md
 ├─ 03_Policy/                        # Working policy docs
 │   └─ README.md
 ├─ 04_UX/                            # Working UX docs (flows, wireframes links)
 │   └─ README.md
 ├─ 05_Operations/                    # Working ops docs (moderation, content mgmt)
 │   └─ README.md
 ├─ 99_Archive/                       # Archived/replaced specs and notes
 │   └─ README.md
 ├─ CHANGELOG.md
 └─ DECISION_LOG.md
```

> **Scope**: No frontend/backend code. Documentation only (planning/UX/operations/policy).

---

## Workflow (Step-by-step)

1. **Create labels** (see `.github/labels.json`).
2. Enable protections: require PR reviews for `main`, enable branch protection rules.
3. Use **Issues** for discussions; open **PRs** for changes from feature branches.
4. Each change: update related docs + **CHANGELOG.md** + **DECISION_LOG.md** (if applicable).
5. Keep **01_Current_State** as the audited baseline; update via PR when reality changes.

### Branching
- `main`: approved documents
- `feature/<short-topic>`: work branches for changes

### Commit Convention (suggested)
```
docs(planning): add baseline IA doc
docs(policy): refine moderation policy
docs(ops): update roles and permissions
docs(ux): add sign-up user flow draft
chore: repository housekeeping
```

---

## First Tasks
- [ ] Fill `01_Current_State/IA/Menu_Hierarchy_Code.md` (seeded here).
- [ ] Review `NAMING_RULES.md` and confirm as the standard.
- [ ] Create initial **milestones** (Baseline Audit, Q4 Improvements, 2026 Redesign Plan).
- [ ] Log first decisions in `DECISION_LOG.md`.
- [ ] Track all edits via Issues/PRs.
