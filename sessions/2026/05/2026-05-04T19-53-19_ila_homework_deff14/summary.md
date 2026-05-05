# Sunny Session Debug Summary

sessionId: deff1429-0a2b-4185-81f6-d4a212a5af42
date: 2026-05-04T19:53:19.087Z
endedAt: 2026-05-04T19:54:35.699Z
child: Ila
subject: homework
mode: real
gitCommit: bf2c552
command: npm run npx
duration_ms: 76612
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
- +42s canvas.draw mode="worksheet_pdf"
- +42s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Ila! How was school today?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +42s canvas.draw mode="idle"
- +42s ws.send type="session_state" state="LOADING"
- +42s turn.state_changed state="LOADING"
- +42s ws.send type="session_state" state="PROCESSING"
- +42s turn.state_changed state="PROCESSING"
- +42s ws.send type="session_state" state="SPEAKING"
- +42s turn.state_changed state="SPEAKING"
- +43s ws.send type="session_state" state="IDLE"
- +43s turn.state_changed state="IDLE"
- +43s session.started sessionType="homework" companionName="Elli"
- +64s ws.send type="session_state" state="LOADING"
- +64s turn.state_changed state="LOADING"
- +64s ws.send type="session_state" state="PROCESSING"
- +64s turn.state_changed state="PROCESSING"
- +66s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +66s tool.client_result tool="companionAct"
- +69s ws.send type="session_state" state="SPEAKING"
- +69s turn.state_changed state="SPEAKING"
- +75s ws.send type="session_state" state="IDLE"
- +75s turn.state_changed state="IDLE"
- +77s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=3

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "deff1429-0a2b-4185-81f6-d4a212a5af42",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 3
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 3,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
