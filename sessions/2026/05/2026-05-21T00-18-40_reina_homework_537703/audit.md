# Sunny Session Audit

sessionDir: /Users/jamaltaylor/Development/sunny/logs/sessions/2026/05/2026-05-21T00-18-40_reina_homework_537703

## Counts
- events: 627
- gameTraces: 406
- chartAttemptEvents: 2
- transcriptWordRadarMentions: 2

## Issues
- [high] target_purpose_missing: Post-session truth has target evidence but no target purposes, so activity fit cannot be audited.
- [high] word_radar_dirty_clean_recall_attempt: Word Radar marked a clean/mastery recall attempt even though the captured value was noisy, duplicated, missing, or too fast to trust.
- [high] stale_current_target: Monster trace carried stale currentWord="know" for itemIndex=1; current target must match the prompted item.
- [high] activity_accuracy_missing_target_truth: An activity reported nonzero accuracy without target-level correct, missed, contaminated, or result evidence.
- [high] companion_truth_contradiction_present: The contradiction checker caught Elli making a claim that did not match authoritative activity truth.
- [high] summary_target_contradiction: Post-session truth lists "building" as both correct and missed; recovered targets must be separated from unresolved misses.
- [high] duplicate_narration_request: Duplicate narration request for word-radar|among||word_radar_mic_click within 632ms; one user action should not create two voices.
- [high] missing_psychologist_adaptation_decision: Normalized activity readings exist, but the session has no psychologist decision or next-plan diff that interprets them.
- [high] companion_false_mastery_claim: Companion claimed perfect/mastery language that contradicted authoritative Word Radar evidence.

