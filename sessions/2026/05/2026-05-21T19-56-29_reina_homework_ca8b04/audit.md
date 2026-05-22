# Sunny Session Audit

sessionDir: /Users/jamaltaylor/Development/sunny/logs/sessions/2026/05/2026-05-21T19-56-29_reina_homework_ca8b04

## Counts
- events: 278
- gameTraces: 152
- chartAttemptEvents: 2
- transcriptWordRadarMentions: 2

## Issues
- [high] impossible_activity_mention: Companion mentioned Word Radar, but game traces do not show Word Radar active.
- [high] first_node_target_count_mismatch: Session opener showed 10 target(s) for spell-check, but normalized evidence only contains 5.
- [high] child_reported_skipped_planned_activity: Child reported missing planned activities that do not appear as active game traces.
- [high] target_purpose_missing: Post-session truth has target evidence but no target purposes, so activity fit cannot be audited.
- [high] companion_truth_contradiction_present: The contradiction checker caught Elli making a claim that did not match authoritative activity truth.
- [high] summary_target_contradiction: Post-session truth lists "comb" as both correct and missed; recovered targets must be separated from unresolved misses.
- [high] missing_psychologist_adaptation_decision: Normalized activity readings exist, but the session has no psychologist decision or next-plan diff that interprets them.

