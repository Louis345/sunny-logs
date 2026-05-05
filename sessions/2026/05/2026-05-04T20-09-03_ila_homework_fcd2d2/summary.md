# Sunny Session Debug Summary

sessionId: fcd2d2d9-9872-4f8c-a990-df8fec83f485
date: 2026-05-04T20:09:03.261Z
endedAt: 2026-05-04T20:10:06.968Z
child: Ila
subject: homework
mode: real
gitCommit: bf2c552
command: npm run npx
duration_ms: 63707
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
- +43s canvas.draw mode="worksheet_pdf"
- +43s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Hey Ila! What's been happening?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +43s canvas.draw mode="idle"
- +44s ws.send type="session_state" state="LOADING"
- +44s turn.state_changed state="LOADING"
- +44s ws.send type="session_state" state="PROCESSING"
- +44s turn.state_changed state="PROCESSING"
- +44s ws.send type="session_state" state="SPEAKING"
- +44s turn.state_changed state="SPEAKING"
- +45s ws.send type="session_state" state="IDLE"
- +45s turn.state_changed state="IDLE"
- +45s session.started sessionType="homework" companionName="Elli"
- +46s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +46s canvas.draw mode="idle"
- +49s ws.send type="session_state" state="LOADING"
- +49s turn.state_changed state="LOADING"
- +49s ws.send type="session_state" state="PROCESSING"
- +49s turn.state_changed state="PROCESSING"
- +51s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +51s tool.client_result tool="companionAct"
- +54s ws.send type="session_state" state="SPEAKING"
- +54s turn.state_changed state="SPEAKING"
- +59s ws.send type="session_state" state="IDLE"
- +59s turn.state_changed state="IDLE"
- +64s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=3

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "fcd2d2d9-9872-4f8c-a990-df8fec83f485",
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
