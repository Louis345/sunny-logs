# Sunny Session Audit

sessionDir: /Users/jamaltaylor/Development/sunny/logs/sessions/2026/05/2026-05-19T23-12-32_ila_homework_220ebf

## Counts
- events: 835
- gameTraces: 536
- chartAttemptEvents: 2
- transcriptWordRadarMentions: 4

## Issues
- [high] activity_accuracy_missing_target_truth: An activity reported nonzero accuracy without target-level correct, missed, contaminated, or result evidence.
- [high] companion_truth_contradiction_present: The contradiction checker caught Elli making a claim that did not match authoritative activity truth.
- [high] adaptation_ignored_word_evidence: Next plan stayed unchanged because the node was treated as non-word-driven even though target evidence was present.
- [high] target_purpose_activity_mismatch: pronunciation selected target "ago" with purpose reinforce; accepted purposes are recognize, read_fluently, pronounce, spell_from_memory, unknown.
- [high] duplicate_narration_request: Duplicate narration request for word-radar|scientist||word_radar_mic_click within 901ms; one user action should not create two voices.
- [high] word_radar_audio_visible_without_playback_proof: Word Radar requested target narration, but the session has no playback proof that the visible hear/speaker control actually played audio.
- [high] word_radar_voice_disabled_with_hear_control: Word Radar showed a voice/hear control while voiceEnabled=false; the child sees an affordance that cannot be trusted.
- [high] visible_adaptation_diff_missing: Post-session adaptation says it changed, but plan-before/plan-after do not contain a visible board shape or readable next-board diff.
- [warning] repeated_help_loop: Transcript contains 12 ahead/a-head help mentions; check scaffold escalation.
- [warning] child_name_pronunciation: Child corrected name pronunciation; verify spoken-name preference.
- [high] companion_stale_or_wrong_target_hint: Elli gave a stale, repeated, or academically wrong target-specific hint instead of grounding help in current activity truth.
- [high] companion_false_mastery_claim: Companion claimed perfect/mastery language that contradicted authoritative Word Radar evidence.

