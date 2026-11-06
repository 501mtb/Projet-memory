# Data and Backend Reference

## Backend
Firebase / Firestore integration and Firestore tests are part of the app work (latest reported test success must be verified). Inspect live source/configuration before changing collections, fields, queries, indexes, or security rules.

Never store private API keys, service-account credentials, passwords, or tokens here.

## Member registry
The All Members list was reported to omit some members. Before changing code, identify:
- Authoritative collection/path
- Query filters and pagination/limits
- Role/status filters
- Document IDs and member ID mapping
- Caching/state filtering
- Security rules and admin permissions

Do not fabricate member records or IDs.

## Registration and approval
Pending Approvals in Settings has been requested. Base implementation on the real registration model and secure admin authorization.

Still to confirm: pending status field and values, required registration fields, approve/reject writes, rejection reason/resubmission, audit timestamps, and notifications.

## Media
Previously supplied ImageKit configuration:
- ID: `501mtb`
- Endpoint: `https://ik.imagekit.io/501mtb`

Do not store private keys. Verify current implementation before media changes.

## Data change rule
Before schema/query changes, document current structure, migration and compatibility impact, security implications, and rollback approach. Preserve existing data.
