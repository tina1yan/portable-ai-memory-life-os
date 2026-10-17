# Methods and measurement protocol (v0.1)

This project is a conceptual model plus one anonymized retrospective case, **not** causal evidence. Proposed prospective design:

## Observation unit
Log one project action, independently record its source and user intervention. Collect at least 4–8 weeks, including reset and non-reset periods.

## Minimum event schema
- timestamp and local time zone
- pseudonymous project ID and task ID
- source: user initiated / agent initiated / recurring maintenance
- reason: genuine task, curiosity, quota-pressure, deadline, unexpected defect
- start and completion/retirement dates
- outcome evidence (link to tests or proof; avoid personal records)
- human minutes (creation, troubleshooting, verification, coordination, restating context; no double counting)
- AI/API/infrastructure cost where available
- issue cause: inaccessible source, retrieval miss, compaction loss, stale state, execution failure, verification failure, intentional approval
- whether the task would have been started without an expiring allowance (self-report, not ground truth)

## Candidate measurements
**Intervention rate** = human corrective interventions / agent task attempts.
**Cross-session continuity success** = resumed tasks with correct prior state and no human re-explanation / eligible resumed tasks.
**Autonomous recovery rate** = initially failed tasks resolved with independent passing evidence without human corrective input / eligible failed tasks.
**Project net value** = self-reported benefits minus human effort, compute/hosting spending and upkeep; disclose valuation assumptions.
**Quota pressure** = perceived urge to use allowance before reset, measured separately from actual usage.

## Critical confounds
Skill growth, availability of leisure time, seasonality, work deadlines, novelty, improved model capability, cross-model switching, sunk-cost fallacy, intrinsic creative enjoyment, legitimate approvals, and project complexity. A single-person record cannot infer population prevalence.

## Study designs
1. Within-person interrupted time series: compare creation/maintenance trends around documented quota resets, controlling for weekends and project complexity.
2. Counterbalanced behavioral intervention: alternate weeks with/without a deliberate “unused quota has zero value” reminder; observe starts and overhead.
3. Multiple participants: recruit opt-in AI hobby builders at various experience levels; never upload raw private chat transcripts.

Record source dates and distinguish model-generated completion messages from independent proof. Publish only aggregated, consented, anonymized observations.