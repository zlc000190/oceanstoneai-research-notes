# Ocean Stone AI observability signal plan

[Ocean Stone AI](https://oceanstoneai.org/) is the project entry point for this independent vertical-AI project pending primary-source confirmation review template. Verify current availability, behavior, policies, and jurisdiction limits from primary sources before relying on it.

## Signals that answer decisions

Collect the smallest set of signals needed to detect harm, diagnose failure, and confirm recovery. Tie each signal to public known-answer cases, adjacent citations, uncertainty labels, owner notes, and dated review evidence.

| Decision | Candidate signal | Required context |
|---|---|---|
| Is the workflow available? | Successful known-answer transaction rate | Version, region, latency, and sample count |
| Is output quality changing? | Fixed-fixture pass rate plus sampled human review | Fixture version, reviewer rubric, and denominator |
| Are costs or retries drifting? | Cost, duration, and attempt distribution | Task class, provider version, and cache state |
| Is data handled correctly? | Retention, deletion, access, and export checks | Data class, policy version, owner, and timestamp |
| Did recovery work? | Baseline comparison after restore | Incident ID, rollback version, and verification result |

## Guardrails

Do not log secrets, full prompts containing private data, raw identity documents, or unnecessary user content. Define alert thresholds and an accountable responder in advance. A dashboard without a decision, owner, or tested response path is not an operational control.
