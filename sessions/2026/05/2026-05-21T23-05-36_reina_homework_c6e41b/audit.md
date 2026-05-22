# Sunny Session Audit

sessionDir: /Users/jamaltaylor/Development/sunny/logs/sessions/2026/05/2026-05-21T23-05-36_reina_homework_c6e41b

## Counts
- events: 65
- gameTraces: 10
- chartAttemptEvents: 2
- transcriptWordRadarMentions: 2

## Issues
- [high] first_node_target_count_mismatch: Session opener showed 10 target(s) for word-radar, but normalized evidence only contains 1.
- [high] target_purpose_missing: Post-session truth has target evidence but no target purposes, so activity fit cannot be audited.
- [high] duplicate_narration_request: Duplicate narration request for word-radar|among||word_radar_mic_click within 583ms; one user action should not create two voices.
- [high] missing_psychologist_adaptation_decision: Normalized activity readings exist, but the session has no psychologist decision or next-plan diff that interprets them.

