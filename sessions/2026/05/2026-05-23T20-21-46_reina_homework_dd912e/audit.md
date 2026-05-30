# Sunny Session Audit

sessionDir: /Users/jamaltaylor/Development/sunny/logs/sessions/2026/05/2026-05-23T20-21-46_reina_homework_dd912e

## Counts
- events: 315
- gameTraces: 304
- chartAttemptEvents: 13
- transcriptWordRadarMentions: 0

## Issues
- [high] target_purpose_missing: Post-session truth has target evidence but no target purposes, so activity fit cannot be audited.
- [high] activity_accuracy_missing_target_truth: An activity reported nonzero accuracy without target-level correct, missed, contaminated, or result evidence.
- [high] word_radar_answer_visible: Word Radar exposed the target during a recall/response state; this invalidates recall evidence.
- [high] missing_psychologist_adaptation_decision: Normalized activity readings exist, but the session has no psychologist decision or next-plan diff that interprets them.

