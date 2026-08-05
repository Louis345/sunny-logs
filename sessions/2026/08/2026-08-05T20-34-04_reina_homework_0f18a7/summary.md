# Sunny Session Debug Summary

sessionId: 0f18a74e-9a06-4b9c-bce8-28725fdc0c04
date: 2026-08-05T20:34:04.897Z
endedAt: 2026-08-05T20:35:28.285Z
child: Reina
subject: homework
mode: real
gitCommit: ec18b68
command: npm run npx
duration_ms: 83388
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: reina
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
- +10s transcript.accepted turnState="IDLE" round=0 transcriptLength=48
- +10s ws.send type="session_state" state="LOADING"
- +10s turn.state_changed state="LOADING"
- +10s ws.send type="session_state" state="PROCESSING"
- +10s turn.state_changed state="PROCESSING"
- +13s flow_game.game_state_update game="generated-baseline" type="game_state_update" activityId="N1"
- +14s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +14s tool.client_result tool="sessionStatus"
- +14s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="N1"
- +17s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +17s tool.client_result tool="companionAct"
- +19s ws.send type="session_state" state="SPEAKING"
- +19s turn.state_changed state="SPEAKING"
- +27s ws.send type="session_state" state="IDLE"
- +27s turn.state_changed state="IDLE"
- +32s flow_game.game_state_update game="generated-baseline" type="game_state_update" activityId="N1"
- +32s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="N1"
- +39s flow_game.game_state_update game="generated-baseline" type="game_state_update" activityId="N1"
- +39s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="N1"
- +47s flow_game.game_state_update game="generated-baseline" type="game_state_update" activityId="N1"
- +48s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="N1"
- +49s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="N1"
- +49s ws.send type="session_state" state="LOADING"
- +49s turn.state_changed state="LOADING"
- +49s ws.send type="session_state" state="PROCESSING"
- +49s turn.state_changed state="PROCESSING"
- +49s ws.send type="session_state" state="SPEAKING"
- +49s turn.state_changed state="SPEAKING"
- +50s ws.send type="session_state" state="IDLE"
- +50s turn.state_changed state="IDLE"
- +81s session.ending turnState="IDLE" roundNumber=1 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=2
- +81s engine.session_finalized totalAttempts=0 accuracy=0
- +81s engine.progression_computed level=78 totalXP=7760 wordsMastered=33

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 1,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "0f18a74e-9a06-4b9c-bce8-28725fdc0c04",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 2
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 2,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
