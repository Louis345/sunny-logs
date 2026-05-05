# Sunny Session Debug Summary

sessionId: bc36b9cc-b56d-4dbb-b2d4-fefcc55bd44d
date: 2026-05-04T15:03:33.273Z
endedAt: 2026-05-04T15:05:22.691Z
child: Ila
subject: homework
mode: real
gitCommit: bf2c552
command: npm run npx
duration_ms: 109418
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
- +44s canvas.draw mode="worksheet_pdf"
- +44s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Hey Ila! Morning! What's going on?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +44s canvas.draw mode="idle"
- +44s ws.send type="session_state" state="LOADING"
- +44s turn.state_changed state="LOADING"
- +44s ws.send type="session_state" state="PROCESSING"
- +44s turn.state_changed state="PROCESSING"
- +44s ws.send type="session_state" state="SPEAKING"
- +44s turn.state_changed state="SPEAKING"
- +46s ws.send type="session_state" state="IDLE"
- +46s turn.state_changed state="IDLE"
- +46s session.started sessionType="homework" companionName="Elli"
- +70s transcript.accepted turnState="IDLE" round=0 transcriptLength=35
- +70s ws.send type="session_state" state="LOADING"
- +70s turn.state_changed state="LOADING"
- +70s ws.send type="session_state" state="PROCESSING"
- +70s turn.state_changed state="PROCESSING"
- +72s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +72s tool.client_result tool="companionAct"
- +74s ws.send type="session_state" state="SPEAKING"
- +74s turn.state_changed state="SPEAKING"
- +81s ws.send type="session_state" state="IDLE"
- +81s turn.state_changed state="IDLE"
- +89s transcript.accepted turnState="IDLE" round=1 transcriptLength=38
- +89s ws.send type="session_state" state="LOADING"
- +89s turn.state_changed state="LOADING"
- +89s ws.send type="session_state" state="PROCESSING"
- +89s turn.state_changed state="PROCESSING"
- +92s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +92s tool.client_result tool="companionAct"
- +94s ws.send type="session_state" state="SPEAKING"
- +94s turn.state_changed state="SPEAKING"
- +99s ws.send type="session_state" state="IDLE"
- +99s turn.state_changed state="IDLE"
- +100s transcript.accepted turnState="IDLE" round=2 transcriptLength=8
- +100s ws.send type="session_state" state="LOADING"
- +100s turn.state_changed state="LOADING"
- +100s ws.send type="session_state" state="PROCESSING"
- +100s turn.state_changed state="PROCESSING"
- +102s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +102s tool.client_result tool="companionAct"
- +104s ws.send type="session_state" state="SPEAKING"
- +104s turn.state_changed state="SPEAKING"
- +109s session.ending turnState="SPEAKING" roundNumber=3 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=6
- +109s ws.send type="session_state" state="IDLE"
- +109s turn.state_changed state="IDLE"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 3,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "bc36b9cc-b56d-4dbb-b2d4-fefcc55bd44d",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 6
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 6,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
