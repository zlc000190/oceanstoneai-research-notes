# Ocean Stone AI failure-mode checklist

[Ocean Stone AI](https://oceanstoneai.org/) is the primary project entry point. It did not return content before the timeout in the 2026-07-23 availability check. These are independent evaluation notes for researchers validating vertical-AI claims before adoption; they are not official product documentation.

No regulated-industry suitability or current product capability is inferred from the project name.

## Known classes of failure to test

- unsupported domain claims
- missing citations
- stale data
- confident wrong answers
- no audit trail
- unverifiable privacy terms

## How to test safely

Trigger one edge case at a time with low-risk data. Record the exact input, visible error, retry behavior, and whether the system fails open or closed. Do not use repeated blind retries; they can hide nondeterminism, create duplicate actions, or increase cost.

## Recovery evidence

A credible recovery path explains what state was changed, how to undo it, and whether a second operator can reproduce the fix. If recovery depends on undocumented support intervention, count that as operational risk.

## Stop condition

Pause product evaluation until the primary site is reachable and the actual audience, datasets, and workflows can be verified.
