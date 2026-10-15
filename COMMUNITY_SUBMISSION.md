# Community contribution filing drafts

All twenty-seven tools are standalone static pages with no dependencies, login, upload, analytics, or server-side processing. The tools are English-first and link to official sources for facts they reference. File each tool page as a separate `build` only after its hosted URL is available.

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

## Third set: safe examples and maintainable learning resources

### 17. Synthetic Data Lab

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/synthetic-data-lab/
- **What it is, and who it helps:** A browser-only deterministic generator for small toy expression matrices, cell/feature metadata, and optional x/y/z coordinates. It also creates a readme and optional Python loader for AnnData. It lets contributors demonstrate or prototype data-processing code without copying Challenge data into examples. The generated files are generic toys, not biological data, official task inputs, or valid submissions.
- **How someone else runs it:** Choose cell/gene/group counts, dropout, seed, and coordinate option; generate the preview; then download expression CSV, cell metadata CSV, feature metadata CSV, and the readme. If desired, download the helper and run it locally with pandas and anndata installed.

### 18. Quickstart Guide Builder

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/quickstart-builder/
- **What it is, and who it helps:** A structured quickstart template for documenting prerequisites, exact clean setup steps, first command, expected result, low-resource route, recovery hints, privacy boundaries, and authoritative sources. It helps maintainers write a first-run path that a new participant can follow and verify.
- **How someone else runs it:** Fill the labeled fields, create the Markdown preview, then copy or download it for review and adaptation. The browser does not publish the guide.

### 19. Micro-Lesson Blueprint

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/lesson-blueprint/
- **What it is, and who it helps:** A blueprint for a short asynchronous lesson built around a measurable learner outcome, prerequisite knowledge, ordered concepts, worked example, practice task, answer and rationale, troubleshooting, and accessibility/source notes. It helps community educators make focused self-paced materials rather than broad, hard-to-finish tutorials.
- **How someone else runs it:** Enter one topic and outcome, add the example and practice, write an answer key and recovery hint, then export the Markdown outline for authoring and peer review.

### 20. Scientific Figure Description Builder

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/figure-caption/
- **What it is, and who it helps:** A template for short alt text and a longer figure description that records layout, axes, visual encodings, supported observation, caveats, and source. It helps authors make workshop and tool visuals understandable to people who cannot inspect the image and guards against overclaiming what a plot establishes.
- **How someone else runs it:** Describe the figure purpose, short alternative text, panel order, encodings, observation and limits; export the draft, then review it alongside the actual visual and current source.

### 21. Source Freshness Tracker

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/source-freshness/
- **What it is, and who it helps:** A local reminder and note generator for a time-sensitive claim, its authoritative source, last human check, and next recheck date. It makes stale rules, dates, and setup claims easier for resource maintainers to find. It calculates dates only; it does not fetch a page or certify its contents.
- **How someone else runs it:** Record one claim, public source, last checked date and recheck interval; calculate the reminder; add what to verify; then export a freshness note for the resource maintainers.

### 22. Feedback Triage Planner

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/feedback-prioritizer/
- **What it is, and who it helps:** A local backlog discussion aid that records one barrier, affected workflow, evidence, and a suggested response. Its visible frequency × impact × urgency ÷ effort heuristic makes assumptions explicit for volunteer maintainers. It is not an official or objective ranking and should be revisited with affected participants.
- **How someone else runs it:** Describe an anonymized issue, enter consistent 1–5 ratings, calculate the heuristic, record the reason and smallest useful response, then export a Markdown triage note.

### 23. Community Project Starter

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/project-starter/
- **What it is, and who it helps:** A browser-only starter that drafts a public project README, contribution guide, and CITATION.cff metadata. It prompts for a first run, expected output, data boundaries, setup, and limitations so a new tool is easier to try, review, maintain, and cite. It does not create a repository or publish any files.
- **How someone else runs it:** Enter the project details and safe example, preview/copy/download README.md, then separately download CONTRIBUTING.md and CITATION.cff. Replace the author placeholder, check the CFF metadata, review license rights, and inspect all files before publication.

### 24. Community Release Notes Builder

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/release-notes/
- **What it is, and who it helps:** A release-note template centered on user-visible improvements, migration steps, verification evidence, unresolved limits, and sources. It helps maintainers tell participants whether an update changes their workflow and what to recheck.
- **How someone else runs it:** Enter the public version/link, intended audience, changes, breakage/migration, verification evidence, limitations, and next freshness check; export the Markdown notes and publish them with the release after review.

## Additional set: compute access and safe data transfer

### 25. HPC Job Log Doctor

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/job-log-doctor/
- **What it is, and who it helps:** A browser-only triage tool for common Slurm, PBS/Torque, LSF, CUDA, storage, environment, and HDF5 failure clues. It identifies matched line numbers, gives bounded next checks, and never sends or displays the pasted log text in its result. It helps participants who are new to research clusters turn a failed job into a focused, privacy-conscious support request. Pattern matches are hints, not a cluster diagnosis.
- **How someone else runs it:** Paste a small, redacted excerpt from the job log, choose or detect the scheduler, and run triage. Review the matched line numbers and suggestions against the local cluster documentation before changing a job.

### 26. Runtime Forecast Planner

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/runtime-forecast/
- **What it is, and who it helps:** A local planner that fits a log-log scaling curve to participant-measured cell-by-gene run sizes and elapsed times, applies the largest observed underprediction plus a configurable safety multiplier, and checks the result against a queue wall-time limit. It helps teams use short pilots to avoid submitting jobs that cannot finish. It labels sparse, weak-fit, or long-range extrapolations as uncertain and does not claim to predict memory or queue wait.
- **How someone else runs it:** Enter at least two completed, comparable pilot measurements as cells, genes, and minutes; enter the intended size and wall-time limit; then review the fitted scaling, buffer, extrapolation range, and warning before scheduling.

### 27. Verified Download Script Builder

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/verified-download/
- **What it is, and who it helps:** A client-side generator for a Bash script that downloads public HTTPS files with retry and resume support, refuses to overwrite an existing final file, and checks a user-supplied SHA-256 digest before finalizing a file. It helps participants on slower connections or cluster login nodes avoid silently using an interrupted data transfer. It rejects credential-bearing and signed URLs, never runs the script, and distinguishes a transfer without a checksum from a verified download.
- **How someone else runs it:** Enter a trusted public HTTPS URL per line and, when published by the source, its expected SHA-256 and filename. Generate and inspect the script, save it locally, then run it in an environment with Bash and curl after confirming cluster policy and storage location.
