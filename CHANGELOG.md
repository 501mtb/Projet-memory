# Project Memory Changelog

Add newest entries at the top.

## 2026-11-06 — UI reference assets identified
- User reports that the UI references from APK version **0.1.56** are already placed in the `UI/` folder of this memory repository.
- Added this as the visual reference baseline in `UI_DESIGN.md`.
- Next: inspect and inventory the actual contents of `UI/`; preserve all files and map each reference to its screen. No UI implementation change is authorized by this note alone.

## 2026-11-06 — Memory repository initialized
- Confirmed repository: `501mtb/Projet-memory`, public, default branch `main`.
- Expanded the existing README into the project memory index and mandatory workflow.
- Added initial status, UI decisions, feature register, backend notes, protected elements, and this changelog.
- Recorded app technical state and pending tasks as **reported / to verify**, not confirmed live Git state.

### Starting context from recent conversation — verify live
- App `main` reported at `d6f1520`.
- PR #20 reported open and not merged.
- `df51160` reported compiled successfully; Firestore tests passed; debug APK reported available.
- PR #13 reported closed without merging.
- Pending: UI 1 Home replacement, complete All Members list, Pending Approvals in Settings.

## Entry template
### YYYY-MM-DD — Short description
- App repo / branch:
- Starting commit / PR:
- Changed files:
- Changes:
- Preserved:
- Checks and results:
- User acceptance:
- Remaining work:


## 2026-11-06 — UI folder inventory
- Verified the `UI/` directory in `501mtb/Projet-memory` contains seven JPEG screenshot files and a 1-byte `read.me` placeholder.
- Recorded exact filenames and byte sizes in `UI_DESIGN.md`.
- Binary image contents could not be visually inspected through the available GitHub fetch response, so screen identities and design details remain unclassified.
- No screenshot was changed, renamed, deleted, or replaced. No application source was modified.
- Next: inspect viewable copies of the seven screenshots and map each to its screen before any UI implementation.


## 2026-11-06 — Retrieved and visually inspected APK v0.1.56 UI references
- Retrieved all seven JPEG screenshots directly from `501mtb/Projet-memory/UI/` using GitHub file content in base64; no re-upload from the user was needed.
- Visually identified: Home regular view, Home Admin Demo view, Past Event detail modal, 501 Profile, Record Ride, Chat, and Rider Profile.
- Recorded visible screen details and navigation order in `UI_DESIGN.md`.
- Confirmed the references show bottom navigation: Home / 501 Profile / Record Ride / Chat / Rider. The 501 Profile is the organization profile; Rider is the individual profile.
- Noted that Settings is absent from the supplied references and must not be designed by assumption.
- No original screenshot or application source file was modified.
