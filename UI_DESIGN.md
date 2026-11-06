# UI Design Decisions

## UI reference assets — APK v0.1.56
**USER-REPORTED / SOURCE TO INSPECT**
- The user has already placed the UI reference materials from APK version **0.1.56** in the `UI` folder of this memory repository.
- Treat these assets as the visual reference set for documenting and comparing the app interfaces.
- Before changing any UI, inspect the contents of `UI/` and identify each screen/image and its filename. Do not replace, rename, delete, or regenerate these references.
- Compare the current app screens against these references before implementing UI changes.
- If a reference image is ambiguous or a screen is missing, ask the user rather than inventing its design.
- The assets are reference material; they do not automatically prove that every screen is final/approved. Record approval screen by screen.

## Global navigation
**APPROVED**
- Bottom navigation position 2: **501 Profile**, the organization profile.
- Bottom navigation position 5: **Rider**, an individual member's personal profile/performance screen.
- These are different screens and must never be conflated.

## UI 1 and UI 2
**TO VERIFY / DOCUMENT**
- UI 1 is distinct from UI 2.
- Current reported task: replace the admin demo Home screen with the approved UI 1.
- Preserve previously worked-on screens and components. Do not rebuild either UI from memory.
- Use the v0.1.56 reference assets in `UI/` as the visual comparison baseline where applicable.

## Screen inventory
For each screen record status, purpose, layout, navigation, actions, data source, loading/empty/error states, responsive behavior, protected elements, source files, reference-image filename, and user approval.

| Screen | Current record |
|---|---|
| Home | UI 1 replacement for admin demo requested; live implementation TO VERIFY |
| 501 Profile | Approved organization profile; distinct from Rider |
| Feed | Existing Feed UI work must be preserved; details TO DOCUMENT |
| Records | Existing Record UI work must be preserved; details TO DOCUMENT |
| Rider | Individual rider profile/performance; bottom navigation position 5 |
| Settings | Pending new-member approval requested; preserve existing UI |
| All Members | Complete list reported incomplete; fix without removing features |

A screen is not approved merely because it compiles or renders. Compare it with the user's approved design and record explicit acceptance.
