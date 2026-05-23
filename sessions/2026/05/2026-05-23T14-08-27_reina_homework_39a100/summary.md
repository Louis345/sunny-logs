# Sunny Session Debug Summary

sessionId: 39a100c6-2329-44a1-ae3e-b392d5b2fd21
date: 2026-05-23T14:08:27.097Z
endedAt: 2026-05-23T14:09:22.672Z
child: Reina
subject: homework
mode: real
gitCommit: cc49f2b
command: npm run npx
duration_ms: 55575
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
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +2s session.started sessionType="homework" companionName="Matilda"
- +24s transcript.accepted turnState="IDLE" round=0 transcriptLength=5
- +24s ws.send type="session_state" state="LOADING"
- +24s turn.state_changed state="LOADING"
- +24s ws.send type="session_state" state="PROCESSING"
- +24s turn.state_changed state="PROCESSING"
- +27s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +27s tool.client_result tool="sessionStatus"
- +30s tool.called tool="launchGame" argsKeys=["name","type","word"] hasResult=true
- +30s tool.client_result tool="launchGame"
- +30s canvas.draw mode="spell-check" canvasRevision=1
- +31s ws.send type="session_state" state="SPEAKING"
- +31s turn.state_changed state="SPEAKING"
- +35s flow_game.voice_control game="word-radar" type="voice_control"
- +36s ws.send type="session_state" state="IDLE"
- +36s turn.state_changed state="IDLE"
- +36s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=1 tts="on"
- +38s transcript.suppressed reason="word-radar_active_game" turnState="IDLE" round=1 transcriptLength=128
- +38s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s flow_game.game_state_update game="word-radar" type="game_state_update"
- +43s flow_game.game_state_update game="word-radar" type="game_state_update"
- +47s transcript.urgent_learning_organic intent="stop_or_pause" reason="child_requested_pause" stateBefore="IDLE" round=1 transcriptLength=151 currentWord="among" activityId="word-radar"
- +47s transcript.suppressed reason="word-radar_active_game" turnState="IDLE" round=1 transcriptLength=151
- +49s session.ending turnState="IDLE" roundNumber=1 isEnding=true childName="Reina" canvasMode="spell-check" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=true activeSpellCheckWord="sign" tts="on" conversationTurns=2
- +49s engine.session_finalized totalAttempts=0 accuracy=0
- +49s engine.progression_computed level=111 totalXP=11080 wordsMastered=49

## Activity Evidence
- activityReadings: 1
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 1,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "39a100c6-2329-44a1-ae3e-b392d5b2fd21",
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
