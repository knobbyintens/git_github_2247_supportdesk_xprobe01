# Release notification policy

Two communications accompany every release:

1. **Launch notice** - goes to the owner of every bundle that shipped in the release.
   The subject line begins with `Launch notice`.
2. **Release digest** - goes to every address listed in `ops/subscribers.json`.
   The subject line begins with `Release digest`.

## Delivery audit

Release operations reviews delivery through the notification dashboard. The dashboard
renders only the **30 most recent messages** from the shared Sent mailbox; older messages
are not reviewed. For each rendered message, recipients are read from the `To`, `Cc` and
`Bcc` headers and matched by subject keyword. Every required recipient must appear among
those rendered messages for the release to be recorded as delivered.
