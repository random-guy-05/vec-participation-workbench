# VEC Participation Workbench

Twenty-seven small, offline-first tools for joining and contributing to the Virtual Embryo Challenge community: planning a submission, coordinating teams, finding a first community task, writing safe help requests, reviewing resources, creating safe examples, teaching, maintaining shared resources, diagnosing compute jobs, forecasting runtime, and transferring data safely.

Each tool runs in a browser with no account, server, analytics, dependency install, or data upload. User-entered information stays in the page until exported. The tools are planning aids; the official Challenge pages control if a rule or date changes.

## Tools

| Tool | Workflow it supports |
|---|---|
| [Board Coverage Planner](https://random-guy-05.github.io/vec-participation-workbench/tools/board-coverage/) | Apply the published per-task mean and zero-for-unattempted-board rule to a team's own board list. |
| [Generality Architecture Mapper](https://random-guy-05.github.io/vec-participation-workbench/tools/generality-map/) | Check a proposed shared architecture against the Generality Award's stated structure and draft its method description. |
| [Team Contribution Ledger](https://random-guy-05.github.io/vec-participation-workbench/tools/team-ledger/) | Keep an exportable record of who made substantive decisions, code, data, and artifacts. |
| [Compute Budget Estimator](https://random-guy-05.github.io/vec-participation-workbench/tools/compute-budget/) | Estimate the raw float32 size of a prediction matrix and plan for overhead before choosing a machine. |
| [Deadline Calendar Exporter](https://random-guy-05.github.io/vec-participation-workbench/tools/calendar/) | Download the Challenge's published schedule as all-day `.ics` events. |
| [Experiment Plan Card](https://random-guy-05.github.io/vec-participation-workbench/tools/experiment-card/) | Record a falsifiable hypothesis, permitted inputs, evaluation plan, and selection rule before running an experiment. |
| [Team Eligibility Checklist](https://random-guy-05.github.io/vec-participation-workbench/tools/team-check/) | Walk through the main team formation and track eligibility questions without entering personal details. |
| [Data-use Readiness Checklist](https://random-guy-05.github.io/vec-participation-workbench/tools/data-use/) | Track disclosure, acknowledgement, and written-approval steps before using Challenge data in public work. |
| [Good First Contribution Finder](https://random-guy-05.github.io/vec-participation-workbench/tools/contribution-finder/) | Match available time, interests, and resources to small tasks with a concrete finish. |
| [Help Request Builder](https://random-guy-05.github.io/vec-participation-workbench/tools/help-request/) | Prepare a reproducible public support request and check it for sensitive content. |
| [Contribution Brief Builder](https://random-guy-05.github.io/vec-participation-workbench/tools/contribution-brief/) | Scope a community barrier into a deliverable, acceptance checks, and access plan. |
| [Community Resource Review](https://random-guy-05.github.io/vec-participation-workbench/tools/resource-review/) | Record the conditions, outcome, blocker, and proposed fix when reviewing a public resource. |
| [Accessibility Review Checklist](https://random-guy-05.github.io/vec-participation-workbench/tools/accessibility-review/) | Capture accessibility checks and actionable findings for a public artifact or event. |
| [Peer Session Agenda Builder](https://random-guy-05.github.io/vec-participation-workbench/tools/workshop-agenda/) | Generate a time-budgeted peer walkthrough agenda with a low-setup access plan. |
| [Discussion-to-Action Notes](https://random-guy-05.github.io/vec-participation-workbench/tools/decision-actions/) | Separate decisions, open questions, and agreed tasks after a community discussion. |
| [Project Handoff Card](https://random-guy-05.github.io/vec-participation-workbench/tools/handoff-card/) | Give the next contributor a clean start, known limits, and a clear first action. |
| [Synthetic Data Lab](https://random-guy-05.github.io/vec-participation-workbench/tools/synthetic-data-lab/) | Generate deterministic toy expression, metadata, and a local AnnData loader for safe software examples. |
| [Quickstart Guide Builder](https://random-guy-05.github.io/vec-participation-workbench/tools/quickstart-builder/) | Draft exact first-run steps, expected output, recovery, and low-setup routes. |
| [Micro-Lesson Blueprint](https://random-guy-05.github.io/vec-participation-workbench/tools/lesson-blueprint/) | Structure a short lesson around an outcome, worked example, practice, and answer. |
| [Scientific Figure Description Builder](https://random-guy-05.github.io/vec-participation-workbench/tools/figure-caption/) | Prepare concise alt text and a longer, evidence-bounded description for a scientific visual. |
| [Source Freshness Tracker](https://random-guy-05.github.io/vec-participation-workbench/tools/source-freshness/) | Set a local reminder to recheck a time-sensitive claim against its source. |
| [Feedback Triage Planner](https://random-guy-05.github.io/vec-participation-workbench/tools/feedback-prioritizer/) | Compare reported barriers with a transparent impact/frequency/urgency/effort heuristic. |
| [Community Project Starter](https://random-guy-05.github.io/vec-participation-workbench/tools/project-starter/) | Generate a README, contributor guide, and citation metadata files for a new public artifact. |
| [Community Release Notes Builder](https://random-guy-05.github.io/vec-participation-workbench/tools/release-notes/) | Explain user-visible changes, migration steps, evidence, and limits for an update. |
| [HPC Job Log Doctor](https://random-guy-05.github.io/vec-participation-workbench/tools/job-log-doctor/) | Triage common Slurm, PBS, LSF, accelerator, storage, and environment errors from a pasted log excerpt, locally. |
| [Runtime Forecast Planner](https://random-guy-05.github.io/vec-participation-workbench/tools/runtime-forecast/) | Fit a simple scaling curve to measured runs, add a buffer, and compare the projection with a queue wall-time limit. |
| [Verified Download Script Builder](https://random-guy-05.github.io/vec-participation-workbench/tools/verified-download/) | Generate a resumable HTTPS Bash downloader that refuses to overwrite files and can check supplied SHA-256 digests. |

## Run locally

Clone the repository and open `docs/index.html` or any `docs/tools/<name>/index.html` in a modern browser. The apps use only local HTML, CSS, and JavaScript. They do not fetch Challenge data or send form contents anywhere.

## Sources and maintenance

The current source links and the facts each tool uses are collected in [`SOURCES.md`](SOURCES.md). Recheck those official pages before relying on date- or rules-sensitive output. Last checked: 14 October 2026.

## Scope

These utilities do not submit predictions, contact the Challenge, decide eligibility, give legal advice, or guarantee a score or award. The Board Coverage Planner computes only the formula in the Rules from the board rows entered by the user. The Generality mapper is an explanation aid, not an organiser ruling. The compute estimator reports matrix storage arithmetic, not actual peak RAM or runtime. Data-use requirements can depend on facts the checklist cannot assess.

## License

MIT. See [`LICENSE`](LICENSE).
