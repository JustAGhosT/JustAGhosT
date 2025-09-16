# Platform Metrics

Evidence-based snapshot of policy spine + automation impact.

## Current Targets
- Policy eval p95 < 45ms
- Policy eval p99 < 70ms
- PR time-to-first-meaningful-review: -25% vs baseline (goal)
- PR noise ratio < 0.35
- IaC gate first-pass success > 0.80

## Latest Snapshot
<!-- METRICS:CURRENT:START -->
(No data yet — baseline collection in progress)
<!-- METRICS:CURRENT:END -->

## History
<!-- METRICS:HISTORY:START -->
(Date, p50(ms), p95(ms), p99(ms), allow%, cache_hit%, pr_ttfmr(min), pr_noise_ratio, iac_first_pass%)
<!-- METRICS:HISTORY:END -->

## Definitions
- pXX: Percentile of policy evaluation latency (ms) excluding warm-up.
- allow%: allow decisions / total.
- cache_hit%: evaluations served from cache / total.
- pr_ttfmr: time (minutes) to first meaningful review (non-trivial semantic diff comment or approval).
- pr_noise_ratio: low-signal comments / total comments.
- iac_first_pass%: successful promotion without rework.

## Next Add
Add delta columns once optimizations land (Baseline vs Current).

