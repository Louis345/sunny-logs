# Sunny Session Debug Summary

sessionId: 6e4e51bc-8bc0-4252-9795-d1d790d1151b
date: 2026-05-01T02:53:15.941Z
endedAt: 2026-05-01T02:53:53.493Z
child: Reina
subject: homework
mode: as-child
gitCommit: 484e23a
command: npm run npx
duration_ms: 37552
result: completed

## Env Flags
- TTS_ENABLED: 
- SUNNY_MODE: as-child
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +7s canvas.draw mode="worksheet_pdf"
- +7s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Hey Reina! Still going strong tonight?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +7s canvas.draw mode="idle"
- +9s ws.send type="session_state" state="LOADING"
- +9s turn.state_changed state="LOADING"
- +9s ws.send type="session_state" state="PROCESSING"
- +9s turn.state_changed state="PROCESSING"
- +9s ws.send type="session_state" state="SPEAKING"
- +9s turn.state_changed state="SPEAKING"
- +11s ws.send type="session_state" state="IDLE"
- +11s turn.state_changed state="IDLE"
- +11s session.started sessionType="homework" companionName="Matilda"
- +38s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=2

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "6e4e51bc-8bc0-4252-9795-d1d790d1151b",
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
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 2,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
