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
