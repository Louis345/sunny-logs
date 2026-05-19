# Sunny Session Debug Summary

sessionId: 34cc7311-60e2-4b1d-861a-1029336d20dd
date: 2026-05-19T04:42:02.918Z
endedAt: 2026-05-19T04:49:55.901Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 472983
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
- +37s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +38s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +38s tool.client_result tool="sessionLog"
- +39s ws.send type="session_state" state="SPEAKING"
- +39s turn.state_changed state="SPEAKING"
- +39s ws.send type="session_state" state="IDLE"
- +39s turn.state_changed state="IDLE"
- +39s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +39s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +39s ws.send type="session_state" state="LOADING"
- +39s turn.state_changed state="LOADING"
- +39s ws.send type="session_state" state="PROCESSING"
- +39s turn.state_changed state="PROCESSING"
- +40s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +40s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +41s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +41s tool.client_result tool="companionAct"
- +41s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +42s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s flow_game.game_state_update game="word-radar" type="game_state_update"
- +43s flow_game.game_state_update game="word-radar" type="game_state_update"
- +43s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +43s tool.client_result tool="sessionLog"
- +44s flow_game.game_complete game="word-radar" type="game_complete"
- +44s flow_game.voice_control game="word-radar" type="voice_control"
- +45s ws.send type="session_state" state="SPEAKING"
- +45s turn.state_changed state="SPEAKING"
- +45s ws.send type="session_state" state="IDLE"
- +45s turn.state_changed state="IDLE"
- +45s transcript.replay turnState="IDLE" round=5 transcriptLength=5
- +45s transcript.accepted turnState="IDLE" round=5 transcriptLength=5
- +45s ws.send type="session_state" state="LOADING"
- +45s turn.state_changed state="LOADING"
- +45s ws.send type="session_state" state="PROCESSING"
- +45s turn.state_changed state="PROCESSING"
- +45s game_narration.speak text="Demo_Adaptive, spell check is ready. First target: again." activityId="spell-check" nodeId="n-spell-check-hw-adapt-weak_performance" reason="game_mount_greeting"
- +48s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +48s tool.client_result tool="companionAct"
- +49s ws.send type="session_state" state="SPEAKING"
- +49s turn.state_changed state="SPEAKING"
- +51s ws.send type="session_state" state="IDLE"
- +51s turn.state_changed state="IDLE"
- +51s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +53s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +53s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +62s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +63s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +64s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +64s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +67s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +67s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +67s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +69s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +69s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +69s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +72s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +74s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +74s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +74s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +76s flow_game.game_complete game="unknown" type="game_complete"
- +84s flow_game.voice_control game="word-radar" type="voice_control"
- +89s flow_game.game_state_update game="word-radar" type="game_state_update"
- +91s flow_game.narration_request game="word-radar" type="narration_request" word="again" reason="word_radar_response_prompt"
- +91s game_narration.speak text="again." activityId="word-radar" reason="word_radar_response_prompt"
- +468s session.ending turnState="IDLE" roundNumber=6 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=47
- +468s engine.session_finalized totalAttempts=23 accuracy=1
- +468s engine.progression_computed level=14 totalXP=1315 wordsMastered=5

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 6,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "34cc7311-60e2-4b1d-861a-1029336d20dd",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 47
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 47,
  "rewardLogEntries": 18
}
```

## Upload
Session saved locally. Upload not configured yet.
