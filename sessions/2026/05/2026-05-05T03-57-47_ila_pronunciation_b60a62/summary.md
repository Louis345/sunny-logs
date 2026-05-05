# Sunny Session Debug Summary

sessionId: b60a62f7-c495-4eb1-920e-f3b758717552
date: 2026-05-05T03:57:47.708Z
endedAt: 2026-05-05T03:58:22.883Z
child: Ila
subject: pronunciation
mode: as-child
gitCommit: 8f8e5f8
command: npm run npx
duration_ms: 35175
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: as-child
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: pronunciation
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Ila" companionName="Elli"
- +5s canvas.draw mode="worksheet_pdf"
- +5s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Ila! Night owl! What's on your mind?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +5s canvas.draw mode="idle"
- +5s ws.send type="session_state" state="LOADING"
- +5s turn.state_changed state="LOADING"
- +5s ws.send type="session_state" state="PROCESSING"
- +5s turn.state_changed state="PROCESSING"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +5s ws.send type="session_state" state="IDLE"
- +5s turn.state_changed state="IDLE"
- +5s session.started sessionType="pronunciation" companionName="Elli"
- +21s transcript.accepted turnState="IDLE" round=0 transcriptLength=7
- +21s ws.send type="session_state" state="LOADING"
- +21s turn.state_changed state="LOADING"
- +22s ws.send type="session_state" state="PROCESSING"
- +22s turn.state_changed state="PROCESSING"
- +22s transcript.queued turnState="PROCESSING" round=1 transcriptLength=8
- +23s transcript.queued turnState="PROCESSING" round=1 transcriptLength=6
- +24s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +24s tool.client_result tool="companionAct"
- +25s ws.send type="session_state" state="SPEAKING"
- +25s turn.state_changed state="SPEAKING"
- +25s ws.send type="session_state" state="IDLE"
- +25s turn.state_changed state="IDLE"
- +25s transcript.replay turnState="IDLE" round=1 transcriptLength=6
- +25s transcript.accepted turnState="IDLE" round=1 transcriptLength=6
- +25s ws.send type="session_state" state="LOADING"
- +25s turn.state_changed state="LOADING"
- +25s ws.send type="session_state" state="PROCESSING"
- +25s turn.state_changed state="PROCESSING"
- +25s transcript.duplicate_suppressed turnState="PROCESSING" round=2 transcriptLength=6
- +25s transcript.duplicate_suppressed turnState="PROCESSING" round=2 transcriptLength=6
- +27s transcript.queued turnState="PROCESSING" round=2 transcriptLength=6
- +27s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +27s tool.client_result tool="companionAct"
- +28s transcript.duplicate_suppressed turnState="PROCESSING" round=2 transcriptLength=6
- +29s ws.send type="session_state" state="SPEAKING"
- +29s turn.state_changed state="SPEAKING"
- +29s ws.send type="session_state" state="IDLE"
- +29s turn.state_changed state="IDLE"
- +29s transcript.replay turnState="IDLE" round=2 transcriptLength=6
- +29s transcript.accepted turnState="IDLE" round=2 transcriptLength=6
- +29s ws.send type="session_state" state="LOADING"
- +29s turn.state_changed state="LOADING"
- +29s ws.send type="session_state" state="PROCESSING"
- +29s turn.state_changed state="PROCESSING"
- +31s transcript.queued turnState="PROCESSING" round=3 transcriptLength=6
- +31s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +31s tool.client_result tool="companionAct"
- +32s ws.send type="session_state" state="SPEAKING"
- +32s turn.state_changed state="SPEAKING"
- +32s ws.send type="session_state" state="IDLE"
- +32s turn.state_changed state="IDLE"
- +32s transcript.replay turnState="IDLE" round=3 transcriptLength=6
- +32s transcript.accepted turnState="IDLE" round=3 transcriptLength=6
- +32s ws.send type="session_state" state="LOADING"
- +32s turn.state_changed state="LOADING"
- +32s ws.send type="session_state" state="PROCESSING"
- +32s turn.state_changed state="PROCESSING"
- +34s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +34s tool.client_result tool="sessionStatus"
- +35s session.ending turnState="PROCESSING" roundNumber=4 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=6
- +35s ws.send type="session_state" state="IDLE"
- +35s turn.state_changed state="IDLE"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 4,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "b60a62f7-c495-4eb1-920e-f3b758717552",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
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
