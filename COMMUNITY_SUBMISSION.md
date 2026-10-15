# Community contribution filing drafts

All forty-eight tools are standalone static pages with no dependencies, login, upload, analytics, or server-side processing. The tools are English-first and link to official sources for facts they reference. File each tool page as a separate `build` only after its hosted URL is available.

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

### 28. VEC Pseudobulk Aggregator

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/pseudobulk/
- **What it is, and who it helps:** Aggregate cell-level numeric measurements within user-selected sample, condition, and cell-state columns. It reports cells per aggregate and supports sums for raw counts or means for normalized values, helping analysts preserve the biological sample as the replicate.
- **How someone else runs it:** Paste a small cell-by-feature CSV, list grouping and feature columns, choose sum or mean, then analyze and download the aggregate CSV.

### 29. VEC Design Confounding Auditor

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/design-confounding/
- **What it is, and who it helps:** Build a categorical one-hot design from a sample manifest and calculate its matrix rank. It flags exact aliasing among condition, stage, batch, and other factors before model fitting.
- **How someone else runs it:** Paste one row per biological sample and name the categorical factors. Review factor levels, observed pair support, and design rank.

### 30. VEC Rare-State Sampling Planner

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/rare-state-sampling/
- **What it is, and who it helps:** Calculate binomial probabilities that a cell state at a chosen prevalence is captured at least a target number of times in one sample, every replicate, or any replicate. It helps plan exploratory sampling while stating that it is not a power calculation.
- **How someone else runs it:** Enter expected prevalence, cells per sample, number of independent samples, and minimum state-cell count; compare the resulting probabilities.

### 31. VEC Cell Composition Distance Explorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/composition-distance/
- **What it is, and who it helps:** Convert per-sample cell-type counts to proportions and compare all sample pairs using Bray–Curtis dissimilarity and Jensen–Shannon distance. It provides descriptive population differences while keeping samples as the replicates.
- **How someone else runs it:** Paste a long CSV with sample, group, cell_type, and count; review pairwise distances and download the table.

### 32. VEC Composition–Expression Decomposer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/composition-expression/
- **What it is, and who it helps:** Apply a symmetric Shapley decomposition to separate a two-condition overall mean-expression change into cell-composition and within-cell-type components. It helps distinguish population-mixture shifts from expression changes within annotated states.
- **How someone else runs it:** Paste one row per cell type with proportions and means for conditions A and B; review each component and the total.

### 33. VEC Gene Signature Coverage Auditor

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/signature-coverage/
- **What it is, and who it helps:** Compare a candidate marker or gene signature with a supplied assay panel, report exact present/missing identifiers, and flag duplicates. It performs no alias or ortholog guessing.
- **How someone else runs it:** Paste one gene identifier per line for the signature and panel; analyze and download the coverage table.

### 34. VEC Gene Set Enrichment Calculator

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/gene-set-enrichment/
- **What it is, and who it helps:** Run a one-sided hypergeometric over-representation analysis on user-supplied gene sets and a clearly specified assay universe, then calculate Benjamini–Hochberg adjusted values. It helps keep the background universe explicit.
- **How someone else runs it:** Paste the selected genes, the complete eligible universe, and a set,gene membership CSV; review overlap counts and adjusted p-values.

### 35. VEC Replicate-Aware Contrast Reporter

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/contrast-reporter/
- **What it is, and who it helps:** Summarize sample-level gene differences for two conditions, including paired direction agreement where sample IDs match. It reports descriptive effect sizes without treating cells as replicates or presenting significance claims.
- **How someone else runs it:** Paste a long CSV of sample, condition, gene, value; enter the two condition labels and pseudocount; download the comparison table.

### 36. VEC Single-Cell QC Threshold Explorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/cell-qc/
- **What it is, and who it helps:** Apply user-chosen count, detected-gene, and mitochondrial-fraction thresholds to a small cell-level QC table, displaying every pass/fail decision and all exclusion reasons.
- **How someone else runs it:** Paste cell_id,n_counts,n_genes,mito_pct rows, set cutoffs, and inspect the per-cell decision table.

### 37. VEC Per-Cell Signature Scorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/signature-score/
- **What it is, and who it helps:** Compute mean gene-wise z-scores for an exact supplied signature on a small already-normalized cell-by-gene matrix. Scores are explicitly relative to the pasted matrix, not calibrated pathway activity.
- **How someone else runs it:** Paste a cell-by-gene matrix and signature gene IDs, choose an optional group column, then analyze and export cell scores.

### 38. VEC Stage Trend & Forecast Explorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/stage-trend/
- **What it is, and who it helps:** Fit linear and quadratic models to replicate-level values across numeric stages, compare training and leave-one-stage-out RMSE, and project to a chosen stage. It exposes extrapolation uncertainty.
- **How someone else runs it:** Paste stage,value rows (replicate IDs are optional), enter a target stage, and compare the observed stage means and model projections.

### 39. VEC Cell-Label Transition Explorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/label-transition/
- **What it is, and who it helps:** Summarize supplied source-to-target label counts with row and column fractions, making refinement, splitting, and merging visible without inventing a biological mapping.
- **How someone else runs it:** Paste source_label,target_label,count rows; inspect the transition table and download it for further review.

### 40. VEC Gene Detection Rate Analyzer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/gene-detection/
- **What it is, and who it helps:** For each group and gene in a small matrix, calculate the fraction of cells above zero separately from mean expression among detected cells. This distinguishes prevalence from positive-value magnitude.
- **How someone else runs it:** Paste a cell-by-gene matrix, specify the group and gene columns, then compare detection prevalence.

### 41. VEC Replicate Concordance Reporter

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/replicate-concordance/
- **What it is, and who it helps:** Calculate pairwise Pearson and Spearman correlations of sample-level gene profiles within each condition, report shared feature counts, and highlight limited coverage without recommending replicate deletion.
- **How someone else runs it:** Paste sample,condition,gene,value rows and review correlations between samples in the same condition.

### 42. VEC 3D Coordinate Alignment Explorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/coordinate-alignment/
- **What it is, and who it helps:** Center a point cloud and rotate it onto its principal axes using an eigendecomposition. It exports transformed coordinates while documenting PCA sign ambiguity and the absence of atlas registration.
- **How someone else runs it:** Paste a point cloud with x,y,z columns and an optional cell_id; download the centered principal-axis coordinates.

### 43. VEC Spatial Neighborhood Radius Explorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/neighborhood-radius/
- **What it is, and who it helps:** For each point, count neighbors within a selected Euclidean radius and report its nearest-neighbor distance. It helps participants make neighborhood scale choices explicit.
- **How someone else runs it:** Paste x,y,z coordinates and enter a radius in the same coordinate units; review per-point neighborhoods.

### 44. VEC Spatial Occupancy Grid Comparator

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/occupancy-comparison/
- **What it is, and who it helps:** Compare two point clouds in a shared coordinate frame using occupied-voxel Jaccard and Dice scores at four resolutions. The multi-resolution report makes discretization sensitivity visible.
- **How someone else runs it:** Paste two CSV point clouds with x,y,z coordinates; review and download the resolution-sensitivity table.

### 45. VEC 3D Spatial Autocorrelation Explorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/spatial-autocorrelation/
- **What it is, and who it helps:** Calculate descriptive global Moran’s I for one feature on a 3D directed k-nearest-neighbor graph and report its randomization reference expectation. It deliberately does not invent a permutation p-value.
- **How someone else runs it:** Paste x,y,z,value rows, choose k, and inspect the statistic and graph size.

### 46. VEC Metric Contract Diff

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/metric-contract-diff/
- **What it is, and who it helps:** Compare two JSON panel or scorer snapshots by nested key path, value, and missing key. It supports careful inspection of public contract drift but does not decide which source is canonical.
- **How someone else runs it:** Paste two JSON objects and review the differing paths; record source URLs, package version, and commit separately.

### 47. VEC Metadata Schema & Drift Comparator

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/metadata-drift/
- **What it is, and who it helps:** Compare two metadata CSV snapshots for added or removed columns, inferred type changes, missingness shifts, and new or removed categorical levels. It does not match observation rows or assert that differences are biologically meaningful.
- **How someone else runs it:** Paste two metadata CSV exports, compare the schema and observed levels, then align row identities and populations before interpreting drift.

### 48. VEC Challenge Service Incident Packet

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/service-incident-packet/
- **What it is, and who it helps:** Draft a privacy-conscious support report for sign-in, upload, scoring, or service incidents. It structures timestamps, checks, user impact, and a clear separation of observed facts from inference.
- **How someone else runs it:** Fill each field, use “not checked” where appropriate, review the report, and remove identifiers, cookies, tokens, and private paths before sharing.

### 49. VEC Analysis Workbench — Spanish and Simplified Chinese interfaces

- **Kind:** expand
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/
- **What it is, and who it helps:** A shared language-access layer across the 21 analysis tools. It translates the analysis catalog, tool titles, descriptions, input labels, guidance, and controls into Spanish and Simplified Chinese. Result summaries, validation messages, table columns, and data values remain in English to preserve technical identifiers; each page discloses this before analysis. It does not create duplicate analysis workflows or store pasted data.
- **How someone else runs it:** Choose English, Español, or 简体中文 in the workbench’s analysis section or on any analysis page. Open a tool, load its synthetic example, replace it with a small public or synthetic table, and run the analysis. Changing the interface language preserves current inputs; the selected language is reflected in the URL only.

### 50. VEC Replicate Influence Explorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/replicate-influence/
- **What it is, and who it helps:** Recomputes an unpaired two-group contrast after omitting each biological sample, showing the leave-one-out range, maximum change, and any direction flips. It helps teams see whether a summary effect is dominated by one replicate without labeling samples as bad or producing inferential statistics.
- **How someone else runs it:** Paste sample-level `sample,group,feature,value` data, name two groups, and review the per-feature influence table. Repeated measurements within a sample are averaged first.

### 51. VEC Spatial Cell-Contact Explorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/spatial-contact/
- **What it is, and who it helps:** Summarizes categorical cell-label contact pairs on a 3D point cloud using a chosen radius, reporting edge counts, pair fractions, and per-label neighbor density. It extends geometry checks to label-resolved spatial neighborhood composition without claiming enrichment.
- **How someone else runs it:** Paste unique cell IDs, x/y/z coordinates, and labels; enter a radius in the coordinate units; inspect contact and neighborhood tables.

### 52. VEC Perturbation Dose Consistency Explorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/dose-consistency/
- **What it is, and who it helps:** Reports per-replicate Spearman trends and between-replicate feature means over dose for one perturbation, helping participants distinguish consistent direction from variable or flat responses. It does not fit a dose-response curve or calculate p-values.
- **How someone else runs it:** Paste `replicate,perturbation,dose,feature,value` data, enter the exact perturbation label, and inspect replicate trends and dose means.

### 53. VEC Gene-Set Redundancy Explorer

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/gene-set-overlap/
- **What it is, and who it helps:** Calculates pairwise Jaccard similarity and overlap coefficient for supplied gene sets and groups connected terms above a selected threshold. It helps readers recognize redundant terms before interpreting over-representation results.
- **How someone else runs it:** Paste `set,gene` membership rows, choose a Jaccard threshold, and review pairwise overlap and connected redundancy groups.

### 54. VEC Cross-Species Mapping Audit

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/orthology-audit/
- **What it is, and who it helps:** Audits a supplied source identifier universe and mapping table for unmapped IDs, one-to-many source mappings, many-to-one target collisions, exact duplicate pairs, and mapping rows outside the expected universe.
- **How someone else runs it:** Paste the expected source IDs and a `source_id,target_id` CSV, then inspect mapping cardinality and collision reports. Mapping evidence and release provenance remain the user’s responsibility.

### 55. VEC Sample Manifest Integrity Auditor

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/manifest-integrity/
- **What it is, and who it helps:** Identifies duplicate sample IDs, conflicting metadata assignments, blank field counts, and exact repeated-record patterns before analysis. Duplicate group summaries avoid echoing entire rows back into the results.
- **How someone else runs it:** Paste a sample manifest, name its sample-ID column and metadata fields, then reconcile flagged records against their source.

### 56. VEC Stage-by-Condition Coverage Planner

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/stage-coverage/
- **What it is, and who it helps:** Builds a planned stage-by-condition sample-count grid, including expected stages with no observed samples, and flags cells below a chosen biological-replicate minimum. It helps teams find temporal design gaps before fitting trends.
- **How someone else runs it:** Paste one row per biological sample with stage and condition, provide the expected stage order and conditions, and set a minimum independent-sample count.

### 57. VEC Cell Annotation Concordance Auditor

- **Kind:** build
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/tools/annotation-concordance/
- **What it is, and who it helps:** Compares two cell-label partitions for the same cells using adjusted Rand index, contingency counts, and majority label purity. It helps teams assess annotation-version agreement without requiring identical label names or implying biological correctness.
- **How someone else runs it:** Paste unique `cell_id,label_a,label_b` rows from two annotations and inspect the partition score and label-level mapping table.

### 58. Pseudoreplication Visualizer

- **Kind:** create
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/simulations/pseudoreplication/
- **What it is, and who it helps:** An interactive teaching demo of how within-replicate correlation reduces the information in clustered cell observations. It states the equal-cluster design-effect approximation and explicitly distinguishes effective cell information from biological replicate-level inference.
- **How someone else runs it:** Adjust the number of biological replicates, cells per replicate, and intraclass correlation; compare the naive cell count with the approximate effective count and read the assumptions on the page.

### 59. Validation Leakage Playground

- **Kind:** create
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/simulations/validation-leakage/
- **What it is, and who it helps:** Shows the probability that related cells cross training and validation partitions under independent cell-level assignment, compared with group-held-out assignment. It helps participants select a split unit that matches the generalization question and flags preprocessing leakage as a separate concern.
- **How someone else runs it:** Change group size and validation fraction; inspect the closed-form crossing probability and the notes about group-held-out interpretation.

### 60. Multiple Testing Expectation Explorer

- **Kind:** create
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/simulations/multiple-testing/
- **What it is, and who it helps:** Separates expected false-positive count from family-wise probability when many hypotheses are tested. Its calculation states the independent, calibrated-null assumption and avoids presenting an adjusted p-value or threshold recommendation.
- **How someone else runs it:** Select test count, assumed null fraction, and per-test alpha; compare the expected false-positive fraction and chance of at least one false positive.

### 61. Composition Shift Demonstrator

- **Kind:** create
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/simulations/composition-shift/
- **What it is, and who it helps:** A synthetic two-subgroup example that lets learners separate changes in subgroup means from changes in subgroup proportions. A symmetric decomposition makes aggregate reversals and masked within-type effects concrete without claiming causality.
- **How someone else runs it:** Adjust control and treatment subgroup means and the fraction of type 1 in each group; compare the four subgroup means with both aggregate means.

### 62. Metric Behavior Playground

- **Kind:** create
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/simulations/metric-behavior/
- **What it is, and who it helps:** Applies an offset, scale change, or one-point outlier to a fixed synthetic prediction series and reports Pearson correlation, Spearman correlation, and RMSE. It teaches that association, ranking, and absolute calibration measure different properties.
- **How someone else runs it:** Choose a prediction change and magnitude; inspect the metric values and scatterplot against the perfect-agreement diagonal.

### 63. Batch Confounding Playground

- **Kind:** create
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/simulations/batch-confounding/
- **What it is, and who it helps:** Visualizes a two-condition by two-batch design and the exact aliasing that occurs when only diagonal combinations are observed. It also explains that a full-rank design is necessary for separating additive effects but does not guarantee balance or power.
- **How someone else runs it:** Add samples to both off-diagonal combinations and watch the displayed design rank change; the page identifies all counts as illustrative independent samples.

### 64. Dose Response Shape Explorer

- **Kind:** create
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/simulations/dose-shape/
- **What it is, and who it helps:** Compares deterministic linear, saturating, and transient-pulse curves over a selected dose range. It gives participants an accessible way to discuss why sparse measurements or a narrow dose window can conceal response shape while clearly labeling the curves as synthetic.
- **How someone else runs it:** Choose a response shape and maximum plotted dose; read the accompanying design notes on controls, replication, and range selection.

### 65. Spatial Neighborhood Scale Playground

- **Kind:** create
- **Public link:** https://random-guy-05.github.io/vec-participation-workbench/simulations/spatial-scale/
- **What it is, and who it helps:** A deterministic two-dimensional point-set demonstration of how a distance radius changes graph edges, edge count, and cross-label mixing together. It makes neighborhood scale an explicit analysis choice rather than hiding it in a default.
- **How someone else runs it:** Adjust the radius, inspect the rendered graph and cross-label edge fraction, and review the notes about units, dimensionality, and segmentation before applying a neighborhood rule to real tissue.
