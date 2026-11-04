# Case Study — Trent Tracker+

## Project origin

I independently started and funded Trent Tracker+ in my spare time to help my father with a demanding executive workload. The company did not fund this personal development project. The intended user and business context informed the problem definition; the public demo uses fictional data and is disconnected from business accounts.

## Challenge

A food-service operations executive faces fragmented project management across emails, scheduling information, notes, and decisions. The original project aimed to reduce the cognitive load of organizing incoming requests and tracking follow-through. The project owner estimated that email consumed many hours of the executive's day; that estimate was an initial problem statement, not a measured outcome.

## My contribution

I defined the user problem, specified a review-first email triage model, set product constraints, and directed AI-assisted prototyping with Claude. The resulting HTML/CSS/JavaScript dashboard demonstrates the interaction model and local project-management functions.

## Prototype capabilities — verified from source

The included HTML contains dashboard, projects, action items, notes, decision log, trends, completed-work, inbox triage, and proposed reply views. It stores user changes in browser localStorage. It can display externally generated JSON brief data if injected into the document. Suggested replies are copied, not transmitted.

## Proposed AI architecture — not verified in production

Planned processing was divided into attention-needed decisions, routine reply recommendations, and handled items. Scheduled Claude-based workflows and a separate Google Workspace/Gemini path were documented, but the public prototype includes neither working Google connectors nor a scheduled service.

## Human oversight and risk

The design calls for no autonomous sends; sensitive or policy-related communications should be escalated rather than answered using unverified AI knowledge. An operational version would need actual consent, access controls, retention policies, approval logging, prompt-injection defenses, and production tests before processing real accounts.

## Lessons and next steps

A useful AI-assisted product does not need autonomous control of every workflow. A focused dashboard, clear data contract, and explicit human approval path can simplify the interface before integrating sensitive systems. Next steps are a tested permissioned backend, server-side persistence, end-to-end integration tests, and metrics from an approved pilot.
