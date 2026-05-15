# Sunny Session Debug Summary

sessionId: 0a60aa78-6ad3-4836-b469-3a964a0603a2
date: 2026-05-15T23:29:16.439Z
endedAt: 2026-05-15T23:29:49.924Z
child: Ila
subject: homework
mode: real
gitCommit: ec55b2b
command: npm run npx
duration_ms: 33485
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Ila" companionName="Elli"
- +0s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s transcript.replay turnState="IDLE" round=0 transcriptLength=863
- +1s transcript.accepted turnState="IDLE" round=0 transcriptLength=863
- +1s ws.send type="session_state" state="LOADING"
- +1s turn.state_changed state="LOADING"
- +1s ws.send type="session_state" state="PROCESSING"
- +1s turn.state_changed state="PROCESSING"
- +3s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +3s tool.client_result tool="companionAct"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +7s session.started sessionType="homework" companionName="Elli"
- +9s ws.send type="session_state" state="IDLE"
- +9s turn.state_changed state="IDLE"
- +11s transcript.accepted turnState="IDLE" round=1 transcriptLength=15
- +11s ws.send type="session_state" state="LOADING"
- +11s turn.state_changed state="LOADING"
- +11s ws.send type="session_state" state="PROCESSING"
- +11s turn.state_changed state="PROCESSING"
- +13s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +13s tool.client_result tool="companionAct"
- +15s ws.send type="session_state" state="SPEAKING"
- +15s turn.state_changed state="SPEAKING"
- +18s ws.send type="session_state" state="IDLE"
- +18s turn.state_changed state="IDLE"
- +18s transcript.accepted turnState="IDLE" round=2 transcriptLength=17
- +18s ws.send type="session_state" state="LOADING"
- +18s turn.state_changed state="LOADING"
- +18s ws.send type="session_state" state="PROCESSING"
- +18s turn.state_changed state="PROCESSING"
- +20s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +20s tool.client_result tool="companionAct"
- +22s ws.send type="session_state" state="SPEAKING"
- +22s turn.state_changed state="SPEAKING"
- +27s ws.send type="session_state" state="IDLE"
- +27s turn.state_changed state="IDLE"
- +28s transcript.accepted turnState="IDLE" round=3 transcriptLength=38
- +28s ws.send type="session_state" state="LOADING"
- +28s turn.state_changed state="LOADING"
- +28s ws.send type="session_state" state="PROCESSING"
- +28s turn.state_changed state="PROCESSING"
- +29s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +29s tool.client_result tool="companionAct"
- +31s ws.send type="session_state" state="SPEAKING"
- +31s turn.state_changed state="SPEAKING"
- +31s session.ending turnState="SPEAKING" roundNumber=4 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=8
- +31s ws.send type="session_state" state="IDLE"
- +31s turn.state_changed state="IDLE"
- +31s engine.session_finalized totalAttempts=0 accuracy=0
- +31s engine.progression_computed level=71 totalXP=7020 wordsMastered=9

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 4,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "0a60aa78-6ad3-4836-b469-3a964a0603a2",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 8
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 8,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
