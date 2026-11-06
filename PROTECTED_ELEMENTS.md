# Protected Elements — Do Not Remove Without Explicit Approval

## Application continuity
- Start from the latest verified stable state of the app repository.
- Never revert to an older snapshot, branch, APK, or remembered code.
- Prefer targeted changes over whole-screen replacements.
- Do not delete existing UI, navigation, controls, data, or behavior to simplify a new task.
- Do not merge or cherry-pick a PR without user authorization.
- Never claim a PR or feature is integrated without checking GitHub.

## UI distinctions
- UI 1 and UI 2 are separate.
- **501 Profile** is the organization profile, bottom navigation position 2.
- **Rider** is the individual rider profile/performance screen, bottom navigation position 5.
- Previously developed Feed, Records, Settings, Home, and profile UI must be preserved until explicitly changed by the user.

## Build and delivery
- User prefers finishing a coherent set of changes before downloading/installing another APK.
- Compilation does not prove UI acceptance or absence of regressions.
- Review diffs and run relevant tests before reporting completion.

## Data and security
- Preserve member records and identifiers.
- Do not weaken Firestore security rules to make a screen work.
- Never commit private keys, credentials, tokens, or secrets.
- Do not replace the member-data source of truth without explicit approval.

If a requested task appears to require changing/removing a protected element, explain the impact and ask first.
