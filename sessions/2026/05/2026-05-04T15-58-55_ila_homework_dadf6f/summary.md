# Sunny Session Debug Summary

sessionId: dadf6f5a-e4ec-43db-bfe1-ac8324dbfd7a
date: 2026-05-04T15:58:55.406Z
endedAt: 2026-05-04T16:00:09.317Z
child: Ila
subject: homework
mode: real
gitCommit: bf2c552
command: npm run npx
duration_ms: 73911
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Ila" companionName="Elli"
- +41s canvas.draw mode="worksheet_pdf"
- +41s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Ila! You're up — how's your morning so far?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +41s canvas.draw mode="idle"
- +41s ws.send type="session_state" state="LOADING"
- +41s turn.state_changed state="LOADING"
- +41s ws.send type="session_state" state="PROCESSING"
- +41s turn.state_changed state="PROCESSING"
- +41s ws.send type="session_state" state="SPEAKING"
- +41s turn.state_changed state="SPEAKING"
- +43s ws.send type="session_state" state="IDLE"
- +43s turn.state_changed state="IDLE"
- +43s session.started sessionType="homework" companionName="Elli"
- +74s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "dadf6f5a-e4ec-43db-bfe1-ac8324dbfd7a",
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
