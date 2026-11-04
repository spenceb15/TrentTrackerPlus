# Trent Tracker+

**An independently developed, self-funded executive task-management dashboard built with AI assistance.**

> **Public demonstration:** All names, requests, tasks, statistics, and correspondence in this repository are synthetic. No Gmail, Calendar, Claude, or Gemini accounts are connected to this demo.

*Dashboard screenshots are available in the downloadable portfolio package; images have not yet been uploaded to this repository.*

## Project origin and ownership

I created Trent Tracker+ as a personal project to help my father organize his executive workload. I developed it in my spare time and paid the project expenses myself; the company did not fund its development. Its use case is inspired by real business operations, but the public repository contains fictional demonstration data and no live company integrations. This describes the development circumstances, not a legal determination of intellectual-property ownership.

## Overview

Trent Tracker+ was conceived in response to a practical operations problem: executive responsibilities scattered across inbox threads, meetings, and project updates. The prototype consolidates project work, requests needing attention, reply suggestions, and decision history in one interface.

## Try the demo

**[Open interactive demo](https://spenceb15.github.io/TrentTrackerPlus/)** (available after GitHub Pages is enabled).

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

Screenshots from the sanitized demo will be added once image uploads are completed. The downloadable portfolio archive includes dashboard, inbox, projects, and replies previews.

## Author

Spencer Brown — independent project initiator and self-funded developer; requirements, workflow design, AI direction, prototyping, and evaluation.

## License

MIT. This was developed personally, outside paid work and without company funding, according to the project author. Employment confidentiality and IP obligations should still be reviewed before reuse or redistribution.