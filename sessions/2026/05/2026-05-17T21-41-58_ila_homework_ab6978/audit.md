# Sunny Session Audit

sessionDir: /Users/jamaltaylor/Development/sunny/logs/sessions/2026/05/2026-05-17T21-41-58_ila_homework_ab6978

## Counts
- events: 791
- gameTraces: 571
- chartAttemptEvents: 2
- transcriptWordRadarMentions: 11

## Issues
- [high] pronunciation_homophone_marked_miss: Pronunciation marked "Pear" as a miss for "pair" even though pronunciation matching accepts it.
- [high] target_purpose_missing: word-radar selected targets without carrying target purpose; the domain oracle cannot prove the activity fits the selected words.
- [high] word_radar_contaminated_attempt: Word Radar counted an attempted value that contained companion chatter instead of isolated child recall.
- [high] stale_current_target: Monster trace carried stale currentWord="ago" for itemIndex=1; current target must match the prompted item.
- [high] adaptation_ignored_word_evidence: Next plan stayed unchanged because the node was treated as non-word-driven even though target evidence was present.
- [high] duplicate_narration_request: Duplicate narration request for monster-stampede||ago.|repeat_word within 810ms; one user action should not create two voices.
- [high] word_radar_narration_request_missing: Word Radar ran, but logs contain no narration_request or game narration proof for the visible hear control.
- [warning] child_name_pronunciation: Child corrected name pronunciation; verify spoken-name preference.
- [high] companion_false_mastery_claim: Companion claimed perfect/mastery language that contradicted authoritative Word Radar evidence.
- [high] companion_false_boss_unlock_claim: Companion claimed boss unlocked, but no authoritative boss unlock trace exists.

