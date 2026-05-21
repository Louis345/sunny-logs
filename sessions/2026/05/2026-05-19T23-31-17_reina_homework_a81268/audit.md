# Sunny Session Audit

sessionDir: /Users/jamaltaylor/Development/sunny/logs/sessions/2026/05/2026-05-19T23-31-17_reina_homework_a81268

## Counts
- events: 577
- gameTraces: 347
- chartAttemptEvents: 2
- transcriptWordRadarMentions: 2

## Issues
- [high] word_radar_dirty_clean_recall_attempt: Word Radar marked a clean/mastery recall attempt even though the captured value was noisy, duplicated, missing, or too fast to trust.
- [high] stale_current_target: Monster trace carried stale currentWord="know" for itemIndex=1; current target must match the prompted item.
- [high] activity_accuracy_missing_target_truth: An activity reported nonzero accuracy without target-level correct, missed, contaminated, or result evidence.
- [high] adaptation_ignored_word_evidence: Next plan stayed unchanged because the node was treated as non-word-driven even though target evidence was present.
- [high] companion_truth_contradiction_present: The contradiction checker caught Elli making a claim that did not match authoritative activity truth.
- [high] word_radar_audio_visible_without_playback_proof: Word Radar requested target narration, but the session has no playback proof that the visible hear/speaker control actually played audio.
- [high] word_radar_voice_disabled_with_hear_control: Word Radar showed a voice/hear control while voiceEnabled=false; the child sees an affordance that cannot be trusted.
- [high] mystery_word_evidence_ignored: Mystery/Wheel target evidence existed for the node, but the next-plan decision ignored it as non-word-driven.
- [high] visible_adaptation_diff_missing: Post-session adaptation says it changed, but plan-before/plan-after do not contain a visible board shape or readable next-board diff.
- [high] companion_stale_or_wrong_target_hint: Elli gave a stale, repeated, or academically wrong target-specific hint instead of grounding help in current activity truth.
- [high] companion_false_mastery_claim: Companion claimed perfect/mastery language that contradicted authoritative Word Radar evidence.

