# Sunny Session Audit

sessionDir: /Users/jamaltaylor/Development/sunny/logs/sessions/2026/05/2026-05-16T17-22-49_ila_homework_ad6275

## Counts
- events: 167
- gameTraces: 103
- chartAttemptEvents: 2
- transcriptWordRadarMentions: 0

## Issues
- [high] opener_game_mismatch: Session opener named spell-check, but the first launched game was pronunciation.
- [high] synthetic_prompt_in_game_state: Synthetic session prompt leaked into pronunciation state.
- [warning] repeated_help_loop: Transcript contains 8 ahead/a-head help mentions; check scaffold escalation.
- [warning] child_name_pronunciation: Child corrected name pronunciation; verify spoken-name preference.

