# Trent Tracker+

**An interactive executive task-management dashboard designed with AI assistance.**

> **Public demonstration:** All names, requests, tasks, statistics, and correspondence in this repository are synthetic. No Gmail, Calendar, Claude, or Gemini accounts are connected to this demo.

![Trent Tracker+ dashboard](screenshots/dashboard.png)

## Overview

Trent Tracker+ was conceived in response to a practical operations problem: executive responsibilities scattered across inbox threads, meetings, and project updates. The prototype consolidates project work, requests needing attention, reply suggestions, and decision history in one interface.

## Try the demo

**[Open interactive demo](https://USERNAME.github.io/trent-tracker-plus/)** — replace this placeholder after GitHub Pages is enabled.

Alternatively, download `index.html` and open it locally in a browser. No install, server, API keys, or account are required. Changes made to the demo are stored in this browser's `localStorage`, not sent to a server. To reset, clear site data for this page.

## Implemented in the included prototype

- Dashboard with priorities, project summaries, and progress statistics
- Project cards, editable action items, subtasks, notes, links, and completion history
- Inbox triage panels for attention-needed items, waiting items, and proposed replies
- Copy-to-clipboard suggested reply text (does **not** send messages)
- Decision logging, trend visualizations, and task/project management
- Local browser persistence and merge logic for replacing an injected brief-data payload

## Proposed production workflow (not part of public demo)

The accompanying design envisaged scheduled AI workflows that read permitted Gmail/Calendar inputs, triage requests, create suggestions, and present recommendations for human approval. A separate Google Workspace/Gemini implementation path was explored using Apps Script and Sheets. **This repository does not implement or prove live connectors, scheduled runs, Gmail draft creation, automated sends, or production deployment.**

## Tech stack

- Vanilla HTML, CSS and JavaScript
- Embedded JSON (`brief-data-fallback`)
- Browser `localStorage`
- No runtime dependencies; no build step
- AI-assisted product specification and code development using Claude (per project records)

## Design principles

1. **Keep the human in charge:** example AI suggestions can be reviewed before any manual action.
2. **Expose context:** proposed tasks retain summaries and project associations.
3. **Keep it understandable:** one visual workspace for a busy executive.
4. **Separate demo and production:** publicly shared sample content is fictional and the demo has no account permissions.

## Evidence and limitations

The interactive UI and browser-state behavior are demonstrated in the provided file. Documentation for planned integration paths exists in the original private project but is deliberately excluded from this public repository, pending implementation and security verification. No validated time savings, rollout adoption, or production automation metrics are claimed.

## Screenshots

| Dashboard | Inbox |
| --- | --- |
| ![Dashboard](screenshots/dashboard.png) | ![Inbox](screenshots/inbox.png) |
| ![Replies](screenshots/replies.png) | ![Projects](screenshots/projects.png) |

## Author

Spencer Brown — project requirements, workflow design, AI direction, prototyping and evaluation.

## License

MIT. Before publishing, verify your employer has authorized public release of any work-developed intellectual property, even when sample data has been substituted.