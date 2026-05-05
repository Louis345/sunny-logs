# Sunny Session Debug Summary

sessionId: 107d502c-76fa-4c28-8153-eb22988c86d8
date: 2026-05-02T00:41:17.591Z
endedAt: 2026-05-02T00:45:47.025Z
child: Reina
subject: homework
mode: as-child
gitCommit: 97dd20e
command: npm run npx
duration_ms: 269434
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
- +5s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Reina! How's your night going?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +5s canvas.draw mode="idle"
- +6s ws.send type="session_state" state="LOADING"
- +6s turn.state_changed state="LOADING"
- +6s ws.send type="session_state" state="PROCESSING"
- +6s turn.state_changed state="PROCESSING"
- +6s ws.send type="session_state" state="SPEAKING"
- +6s turn.state_changed state="SPEAKING"
- +7s ws.send type="session_state" state="IDLE"
- +7s turn.state_changed state="IDLE"
- +7s session.started sessionType="homework" companionName="Matilda"
- +269s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "107d502c-76fa-4c28-8153-eb22988c86d8",
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
