# Sunny Session Debug Summary

sessionId: e89c7a5e-d08b-4d29-b274-0abe778f2997
date: 2026-05-11T22:41:11.223Z
endedAt: 2026-05-11T22:41:35.847Z
child: Reina
subject: homework
mode: as-child
gitCommit: 7bbbafb
command: npm run npx
duration_ms: 24624
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
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Reina! Good to see you — what's new?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
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
- +25s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "e89c7a5e-d08b-4d29-b274-0abe778f2997",
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
