# Sunny Session Debug Summary

sessionId: 52f9b2e2-db89-4a8f-b7b8-e07636eea0b2
date: 2026-07-21T00:55:25.045Z
endedAt: 2026-07-21T00:57:04.473Z
child: Reina
subject: homework
mode: real
gitCommit: 8097a27
command: npm run npx
duration_ms: 99428
result: errored

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: 
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false chartChildId="reina"
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +0s companion.greeting_generated source="live_homework_context" words=9
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Your first challenge is ready. Want to try it?" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s ws.send type="session_state" state="LOADING"
- +1s turn.state_changed state="LOADING"
- +1s ws.send type="session_state" state="PROCESSING"
- +1s turn.state_changed state="PROCESSING"
- +1s ws.send type="session_state" state="SPEAKING"
- +1s turn.state_changed state="SPEAKING"
- +2s ws.send type="session_state" state="IDLE"
- +2s turn.state_changed state="IDLE"
- +2s session.started sessionType="homework" companionName="Matilda"
- +12s flow_game.game_state_update game="generated-baseline" type="game_state_update" activityId="act-wordproblems-speed"
- +12s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-wordproblems-speed"
- +19s flow_game.attempt_event game="unknown" type="attempt_event"
- +20s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-wordproblems-speed"
- +22s flow_game.attempt_event game="unknown" type="attempt_event"
- +28s flow_game.game_state_update game="generated-baseline" type="game_state_update" activityId="act-factretrieval-puzzle"
- +28s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-factretrieval-puzzle"
- +30s flow_game.attempt_event game="unknown" type="attempt_event"
- +31s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-factretrieval-puzzle"
- +32s flow_game.attempt_event game="unknown" type="attempt_event"
- +33s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-factretrieval-puzzle"
- +36s flow_game.attempt_event game="unknown" type="attempt_event"
- +37s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-factretrieval-puzzle"
- +38s flow_game.attempt_event game="unknown" type="attempt_event"
- +39s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-factretrieval-puzzle"
- +42s flow_game.attempt_event game="unknown" type="attempt_event"
- +50s flow_game.game_state_update game="generated-baseline" type="game_state_update" activityId="act-wordproblems-puzzle"
- +50s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-wordproblems-puzzle"
- +71s flow_game.attempt_event game="unknown" type="attempt_event"
- +73s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-wordproblems-puzzle"
- +82s flow_game.attempt_event game="unknown" type="attempt_event"
- +84s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-wordproblems-puzzle"
- +99s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +99s engine.progression_computed level=78 totalXP=7755 wordsMastered=33

## Errors
- [2026-07-21T00:57:04.472Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "52f9b2e2-db89-4a8f-b7b8-e07636eea0b2",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 0
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "postSessionError": "messages: text content blocks must be non-empty",
  "shouldPersistSessionData": true,
  "conversationTurns": 0,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
