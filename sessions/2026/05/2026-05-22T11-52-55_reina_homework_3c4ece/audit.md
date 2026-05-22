# Sunny Session Audit

sessionDir: /Users/jamaltaylor/Development/sunny/logs/sessions/2026/05/2026-05-22T11-52-55_reina_homework_3c4ece

## Counts
- events: 801
- gameTraces: 448
- chartAttemptEvents: 2
- transcriptWordRadarMentions: 3

## Issues
- [high] off_assignment_target_launched: Activity reading for letter-rush used "farmer", but node node-5-silent-mastery approved 5 other target(s).
- [high] target_purpose_missing: Post-session truth has target evidence but no target purposes, so activity fit cannot be audited.
- [high] word_radar_dirty_clean_recall_attempt: Word Radar marked a clean/mastery recall attempt even though the captured value was noisy, duplicated, missing, or too fast to trust.
- [high] companion_truth_contradiction_present: The contradiction checker caught Elli making a claim that did not match authoritative activity truth.
- [high] activity_accuracy_missing_target_truth: An activity reported nonzero accuracy without target-level correct, missed, contaminated, or result evidence.
- [high] summary_target_contradiction: Activity summary lists "among" as both correct and missed; recovered targets must be separated from unresolved misses.
- [high] pronunciation_homophone_marked_miss: Pronunciation marked "Right" as a miss for "write" even though pronunciation matching accepts it.
- [high] duplicate_narration_request: Duplicate narration request for letter-rush||farmer.|word_prompt within 4ms; one user action should not create two voices.
- [high] missing_psychologist_adaptation_decision: Normalized activity readings exist, but the session has no psychologist decision or next-plan diff that interprets them.
- [high] companion_false_mastery_claim: Companion claimed perfect/mastery language that contradicted authoritative Word Radar evidence.

