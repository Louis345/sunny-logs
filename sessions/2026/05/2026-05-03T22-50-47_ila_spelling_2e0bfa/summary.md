# Sunny Session Debug Summary

sessionId: 2e0bfa34-b94a-40cf-b24a-94bf99eb9ebd
date: 2026-05-03T22:50:47.729Z
endedAt: 2026-05-03T22:54:24.204Z
child: Ila
subject: spelling
mode: as-child
gitCommit: 8e7077a
command: npm run npx
duration_ms: 216475
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: as-child
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: onboarding
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Ila" companionName="Elli"
- +5s canvas.draw mode="worksheet_pdf"
- +5s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Ila! Good to see you — what's new?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +5s canvas.draw mode="idle"
- +5s ws.send type="session_state" state="LOADING"
- +5s turn.state_changed state="LOADING"
- +5s ws.send type="session_state" state="PROCESSING"
- +5s turn.state_changed state="PROCESSING"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +5s ws.send type="session_state" state="IDLE"
- +5s turn.state_changed state="IDLE"
- +5s session.started sessionType="spelling" companionName="Elli"
- +216s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "2e0bfa34-b94a-40cf-b24a-94bf99eb9ebd",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
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
