# Community contribution filing drafts

All eight tools are standalone static pages with no dependencies, login, upload, analytics, or server-side processing. The tools are English-first and link to the official source for the facts each uses. File each tool page as a separate `build` only after its hosted URL is available.

## 1. VEC Board Coverage Planner

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/board-coverage/
- **What it is, and who it helps:** An offline calculator for the published overall-standing formula. Participants enter board names and scores; blank boards count as zero, each task is averaged across its listed boards, and the three task means are summed. The starting board list is editable because the roster changes by phase. It exports a CSV planning report and does not predict scores or infer hidden targets.
- **How someone else runs it:** Open the hosted page, edit the board rows to match the current phase, enter best scores, and choose Calculate. Add/remove rows as needed. Export CSV saves the calculation locally.

## 2. VEC Generality Architecture Mapper

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/generality-map/
- **What it is, and who it helps:** A guided architecture worksheet for teams considering the Generality Award. It checks that at least two tasks are selected, prompts a clear account of the shared architecture and task-specific heads/inputs, and drafts a method-summary paragraph. It explicitly explains that the organisers judge the actual method and that the tool is not an eligibility ruling.
- **How someone else runs it:** Select tasks, describe common model components and task-specific differences, confirm whether the same underlying architecture is used, and draft/copy the statement. No inputs leave the page.

## 3. VEC Team Contribution Ledger

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/team-ledger/
- **What it is, and who it helps:** A local, exportable record of contributor, concrete work, date, work type, and optional artifact reference. It helps teams credit genuine contributions and prepare a handoff without claiming to settle authorship or disputes.
- **How someone else runs it:** Add one record at a time, then export CSV for a spreadsheet or Markdown for a report. Data is held only in the open page and is not uploaded.

## 4. VEC Compute Budget Estimator

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/compute-budget/
- **What it is, and who it helps:** A pre-run memory calculator for prediction arrays. It uses the official T1 gene count or T2/T3 panel size and includes spatial coordinates for T2/T3. A selectable planning multiplier exposes temporary-array overhead assumptions instead of presenting raw matrix size as total RAM.
- **How someone else runs it:** Select a task, enter a prediction cell count, and choose a planning multiplier. The page reports raw matrix bytes and the multiplied planning allowance. It does not read data or claim to predict total peak memory.

## 5. VEC Deadline Calendar Exporter

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/calendar/
- **What it is, and who it helps:** A calendar export for the official 2026 Challenge milestones. Events are all-day because the published timeline supplies dates rather than time-of-day deadlines; every event points back to the authoritative timeline.
- **How someone else runs it:** Choose which milestones to include, then download and import the `.ics` file. Check the official timeline for changes before relying on it.

## 6. VEC Experiment Plan Card

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/experiment-card/
- **What it is, and who it helps:** A prospective experiment worksheet capturing a falsifiable hypothesis, inputs, evaluation method, metrics, and candidate-selection rule before results are viewed. It complements after-run provenance logs by making the planned decision process portable as Markdown.
- **How someone else runs it:** Fill in the fields and create, copy, or download the Markdown card. It is not a preregistration service and cannot decide whether data are eligible.

## 7. VEC Team Eligibility Checklist

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/team-check/
- **What it is, and who it helps:** A private checklist for team formation: captain age, genuine contribution, team size, one account/one team, excluded groups, institutional permission and representation, and the Agent Team lock/evidence reminders. It requests no names or contact details.
- **How someone else runs it:** Review and mark each requirement, select the track, and export the status summary. The result is a planning record, not organiser approval.

## 8. VEC Data-use Readiness Checklist

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/data-use/
- **What it is, and who it helps:** An offline recordkeeping checklist for external-source disclosure, license/source notes, Challenge-data acknowledgement, and prior written approval before publishing or publicly presenting the unpublished Challenge dataset. It makes the distinction between participant recordkeeping and actual organiser/data-generator approval explicit.
- **How someone else runs it:** Mark confirmed items, add source and approval-record references without pasting private correspondence, and download Markdown. It is not a legal opinion or data-eligibility decision.

## Second set: community participation tools

### 9. Good First Contribution Finder

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/contribution-finder/
- **What it is, and who it helps:** A private idea matcher for people who want to help but do not know where to start. Time, interests, and available resources filter concrete tasks with a suggested finish artifact. It includes options that need only a browser and prompts contributors to check the existing directory.
- **How someone else runs it:** Choose time, interest, and resources; select a suggested idea; fill in the intended audience and “done” check; then copy or download a Markdown plan. Nothing is sent to a server.

### 10. Help Request Builder

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/help-request/
- **What it is, and who it helps:** A structured support-request composer that records expected and actual behavior, steps to reproduce, environment, smallest safe example, and previous attempts. A privacy checklist reminds participants to remove Challenge data, unpublished results, credentials, and private correspondence. It helps newcomers ask questions others can answer.
- **How someone else runs it:** Fill in the labeled fields, confirm the sharing checks, generate the Markdown issue/question, and choose the public destination yourself. The page does not send the request.

### 11. Contribution Brief Builder

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/contribution-brief/
- **What it is, and who it helps:** A scope worksheet for turning an observed community barrier into one bounded deliverable. It prompts intended audience, out-of-scope work, observable acceptance checks, evidence of usefulness, accessibility, and maintenance. This helps a first-time contributor propose something reviewable rather than an open-ended idea.
- **How someone else runs it:** Describe the user need, select one deliverable, fill in acceptance and access checks, then export a Markdown brief to share or use privately.

### 12. Community Resource Review

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/resource-review/
- **What it is, and who it helps:** A reproducible review template for a public VEC guide, tutorial, or tool. It captures the intended audience, setup conditions, actual outcome, concrete blocker, and one proposed fix. It helps participants improve existing resources and keeps reviews grounded in what the reviewer actually tried.
- **How someone else runs it:** Enter the exact public resource and test conditions, mark only checks completed, describe the blocker and fix, then export the review note. Do not include private data or credentials.

### 13. Accessibility Review Checklist

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/accessibility-review/
- **What it is, and who it helps:** A first-pass accessibility review for public tools, tutorials, visual materials, and sessions. It prompts concrete checks for keyboard use, focus, labels, zoom, color, alt text/captions, plain language, compute/bandwidth access, and motion. Reviewers record conditions and fixes without making diagnoses or claiming certification.
- **How someone else runs it:** Record the public item and test setup, mark only the checks performed, describe observed barriers and a small fix, then export the note. It is a practical review aid, not a formal conformance audit.

### 14. Peer Session Agenda Builder

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/workshop-agenda/
- **What it is, and who it helps:** A time-budgeting tool for peer walkthroughs, reading groups, and troubleshooting sessions. It divides a selected session length into welcome, context, demonstration, hands-on practice, and debrief, and prompts a low-setup access plan. It helps community members host focused learning sessions without designing an agenda from scratch.
- **How someone else runs it:** Choose a 30–180 minute session, edit the segment names and access plan, generate the schedule, then export it as Markdown. It is a planning aid, not an official curriculum.

### 15. Discussion-to-Action Notes

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/decision-actions/
- **What it is, and who it helps:** A lightweight note template that separates agreed decisions from open questions and actions after a peer discussion. Actions include an observable finish and role/alias, without collecting private contact details. It helps small volunteer groups avoid losing work between sessions.
- **How someone else runs it:** Record the shared question, decisions, open issues, next actions, blockers, and public references; complete the privacy checks; export Markdown for the group.

### 16. Project Handoff Card

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/handoff-card/
- **What it is, and who it helps:** A reusable handoff document for a community tool, guide, or analysis. It captures a clean start, current state, key public artifacts, decisions, next steps, blockers, verification method, and freshness limits. It reduces reliance on private walkthroughs and makes it easier for a new volunteer to take one bounded step.
- **How someone else runs it:** Fill in public links, exact setup steps, status, next action, and verification details; confirm the safety checks; export and share the Markdown handoff with the intended group.
