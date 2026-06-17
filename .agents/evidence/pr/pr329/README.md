# PR 329 — Session Detail Back Button

Screenshot showing the `←` back button in `.detail-page-head` bar on the dashboard session detail page.

**Changes:**
- Back button in detail page header calls `showListView()`
- Clears `state.selectedSessionId` before returning to list (fixes stale-fetch race)
