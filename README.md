# VEC Participation Workbench

Eight small, offline-first tools for the work around a Virtual Embryo Challenge submission: planning board coverage, checking Generality Award architecture fit, recording genuine team contributions, sizing memory, exporting the official schedule, preregistering experiments, checking team eligibility, and tracking data-use permissions.

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

## Run locally

Clone the repository and open any `tools/<name>/index.html` in a modern browser. The apps use only local HTML, CSS, and JavaScript. They do not fetch Challenge data or send form contents anywhere.

## Sources and maintenance

The current source links and the facts each tool uses are collected in [`SOURCES.md`](SOURCES.md). Recheck those official pages before relying on date- or rules-sensitive output. Last checked: 14 October 2026.

## Scope

These utilities do not submit predictions, contact the Challenge, decide eligibility, give legal advice, or guarantee a score or award. The Board Coverage Planner computes only the formula in the Rules from the board rows entered by the user. The Generality mapper is an explanation aid, not an organiser ruling. The compute estimator reports matrix storage arithmetic, not actual peak RAM or runtime. Data-use requirements can depend on facts the checklist cannot assess.

## License

MIT. See [`LICENSE`](LICENSE).
