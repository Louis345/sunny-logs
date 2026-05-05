# Sunny Session Debug Summary

sessionId: fe9c3221-3d59-4f89-8629-e52b388a7353
date: 2026-05-01T22:53:46.915Z
endedAt: 2026-05-01T22:54:17.281Z
child: Reina
subject: homework
mode: as-child
gitCommit: 97dd20e
command: npm run npx
duration_ms: 30366
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: as-child
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +5s canvas.draw mode="worksheet_pdf"
- +5s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Hey Reina! What's been happening?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +5s canvas.draw mode="idle"
- +5s ws.send type="session_state" state="LOADING"
- +5s turn.state_changed state="LOADING"
- +5s ws.send type="session_state" state="PROCESSING"
- +5s turn.state_changed state="PROCESSING"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +6s ws.send type="session_state" state="IDLE"
- +6s turn.state_changed state="IDLE"
- +6s session.started sessionType="homework" companionName="Matilda"
- +30s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "fe9c3221-3d59-4f89-8629-e52b388a7353",
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
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 0,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
