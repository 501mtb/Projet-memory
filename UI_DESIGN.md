# UI Design Decisions

## UI reference assets — APK v0.1.56
**VISUALLY INSPECTED AND TRANSCRIBED**
- The seven original JPEG references in `UI/` were retrieved directly from GitHub and visually inspected.
- A detailed plain-text transcription is stored in [UI_REFERENCE_v0.1.56.txt](UI_REFERENCE_v0.1.56.txt). Read that text file as the quick-access description of the screenshots; consult the original JPGs when visual precision matters.
- Do not replace, rename, delete, or regenerate the original reference images.
- Compare the current app screens against these references before implementing UI changes.
- The images are visual references; they do not automatically prove that every screen is final/approved. Record approval screen by screen.

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


## UI reference file inventory — 2026-11-06
**Directory listing verified from GitHub:** `UI/` contains 7 JPEG screenshots and one placeholder file.

| File | Size | Visual contents |
|---|---:|---|
| `Screenshot_20261106_071858_501MTB.jpg` | 611,100 bytes | Visually inspected; see UI_REFERENCE_v0.1.56.txt |
| `Screenshot_20261106_071907_501MTB.jpg` | 600,703 bytes | Not yet visually inspected |
| `Screenshot_20261106_071913_501MTB.jpg` | 391,039 bytes | Not yet visually inspected |
| `Screenshot_20261106_071920_501MTB.jpg` | 506,454 bytes | Not yet visually inspected |
| `Screenshot_20261106_071935_501MTB.jpg` | 287,161 bytes | Not yet visually inspected |
| `Screenshot_20261106_071941_501MTB.jpg` | 221,011 bytes | Not yet visually inspected |
| `Screenshot_20261106_071948_501MTB.jpg` | 500,596 bytes | Not yet visually inspected |
| `read.me` | 1 byte | Placeholder; no useful inventory notes |

The directory listing and filenames are verified, but the GitHub file-fetch interface available in this session returned metadata only for binary JPEGs; the image pixels could not be opened here. Therefore no screen names, UI layouts, or approval statuses have been inferred. Next step: obtain viewable copies of these seven screenshots in the chat (or another image-capable route), then map each image to its screen. Do not modify or replace the originals.


## Visual inspection — APK v0.1.56 references (2026-11-06)
All seven original JPEGs in `UI/` were successfully retrieved from GitHub as base64 and visually inspected. Originals remain unchanged.

| Screenshot | Screen / state identified | Notes observed |
|---|---|---|
| `Screenshot_20261106_071858_501MTB.jpg` | Home — regular/member view | Next Ride, Past Event, Community member ride stories; bottom navigation Home / 501 Profile / Record Ride / Chat / Rider. Green-on-black theme. |
| `Screenshot_20261106_071907_501MTB.jpg` | Home — Admin Demo showcase state | Adds “SHOWCASE ADMIN MODE”, add controls and overflow menus to ride/member cards; explicitly says actions are demonstrations only. |
| `Screenshot_20261106_071913_501MTB.jpg` | Past Event detail modal | Event title, cover image, date, distance/level, time, meeting point, photo gallery, Fire / Comments / Share / Close actions. |
| `Screenshot_20261106_071920_501MTB.jpg` | 501 Profile — organization profile | 501MTB identity, About, Useful Links, Vision/Mission/Community, Team/Ride/Document spaces; bottom nav highlights 501 Profile. |
| `Screenshot_20261106_071935_501MTB.jpg` | Record Ride | Recording mode (Group Event / Individual), GPS status/map area, live performance metrics and GPS recording setup state. |
| `Screenshot_20261106_071941_501MTB.jpg` | Chat — 501MTB General | Community group chat header, group card, welcome/empty state, message composer and connection status. |
| `Screenshot_20261106_071948_501MTB.jpg` | Rider Profile — individual rider | Rider header, personal badge/ID, group statistics, individual performance, About section and settings icon. Bottom nav highlights Rider. |

### Important interpretation / limits
- These are verified visual references from APK v0.1.56, not proof that each screen is currently implemented identically or that every detail has final approval.
- The first two images are two Home states (regular and Admin Demo); the Admin Demo explicitly labels its controls as demonstrations only.
- The third image is a modal/state within Home, not a separate bottom-navigation destination.
- Settings is not represented in these seven screenshots. Do not invent its layout from these references.
- Bottom navigation in the references confirms the five destinations and ordering: Home, 501 Profile, Record Ride, Chat, Rider. 501 Profile is the organization profile; Rider is the individual profile.
- Preserve these screenshots as immutable reference assets. Use them for comparison before changing the corresponding screens; ask if a visual detail or approval status is uncertain.
