# Sunny Session Debug Summary

sessionId: 92a7bb86-34b9-4110-9a5d-01336e212d38
date: 2026-08-04T18:57:54.166Z
endedAt: 2026-08-04T18:58:17.906Z
child: Reina
subject: spelling
mode: default
gitCommit: ec18b68
command: npm run npx
duration_ms: 23740
result: completed

## Env Flags
- TTS_ENABLED: 
- SUNNY_MODE: 
- SUNNY_CHILD: 
- SUNNY_SUBJECT: 
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: 
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
- +2s session.started sessionType="freeform" companionName="Matilda"
- +7s transcript.accepted turnState="IDLE" round=0 transcriptLength=32
- +7s ws.send type="session_state" state="LOADING"
- +7s turn.state_changed state="LOADING"
- +7s ws.send type="session_state" state="PROCESSING"
- +7s turn.state_changed state="PROCESSING"
- +10s tool.called tool="expressCompanion" argsKeys=["emote"] hasResult=true
- +10s tool.client_result tool="expressCompanion"
- +12s ws.send type="session_state" state="SPEAKING"
- +12s turn.state_changed state="SPEAKING"
- +17s ws.send type="session_state" state="IDLE"
- +17s turn.state_changed state="IDLE"
- +22s transcript.accepted turnState="IDLE" round=1 transcriptLength=62
- +22s ws.send type="session_state" state="LOADING"
- +22s turn.state_changed state="LOADING"
- +22s session.ending turnState="LOADING" roundNumber=1 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=2
- +22s ws.send type="session_state" state="IDLE"
- +22s turn.state_changed state="IDLE"
- +22s engine.progression_computed level=78 totalXP=7755 wordsMastered=33

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 1,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "92a7bb86-34b9-4110-9a5d-01336e212d38",
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
