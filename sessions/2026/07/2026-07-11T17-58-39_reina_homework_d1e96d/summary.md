# Sunny Session Debug Summary

sessionId: d1e96d32-a6dd-413d-97f1-6590d23fc618
date: 2026-07-11T17:58:39.505Z
endedAt: 2026-07-11T18:00:36.317Z
child: Reina
subject: homework
mode: real
gitCommit: 6e85b75
command: npm run npx
duration_ms: 116812
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: demo-pashley
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false chartChildId="reina"
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s session.started sessionType="homework" companionName="Matilda"
- +30s transcript.accepted turnState="IDLE" round=0 transcriptLength=16
- +30s ws.send type="session_state" state="LOADING"
- +30s turn.state_changed state="LOADING"
- +30s ws.send type="session_state" state="PROCESSING"
- +30s turn.state_changed state="PROCESSING"
- +31s transcript.queued turnState="PROCESSING" round=1 transcriptLength=24
- +31s ws.send type="session_state" state="SPEAKING"
- +31s turn.state_changed state="SPEAKING"
- +31s ws.send type="session_state" state="IDLE"
- +31s turn.state_changed state="IDLE"
- +31s transcript.replay turnState="IDLE" round=1 transcriptLength=24
- +32s transcript.accepted turnState="IDLE" round=1 transcriptLength=24
- +32s ws.send type="session_state" state="LOADING"
- +32s turn.state_changed state="LOADING"
- +32s ws.send type="session_state" state="PROCESSING"
- +32s turn.state_changed state="PROCESSING"
- +32s ws.send type="session_state" state="SPEAKING"
- +32s turn.state_changed state="SPEAKING"
- +32s ws.send type="session_state" state="IDLE"
- +32s turn.state_changed state="IDLE"
- +114s session.ending turnState="IDLE" roundNumber=2 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=4
- +114s engine.session_finalized totalAttempts=0 accuracy=0
- +114s engine.progression_computed level=78 totalXP=7740 wordsMastered=33

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "d1e96d32-a6dd-413d-97f1-6590d23fc618",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 4
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 4,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
