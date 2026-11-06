# Feature Register

## In progress / verify against source
- **Home / UI 1:** replace `DemoAdminHomeScreen` with approved UI 1; preserve navigation and existing UI.
- **All Members:** display the complete member registry; investigate missing members.
- **New-member approval:** add Pending Approvals workflow in Settings.

## Existing areas to preserve and inventory
- Bottom navigation and screen routing.
- 501 Profile (organization profile).
- Feed.
- Records.
- Rider personal profile/performance.
- Settings and existing controls.
- Member registration and member listing.
- Firestore integration and tests.
- Shared photo library / image handling.
- Launcher icon and Android app identity.

Verify implementation details in the current repository before modifying anything.

## Feature specification template
For each feature record user goal, entry point, roles/permissions, data read/written, loading/empty/error/success states, validation/security, offline behavior, tests, status, and user acceptance.

## Pending Approvals — requested behavior
- Show registrations awaiting review inside Settings.
- Allow an authorized administrator to approve or reject a pending registration.
- Do not expose admin actions to ordinary members.
- Preserve existing registration and member-list behavior.
- Inspect the actual Firestore model and security rules before implementation.
- Exact status fields, rejection reason, resubmission, notifications, and audit history: TO CONFIRM.
