# Sunny Session Audit

sessionDir: /Users/jamaltaylor/Development/sunny/logs/sessions/2026/05/2026-05-22T22-29-32_reina_homework_0b94da

## Counts
- events: 817
- gameTraces: 545
- chartAttemptEvents: 2
- transcriptWordRadarMentions: 1

## Issues
- [high] activity_companion_chatter_ratio_high: monster-stampede activity window had 13 assistant turn(s), 12 user turn(s), and 21 average assistant words; activity attempts should stay activity-owned unless the child asks for help or reports a bug.
- [high] letter_rush_selected_targets_not_materialized: Letter Rush selected 5 target(s), but launch expected/planned/launched targets were empty.
- [high] letter_rush_stale_prompted_word: Letter Rush prompted "farmer", but the launched selector targets were wrong, climb, sign, know, write.
- [high] off_assignment_target_launched: Activity reading for monster-stampede used "among", but node node-2-silent-practice approved 10 other target(s).
- [high] target_purpose_missing: Post-session truth has target evidence but no target purposes, so activity fit cannot be audited.
- [high] word_radar_mode_contract_violation: Word Radar used hidden_word_recall but recorded the result as ordinary practice; hidden recall must be diagnostic/mastery-gated by the activity mode contract.
- [high] word_radar_dirty_clean_recall_attempt: Word Radar marked a clean/mastery recall attempt even though the captured value was noisy, duplicated, missing, or too fast to trust.
- [high] activity_accuracy_missing_target_truth: An activity reported nonzero accuracy without target-level correct, missed, contaminated, or result evidence.
- [high] summary_target_contradiction: Activity summary lists "wheel" as both correct and missed; recovered targets must be separated from unresolved misses.
- [high] pronunciation_accuracy_denominator_mismatch: Pronunciation reported 100% after 10/11 target(s); accuracy must use the planned target denominator.
- [high] missing_psychologist_adaptation_decision: Normalized activity readings exist, but the session has no psychologist decision or next-plan diff that interprets them.
- [high] companion_false_mastery_claim: Companion claimed perfect/mastery language that contradicted authoritative Word Radar evidence.

