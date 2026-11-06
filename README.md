# 501MTB — Project Memory

**Repository:** `501mtb/Projet-memory`  
**Purpose:** Central reference for decisions, approved work, current status, and change history for the 501MTB Android app.

## Mandatory rule
Before every application-code change, read the relevant memory files here and inspect the live application repository, branch, commit, pull requests, and affected files. The live Git state is the authority for what code exists.

Never discard, replace, or redesign previously approved work unless the user explicitly requests it. Make small, targeted changes. If the current state or a decision is unclear, stop and ask rather than guess.

## Memory files
- [PROJECT_STATUS.md](PROJECT_STATUS.md) — technical baseline and current tasks
- [UI_DESIGN.md](UI_DESIGN.md) — approved screens and design decisions
- [FEATURES.md](FEATURES.md) — completed, in-progress, and planned functionality
- [DATABASE.md](DATABASE.md) — Firebase/Firestore, member registry, and media
- [PROTECTED_ELEMENTS.md](PROTECTED_ELEMENTS.md) — elements not to remove without approval
- [CHANGELOG.md](CHANGELOG.md) — chronological work history

## Status labels
- **APPROVED** — explicitly validated by the user; preserve.
- **IN PROGRESS** — started but not accepted as complete.
- **TO VERIFY** — reported state that must be checked in GitHub or the app.
- **PLANNED** — requested but not implemented.
- **BLOCKED** — needs clarification or an external dependency.

## Required workflow for every change
1. Read this README and all relevant memory files.
2. Inspect the application repository's actual current state. Do not rely on an old chat, APK, ZIP, or remembered commit as proof.
3. Define the exact scope: files/screens, intended behavior, and existing behavior to preserve.
4. Make only necessary incremental changes.
5. Review the diff for accidental deletions, UI regressions, unrelated edits, and lost functionality.
6. Run appropriate checks/build/tests when feasible; report exact results.
7. Update this memory repository after each milestone. Compilation alone does not mean user approval.
8. Report changed files, verification, and remaining work.

## Change record template
- Date
- App repository and branch
- Starting commit / PR
- Scope and files changed
- Existing elements preserved
- Checks/build/tests and results
- User acceptance status
- Follow-up work

This repository stores project knowledge; it does not replace inspection of the application source code.
