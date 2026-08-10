# Sunny Session Debug Summary

sessionId: ff5f9639-0e60-443e-87a7-53e1ddb70da8
date: 2026-08-10T00:12:06.752Z
endedAt: 2026-08-10T00:29:32.956Z
child: Reina
subject: homework
mode: real
gitCommit: 9beac0f
command: npm run npx
duration_ms: 1046204
result: errored

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
- +1012s transcript.accepted turnState="IDLE" round=0 transcriptLength=3
- +1012s ws.send type="session_state" state="LOADING"
- +1012s turn.state_changed state="LOADING"
- +1012s ws.send type="session_state" state="PROCESSING"
- +1012s turn.state_changed state="PROCESSING"
- +1015s ws.send type="session_state" state="SPEAKING"
- +1015s turn.state_changed state="SPEAKING"
- +1019s ws.send type="session_state" state="IDLE"
- +1019s turn.state_changed state="IDLE"
- +1032s transcript.accepted turnState="IDLE" round=1 transcriptLength=5
- +1032s ws.send type="session_state" state="LOADING"
- +1032s turn.state_changed state="LOADING"
- +1032s ws.send type="session_state" state="PROCESSING"
- +1032s turn.state_changed state="PROCESSING"
- +1035s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +1035s tool.client_result tool="sessionStatus"
- +1037s ws.send type="session_state" state="SPEAKING"
- +1037s turn.state_changed state="SPEAKING"
- +1043s ws.send type="session_state" state="IDLE"
- +1043s turn.state_changed state="IDLE"
- +1046s session.ending turnState="IDLE" roundNumber=2 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=4
- +1046s engine.session_finalized totalAttempts=0 accuracy=0
- +1046s engine.progression_computed level=15 totalXP=1400 wordsMastered=4

## Errors
- [2026-08-10T00:29:32.943Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "ff5f9639-0e60-443e-87a7-53e1ddb70da8",
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
  "postSessionError": "ENOENT: no such file or directory, open '/Users/jamaltaylor/Development/sunny-feedback-ingestion-proof-2026-08-09-1805/src/context/reina/soul.md'",
  "shouldPersistSessionData": true,
  "conversationTurns": 4,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
