---
notification: patch
---

On Android, only apply `InboxStyle` when `inboxLines` has entries. Every notification without `largeBody` used to get an empty `InboxStyle`, which hid the body text when the notification was expanded.
