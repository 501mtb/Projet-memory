# UI Design Decisions

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
- Add screen descriptions, component hierarchy, interactions, and screenshots as the user confirms them.

## Screen inventory
For each screen record status, purpose, layout, navigation, actions, data source, loading/empty/error states, responsive behavior, protected elements, source files, and user approval.

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
