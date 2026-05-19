# Sunny Session Debug Summary

sessionId: 20ec0555-dd96-4bf5-a0eb-f2a0a802bfd9
date: 2026-05-19T05:33:53.178Z
endedAt: 2026-05-19T05:37:01.911Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 188733
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: real
- SUNNY_CHILD: demo_adaptive
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +52s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +52s tool.client_result tool="sessionLog"
- +54s ws.send type="session_state" state="SPEAKING"
- +54s turn.state_changed state="SPEAKING"
- +57s ws.send type="session_state" state="IDLE"
- +57s turn.state_changed state="IDLE"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +58s transcript.accepted turnState="IDLE" round=5 transcriptLength=16
- +58s ws.send type="session_state" state="LOADING"
- +58s turn.state_changed state="LOADING"
- +58s ws.send type="session_state" state="PROCESSING"
- +58s turn.state_changed state="PROCESSING"
- +59s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +60s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +60s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +60s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +62s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +62s tool.client_result tool="companionAct"
- +62s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +63s ws.send type="session_state" state="SPEAKING"
- +63s turn.state_changed state="SPEAKING"
- +63s ws.send type="session_state" state="IDLE"
- +63s turn.state_changed state="IDLE"
- +67s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +68s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +68s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +69s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +69s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +69s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +72s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +72s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +74s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +74s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +77s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +77s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +77s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +82s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +82s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +82s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +84s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +84s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +84s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +86s flow_game.game_complete game="unknown" type="game_complete"
- +93s flow_game.voice_control game="word-radar" type="voice_control"
- +99s flow_game.game_state_update game="word-radar" type="game_state_update"
- +101s flow_game.narration_request game="word-radar" type="narration_request" word="again" reason="word_radar_response_prompt"
- +101s game_narration.speak text="again." activityId="word-radar" reason="word_radar_response_prompt"
- +109s flow_game.game_state_update game="word-radar" type="game_state_update"
- +111s flow_game.narration_request game="word-radar" type="narration_request" word="around" reason="word_radar_response_prompt"
- +111s game_narration.speak text="around." activityId="word-radar" reason="word_radar_response_prompt"
- +119s flow_game.game_state_update game="word-radar" type="game_state_update"
- +123s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +123s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +131s flow_game.game_state_update game="word-radar" type="game_state_update"
- +134s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +134s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +142s flow_game.game_state_update game="word-radar" type="game_state_update"
- +145s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +145s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +153s flow_game.game_state_update game="word-radar" type="game_state_update"
- +156s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +156s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +164s flow_game.game_state_update game="word-radar" type="game_state_update"
- +165s flow_game.game_state_update game="word-radar" type="game_state_update"
- +166s flow_game.game_complete game="word-radar" type="game_complete"
- +167s flow_game.voice_control game="word-radar" type="voice_control"
- +176s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +178s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +178s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +180s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +180s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +180s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +181s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +182s session.ending turnState="IDLE" roundNumber=6 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=66
- +182s engine.session_finalized totalAttempts=31 accuracy=0.8064516129032258
- +182s engine.progression_computed level=8 totalXP=725 wordsMastered=0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 6,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "20ec0555-dd96-4bf5-a0eb-f2a0a802bfd9",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 66
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 66,
  "rewardLogEntries": 21
}
```

## Upload
Session saved locally. Upload not configured yet.
