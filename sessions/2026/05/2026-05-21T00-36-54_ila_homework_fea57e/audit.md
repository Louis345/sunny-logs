# Sunny Session Audit

sessionDir: /Users/jamaltaylor/Development/sunny/logs/sessions/2026/05/2026-05-21T00-36-54_ila_homework_fea57e

## Counts
- events: 769
- gameTraces: 489
- chartAttemptEvents: 2
- transcriptWordRadarMentions: 2

## Issues
- [high] off_assignment_target_launched: Activity reading for word-radar used "pair", but node n-word-radar-hw-spelling_test-bb11de93 approved 3 other target(s).
- [high] target_purpose_missing: Post-session truth has target evidence but no target purposes, so activity fit cannot be audited.
- [high] summary_target_contradiction: Activity summary lists "ago" as both correct and missed; recovered targets must be separated from unresolved misses.
- [high] pronunciation_homophone_marked_miss: Pronunciation marked "Payer" as a miss for "pair" even though pronunciation matching accepts it.
- [high] word_radar_dirty_clean_recall_attempt: Word Radar marked a clean/mastery recall attempt even though the captured value was noisy, duplicated, missing, or too fast to trust.
- [high] activity_accuracy_missing_target_truth: An activity reported nonzero accuracy without target-level correct, missed, contaminated, or result evidence.
- [high] target_purpose_activity_mismatch: pronunciation selected target "ago" with purpose reinforce; accepted purposes are recognize, read_fluently, pronounce, spell_from_memory, unknown.
- [high] missing_psychologist_adaptation_decision: Normalized activity readings exist, but the session has no psychologist decision or next-plan diff that interprets them.
- [warning] repeated_help_loop: Transcript contains 10 ahead/a-head help mentions; check scaffold escalation.
- [warning] child_name_pronunciation: Child corrected name pronunciation; verify spoken-name preference.
- [high] companion_stale_or_wrong_target_hint: Elli gave a stale, repeated, or academically wrong target-specific hint instead of grounding help in current activity truth.
- [high] companion_false_mastery_claim: Companion claimed perfect/mastery language that contradicted authoritative Word Radar evidence.

