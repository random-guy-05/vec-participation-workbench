# Novelty and scope map

The 29 original analysis pages are separate jobs with independent inputs and outputs. They use small user-supplied CSV/JSON extracts so a participant can explore a concrete question without installing a notebook stack or sharing the data. Eight paired prediction diagnostics and eight spatial graph diagnostics are mapped separately below; none of these pages replaces specialist statistical packages or official Challenge services.

The community already has substantial resources for onboarding, score calculation, submission validation, broad data inspection, and geometric sanity checks. The distinctions below are the intended boundaries of this new set.

| New build | Related existing resource | Distinct job |
|---|---|---|
| Pseudobulk Aggregator | [VEC Cohort Audit](https://github.com/random-guy-05/vec-cohort-audit) profiles metadata only. | Aggregate numeric cell measurements within sample and cell-state groups before downstream comparisons. |
| Design Confounding Auditor | [VEC Cohort Audit](https://github.com/random-guy-05/vec-cohort-audit) profiles sample composition. | Check exact rank deficiency in a user-selected categorical study design. |
| Rare-State Sampling Planner | Existing sample and scoring sensitivity tools analyze observed runs. | Estimate a binomial capture probability before choosing a sampling target. |
| Cell Composition Distance Explorer | [VEC Cohort Audit](https://github.com/random-guy-05/vec-cohort-audit) summarizes per-sample composition. | Calculate pairwise composition distances, including within- and between-group comparisons. |
| Composition–Expression Decomposer | [VEC Cohort Audit](https://github.com/random-guy-05/vec-cohort-audit) summarizes composition but not expression. | Attribute a two-condition mean shift to composition versus within-cell-type means. |
| Gene Signature Coverage Auditor | [VEC PanelGuard](https://github.com/random-guy-05/vec-panelguard) repairs exact submission panel order; external-data tools map genes. | Check exact presence, absence, and duplication for a user-defined signature without mapping aliases. |
| Gene Set Enrichment Calculator | Existing marker and pathway resources provide biological interpretation. | Compute a transparent over-representation statistic against an explicit supplied universe. |
| Replicate-Aware Contrast Reporter | [VEC Diff](https://github.com/random-guy-05/vec-diff) compares prediction files and [Replicate Range](https://github.com/random-guy-05/vec-replicate-range) summarizes Task 3 score spread. | Summarize sample-level gene effects and paired direction consistency before scoring. |
| Single-Cell QC Threshold Explorer | Community data inspectors focus on file/schema review and common data pitfalls. | Apply user-selected per-cell count/gene/mitochondrial thresholds and expose every exclusion reason. |
| Per-Cell Signature Scorer | Marker-consistency tools inspect curated markers. | Score a participant-selected signature relative to a small pasted matrix. |
| Stage Trend & Forecast Explorer | Task-specific model labs explore full predictive methods. | Compare two simple univariate stage trends with leave-one-stage-out error on a small summary table. |
| Cell-Label Transition Explorer | Cell-type vocabulary tools identify label renames and harmonization candidates. | Quantify source-to-target label transitions as observed counts and normalized fractions. |
| Cell-Label Mapping Auditor | Cell-Label Transition Explorer | Aggregates counts after a participant-supplied canonical mapping and reports unresolved labels; it does not infer stage-to-stage identity or lineage. |
| Gene Detection Rate Analyzer | Count-recovery and log-scale tools inspect file representation. | Separate per-gene detection prevalence from mean positive expression by group. |
| Replicate Concordance Reporter | [VEC Replicate Range](https://github.com/random-guy-05/vec-replicate-range) reports differences in official Task 3 scores across two target replicates. | Compare participant sample-level expression profiles over shared genes. |
| 3D Coordinate Alignment Explorer | [VEC SpatialQC](https://github.com/random-guy-05/vec-spatialqc) detects degenerate clouds; the submission viewer visualizes coordinates. | Produce centered principal-axis coordinates and state the ambiguity of PCA orientation. |
| Spatial Neighborhood Radius Explorer | [VEC SpatialQC](https://github.com/random-guy-05/vec-spatialqc) checks degeneracy and nearest-neighbor distances. | Report counts within an explicitly chosen physical radius for every point. |
| Spatial Occupancy Grid Comparator | Existing spatial tools visualize submissions or compute official scoring metrics. | Compare two user-provided point clouds at multiple voxel resolutions with exploratory Jaccard/Dice. |
| 3D Spatial Autocorrelation Explorer | Existing spatial tools focus on shape and score diagnostics. | Calculate Moran's I for a supplied feature on a stated 3D k-nearest-neighbor graph. |
| Metric Contract Diff | [VEC Rules and Contract Watch](https://github.com/xxx12e/vec-community-kit/tree/main/vec_rules_watch) watches public pages; [veckit issue #1](https://github.com/aristoteleo/veckit/issues/1) and [issue #3](https://github.com/aristoteleo/veckit/issues/3) discuss scorer scope. | Compare two local JSON snapshots without claiming which is authoritative. |
| Metadata Schema & Drift Comparator | [VEC Cohort Audit](https://github.com/random-guy-05/vec-cohort-audit) profiles one dataset; cell-type vocabulary tools focus on label harmonization. | Compare two metadata CSV snapshots for changed columns, inferred types, missingness, and categories; it deliberately does not match rows. |
| Challenge Service Incident Packet | [Help Request Builder](https://random-guy-05.github.io/vec-participation-workbench/tools/help-request/) drafts general reproducible questions. | Structure outage evidence, impact, timestamps, and observed-versus-inferred claims for service incidents. |
| Replicate Influence Explorer | [Replicate-Aware Contrast Reporter](https://random-guy-05.github.io/vec-participation-workbench/tools/contrast-reporter/) summarizes paired direction agreement. | Recompute an unpaired group contrast after omitting each biological sample and report effect sensitivity, range, and sign flips. |
| Spatial Cell-Contact Explorer | [Spatial Neighborhood Radius Explorer](https://random-guy-05.github.io/vec-participation-workbench/tools/neighborhood-radius/) counts neighbors per point; [Spatial Autocorrelation Explorer](https://random-guy-05.github.io/vec-participation-workbench/tools/spatial-autocorrelation/) uses one numeric feature. | Summarize undirected contacts between categorical cell labels and the resulting label-pair frequencies on a user-supplied 3D point cloud. |
| Perturbation Dose Consistency Explorer | [Stage Trend & Forecast Explorer](https://random-guy-05.github.io/vec-participation-workbench/tools/stage-trend/) compares developmental-stage trends. | Compare monotonic dose direction independently within replicate series for one perturbation; it neither forecasts stage values nor fits a mechanistic curve. |
| Gene-Set Redundancy Explorer | [Gene Set Enrichment Calculator](https://random-guy-05.github.io/vec-participation-workbench/tools/gene-set-enrichment/) tests overlap with selected genes and a universe. | Compare gene sets against one another to identify redundant pairs and connected overlap groups before term interpretation. |
| Cross-Species Mapping Audit | [Gene Signature Coverage Auditor](https://random-guy-05.github.io/vec-participation-workbench/tools/signature-coverage/) checks exact presence in a panel. | Audit a user-supplied cross-species source/target mapping for unmapped IDs and one-to-many or many-to-one collisions. |
| Sample Manifest Integrity Auditor | [Design Confounding Auditor](https://random-guy-05.github.io/vec-participation-workbench/tools/design-confounding/) checks identifiability of categorical study factors. | Detect record-level duplicate IDs, conflicting assignments, blanks, and exact repeated rows before design analysis. |
| Stage-by-Condition Coverage Planner | [Stage Trend & Forecast Explorer](https://random-guy-05.github.io/vec-participation-workbench/tools/stage-trend/) fits trends to observed stage measurements. | Expose missing or under-replicated stage-condition combinations against an explicit expected stage order; it does not model expression. |
| Cell Annotation Concordance Auditor | [Cell-Label Transition Explorer](https://random-guy-05.github.io/vec-participation-workbench/tools/label-transition/) counts supplied source-to-target transitions. | Compare paired per-cell partitions with adjusted Rand agreement and majority mapping, invariant to label spelling. |

## Interactive learning simulations

These sixteen pages are deterministic teaching demonstrations, separate from the user-input analysis tools above. Each states its assumptions and warns against treating synthetic output as a biological result.

| Simulation | Neighboring concept or resource | Distinct learning job |
|---|---|---|
| Pseudoreplication Visualizer | Pseudobulk Aggregator groups measurements by sample; this page teaches the information loss from within-sample correlation. | Show the equal-cluster design-effect approximation and why an effective cell count does not create biological replicates. |
| Validation Leakage Playground | SplitForge builds leakage-audited pseudo-validation splits. | Give a closed-form intuition for the chance a related group crosses an independent cell split and explain what group-held-out validation estimates. |
| Multiple Testing Expectation Explorer | Gene Set Enrichment Calculator applies Benjamini–Hochberg adjustment to supplied sets. | Distinguish expected false-positive count from family-wise probability under explicit independent-null assumptions. |
| Composition Shift Demonstrator | Composition–Expression Decomposer analyzes user-provided values. | Let learners construct aggregate reversals and inspect a symmetric composition/within-type decomposition on a two-group toy example. |
| Metric Behavior Playground | Metric Cards are static score references; MetricLens diagnoses local score outputs. | Change a toy prediction and directly compare Pearson, Spearman, and RMSE behavior under offset, scaling, or an outlier. |
| Batch Confounding Playground | Design Confounding Auditor analyzes a supplied categorical design. | Make the treatment-by-batch aliasing pattern visible and show why restoring matrix rank is necessary but not sufficient. |
| Dose Response Shape Explorer | Perturbation Dose Consistency Explorer summarizes supplied replicate trends. | Contrast three deterministic curve shapes and teach why dose range and replication affect what can be inferred. |
| Spatial Neighborhood Scale Playground | Spatial Cell-Contact Explorer analyzes supplied labeled points. | Show how a radius choice changes an example graph's edge density and cross-label fraction at the same time. |


| Regression-to-the-Mean Playground | Pseudoreplication Visualizer explains clustered observations. | Show selection on an extreme noisy baseline followed by remeasurement, with no intervention effect. |
| Range Restriction Correlation Explorer | Metric Behavior Playground changes prediction values and metrics. | Keep the generating relationship fixed while restricting the predictor range and comparing observed correlations. |
| Winner’s Curse Selection Simulator | Multiple Testing Expectation Explorer counts expected false positives. | Demonstrate the optimism from selecting the maximum of noisy candidate estimates and checking it independently. |
| Optional Stopping Demonstrator | Multiple Testing Expectation Explorer examines a family of tests. | Simulate repeated looks at the same accumulating null sample and contrast with one pre-specified final look. |
| Missing-Data Bias Playground | Single-Cell QC Threshold Explorer applies explicit row-level filters. | Compare complete-case and zero-filled group contrasts under MCAR, group-dependent, and outcome-dependent missingness. |
| Measurement Error Attenuation Explorer | Gene Detection Rate Analyzer separates detection prevalence from positive magnitude. | Show classical predictor measurement error pulling a fitted slope toward zero in a fixed synthetic model. |
| Batch Adjustment Trade-off Playground | Batch Confounding Playground shows design-matrix rank. | Show how condition–batch overlap affects the raw contrast and the separately estimated additive treatment effect. |
| Log-Transform Compression Explorer | LogCheck warns about raw-count representation. | Visualize how one fold change maps to raw and log2(1 + count) scales without claiming normalization or normality. |

## Paired prediction diagnostics

These eight tools use small `reference,predicted` tables but answer different questions. They are descriptive diagnostics rather than replacements for the official scoring implementation.

| Diagnostic | Distinct job |
|---|---|
| Agreement Limits Analyzer | Summarize paired signed bias and approximate difference limits; the Concordance Correlation Calculator covers a single agreement coefficient, not the spread of differences. |
| Concordance Correlation Calculator | Combine association with mean/scale agreement; it adds agreement information beyond Pearson correlation. |
| Prediction Calibration Fitter | Fit a reference-on-prediction line and show intercept/slope departure from ideal calibration. |
| Error-by-Range Profiler | Reveal whether bias or error size changes across the reference range. |
| Replicate Error Stability Auditor | Preserve group-level error patterns so a pooled cell count does not hide between-sample variation. |
| Tolerance Coverage Analyzer | Report the empirical fraction inside explicitly user-chosen absolute-error cutoffs, without inventing an official threshold. |
| Bias–Variance Error Decomposer | Verify the empirical MSE identity for mean bias and error variance; it is not the broader learning-theory decomposition. |
| Prediction Distribution Shift Comparator | Compare marginal distributions without matching pairs, a different question from paired agreement or prediction error. |

The community catalog changes over time. Before extending these pages or filing a later version, check the current [community resources](https://virtualembryo.ai/challenge/resources) and prefer improving an existing item when the actual workflow overlaps.

## Spatial graph diagnostics

These eight browser-only point-table tools use a shared 3D coordinate format. They are distinct from the existing spatial radius, contact, occupancy, alignment, and autocorrelation jobs by focusing on graph topology, scale sensitivity, data collisions, and label-boundary summaries. The permutation page states its exchangeability assumption and reports a Monte Carlo reference rather than an official score.

| Diagnostic | Related existing resource | Distinct job |
|---|---|---|
| Spatial Graph Connectivity Auditor | Spatial Neighborhood Radius Explorer reports local counts at one radius. | Identify connected components, component membership, degrees, and isolated points in that radius graph. |
| Spatial kNN Distance Profiler | Spatial Neighborhood Radius Explorer reports nearest-neighbor distances. | Profile the user-selected k-th neighbor distance across all points to expose local scale variation beyond first neighbors. |
| Spatial Radius Stability Auditor | Spatial Neighborhood Scale Playground demonstrates radius effects on a synthetic graph. | Compare graph edge sets and isolate counts across a supplied point cloud and a user-entered radius sequence. |
| Spatial Label Mixing Permutation Explorer | Spatial Cell-Contact Explorer reports observed label contacts; Spatial Autocorrelation Explorer concerns a numeric feature. | Compare observed cross-label edge fraction with a fixed-graph, fixed-label-count shuffle reference under an explicit exchangeability caveat. |
| Spatial Coordinate Collision Auditor | Sample Manifest Integrity Auditor detects repeated sample records, not geometric collisions. | Locate distinct cell identifiers at exact or tolerance-defined duplicate coordinates without modifying records. |
| Spatial Nearest Different-Label Distance Reporter | Spatial Cell-Contact Explorer counts labels that share radius-defined edges. | Report each point’s nearest differently labeled point distance and per-label distance summaries, without claiming contact enrichment. |
| Spatial Axis-Scale Sensitivity Auditor | 3D Coordinate Alignment Explorer rotates and centers point clouds. | Quantify how user-supplied per-axis physical spacing factors change k-nearest-neighbor identities. |
| Spatial Axis Slice Profiler | Stage-by-Condition Coverage Planner counts table combinations, not spatial location. | Summarize cell counts and label composition in equal-width bins along a selected coordinate axis. |

## Task Metric Lab

The [Task Metric Lab](https://random-guy-05.github.io/vec-participation-workbench/metric-lab/) adds small browser-local calculators for the published scoring formulas. These are explanatory, small-data diagnostics, not competing implementations of the official scorer.

| Calculator | Related existing resource | Distinct job |
|---|---|---|
| Per-Metric Skill Transformer | MetricLens inspects local score outputs; Board Coverage Planner rolls board scores up. | Apply the published floor/ceiling transform to a raw metric value, including zero-is-ideal metrics. |
| Metric Weight Budget Auditor | Board Coverage Planner handles per-board task averages. | Check that metric weights sum within groups and group weights sum across the task. |
| Hierarchical Task Score Reconciler | Board Coverage Planner aggregates boards, not metrics. | Rebuild one task score from per-metric skill values and explicit two-level weights; missing rows count as zero. |
| DES Signed Top-Set Preview | Gene Signature Coverage Auditor checks exact panel membership. | Preview top/bottom signed DE-gene overlap against a supplied truth set and the reference-only null. |
| DCS Partial Rank Concordance | Prediction Calibration Fitter compares reference and prediction values. | Rank-transform change and reference vectors, then isolate predicted/true direction agreement conditional on baseline expression. |
| Unbiased Multi-Bandwidth MMD Explorer | Prediction Distribution Shift Comparator compares one-dimensional marginals. | Explain the unbiased RBF two-sample estimator across five target-based bandwidth scales in a supplied feature space. |
| Gene Co-Variation Variogram Comparator | Gene Detection Rate Analyzer and per-gene diagnostics inspect individual genes. | Compare pairwise gene variograms so changes in co-variation remain visible when gene marginals look similar. |
| PSS Perturbation Severity Calculator | Replicate Range summarizes official score variation across samples. | Fit the truth-DE zero-intercept response slope, apply the published fit gate, and report its signed log. |
| Tissue Scale Ratio Calculator | Spatial Occupancy Grid Comparator compares occupied volume. | Isolate physical tissue scale with the rotation-invariant RMS-radius log ratio. |
| Shape Distance Distribution Comparator | Spatial Occupancy Grid Comparator compares occupied voxels. | Compare within-cloud, RMS-normalized pair-distance distributions without requiring cell correspondence. |
| Canonicalized Occupancy Dice Explorer | Spatial Occupancy Grid Comparator uses a shared supplied frame. | Demonstrate PCA canonicalization, proper sign flips, and the fixed occupancy grid used by the public shape metric. |
| Neighborhood Fidelity Profile Comparator | Spatial Cell-Contact Explorer counts categorical label contacts. | Build each cell's 15-neighbor expression profile and compare the resulting profile distributions without assuming cell matching. |

## Language access

The 29 original analysis pages share a client-side language selector for English, Spanish, and Simplified Chinese. The workbench index translates cards for the 21 core analysis tools; the eight additional audit cards are labeled in English and link to pages with translated tool descriptions, labels, and input guidance. The eight paired prediction diagnostics, eight spatial graph diagnostics, and Task Metric Lab are currently English-only. Calculation summaries, validation messages, table columns, and data values remain in English so machine-readable identifiers stay stable. Language selection is kept in the URL only; pasted inputs are not stored or transmitted.
| External Data Eligibility Checker | Data-use Readiness Checklist | Applies task-specific stage intervals and held-out genotype prompts to external-source screening; the existing checklist records broad obligations but does not evaluate those boundaries. |
