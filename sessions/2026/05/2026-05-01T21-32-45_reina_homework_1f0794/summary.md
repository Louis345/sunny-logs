# Sunny Session Debug Summary

sessionId: 1f0794bb-0327-4f81-9d93-9339f6ace7a3
date: 2026-05-01T21:32:45.179Z
endedAt: 2026-05-01T21:33:06.906Z
child: Reina
subject: homework
mode: as-child
gitCommit: 97dd20e
command: npm run npx
duration_ms: 21727
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
- +5s canvas.draw mode="worksheet_pdf"
- +5s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Hey Reina! What's been happening?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
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
- +22s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=1

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "1f0794bb-0327-4f81-9d93-9339f6ace7a3",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 1
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 1,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
