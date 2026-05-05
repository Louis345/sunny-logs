# Sunny Session Debug Summary

sessionId: 1eee224a-01a3-477c-9d53-a5baee340e90
date: 2026-05-02T04:01:59.359Z
endedAt: 2026-05-02T04:03:06.421Z
child: Reina
subject: homework
mode: as-child
gitCommit: 97dd20e
command: npm run npx
duration_ms: 67062
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
- +6s canvas.draw mode="worksheet_pdf"
- +6s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Reina! Good morning — how'd you sleep?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +6s canvas.draw mode="idle"
- +7s ws.send type="session_state" state="LOADING"
- +7s turn.state_changed state="LOADING"
- +7s ws.send type="session_state" state="PROCESSING"
- +7s turn.state_changed state="PROCESSING"
- +7s ws.send type="session_state" state="SPEAKING"
- +7s turn.state_changed state="SPEAKING"
- +8s ws.send type="session_state" state="IDLE"
- +8s turn.state_changed state="IDLE"
- +8s session.started sessionType="homework" companionName="Matilda"
- +67s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "1eee224a-01a3-477c-9d53-a5baee340e90",
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
