# Sunny Session Debug Summary

sessionId: 46463dbb-1078-42cb-8f8b-f0c086ab96da
date: 2026-05-11T23:04:44.851Z
endedAt: 2026-05-11T23:05:41.043Z
child: Reina
subject: homework
mode: as-child
gitCommit: 7bbbafb
command: npm run npx
duration_ms: 56192
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
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Hey Reina! What's been happening?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
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
- +43s transcript.accepted turnState="IDLE" round=0 transcriptLength=28
- +43s ws.send type="session_state" state="LOADING"
- +43s turn.state_changed state="LOADING"
- +43s ws.send type="session_state" state="PROCESSING"
- +43s turn.state_changed state="PROCESSING"
- +43s transcript.queued turnState="PROCESSING" round=1 transcriptLength=31
- +46s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +46s tool.client_result tool="sessionStatus"
- +48s ws.send type="session_state" state="SPEAKING"
- +48s turn.state_changed state="SPEAKING"
- +56s session.ending turnState="SPEAKING" roundNumber=1 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=31 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=2
- +56s ws.send type="session_state" state="IDLE"
- +56s turn.state_changed state="IDLE"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 1,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "46463dbb-1078-42cb-8f8b-f0c086ab96da",
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
