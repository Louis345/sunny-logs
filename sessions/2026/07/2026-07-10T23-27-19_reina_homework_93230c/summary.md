# Sunny Session Debug Summary

sessionId: 93230c69-4555-4252-8ef4-098e6a4469de
date: 2026-07-10T23:27:19.169Z
endedAt: 2026-07-10T23:27:27.138Z
child: Reina
subject: homework
mode: real
gitCommit: 6e85b75
command: npm run npx
duration_ms: 7969
result: errored

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: 
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false chartChildId="reina"
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +0s session.started sessionType="homework" companionName="Matilda"
- +8s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +8s engine.session_finalized totalAttempts=0 accuracy=0
- +8s engine.progression_computed level=78 totalXP=7730 wordsMastered=33

## Errors
- [2026-07-10T23:27:27.137Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "93230c69-4555-4252-8ef4-098e6a4469de",
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
  "persistedSessionData": true,
  "postSessionError": "Not Found",
  "shouldPersistSessionData": true,
  "conversationTurns": 0,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
