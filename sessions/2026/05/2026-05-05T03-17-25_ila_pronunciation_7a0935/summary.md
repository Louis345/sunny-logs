# Sunny Session Debug Summary

sessionId: 7a09355e-b9d8-43ba-9095-76282ccab935
date: 2026-05-05T03:17:25.000Z
endedAt: 2026-05-05T03:18:38.287Z
child: Ila
subject: pronunciation
mode: as-child
gitCommit: 8f8e5f8
command: npm run npx
duration_ms: 73287
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: as-child
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: pronunciation
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +26s ws.send type="session_state" state="IDLE"
- +26s turn.state_changed state="IDLE"
- +26s transcript.replay turnState="IDLE" round=1 transcriptLength=10
- +26s transcript.accepted turnState="IDLE" round=1 transcriptLength=10
- +26s ws.send type="session_state" state="LOADING"
- +26s turn.state_changed state="LOADING"
- +26s ws.send type="session_state" state="PROCESSING"
- +26s turn.state_changed state="PROCESSING"
- +28s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +28s tool.client_result tool="companionAct"
- +32s transcript.queued turnState="PROCESSING" round=2 transcriptLength=8
- +34s transcript.queued turnState="PROCESSING" round=2 transcriptLength=5
- +36s ws.send type="session_state" state="SPEAKING"
- +36s turn.state_changed state="SPEAKING"
- +36s ws.send type="session_state" state="IDLE"
- +36s turn.state_changed state="IDLE"
- +36s transcript.replay turnState="IDLE" round=2 transcriptLength=5
- +36s transcript.accepted turnState="IDLE" round=2 transcriptLength=5
- +36s ws.send type="session_state" state="LOADING"
- +36s turn.state_changed state="LOADING"
- +36s ws.send type="session_state" state="PROCESSING"
- +36s turn.state_changed state="PROCESSING"
- +36s transcript.queued turnState="PROCESSING" round=3 transcriptLength=9
- +37s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +37s tool.client_result tool="companionAct"
- +38s transcript.queued turnState="PROCESSING" round=3 transcriptLength=7
- +39s ws.send type="session_state" state="SPEAKING"
- +39s turn.state_changed state="SPEAKING"
- +39s ws.send type="session_state" state="IDLE"
- +39s turn.state_changed state="IDLE"
- +39s transcript.replay turnState="IDLE" round=3 transcriptLength=7
- +39s transcript.accepted turnState="IDLE" round=3 transcriptLength=7
- +39s ws.send type="session_state" state="LOADING"
- +39s turn.state_changed state="LOADING"
- +40s ws.send type="session_state" state="PROCESSING"
- +40s turn.state_changed state="PROCESSING"
- +40s transcript.queued turnState="PROCESSING" round=4 transcriptLength=6
- +41s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +41s tool.client_result tool="companionAct"
- +43s ws.send type="session_state" state="SPEAKING"
- +43s turn.state_changed state="SPEAKING"
- +43s ws.send type="session_state" state="IDLE"
- +43s turn.state_changed state="IDLE"
- +43s transcript.replay turnState="IDLE" round=4 transcriptLength=6
- +43s transcript.accepted turnState="IDLE" round=4 transcriptLength=6
- +43s ws.send type="session_state" state="LOADING"
- +43s turn.state_changed state="LOADING"
- +43s ws.send type="session_state" state="PROCESSING"
- +43s turn.state_changed state="PROCESSING"
- +45s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +45s tool.client_result tool="companionAct"
- +46s ws.send type="session_state" state="SPEAKING"
- +46s turn.state_changed state="SPEAKING"
- +46s ws.send type="session_state" state="IDLE"
- +46s turn.state_changed state="IDLE"
- +56s transcript.accepted turnState="IDLE" round=5 transcriptLength=7
- +56s ws.send type="session_state" state="LOADING"
- +56s turn.state_changed state="LOADING"
- +56s ws.send type="session_state" state="PROCESSING"
- +56s turn.state_changed state="PROCESSING"
- +57s transcript.queued turnState="PROCESSING" round=6 transcriptLength=6
- +57s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +57s tool.client_result tool="companionAct"
- +59s ws.send type="session_state" state="SPEAKING"
- +59s turn.state_changed state="SPEAKING"
- +59s ws.send type="session_state" state="IDLE"
- +59s turn.state_changed state="IDLE"
- +59s transcript.replay turnState="IDLE" round=6 transcriptLength=6
- +59s transcript.accepted turnState="IDLE" round=6 transcriptLength=6
- +59s ws.send type="session_state" state="LOADING"
- +59s turn.state_changed state="LOADING"
- +59s ws.send type="session_state" state="PROCESSING"
- +59s turn.state_changed state="PROCESSING"
- +61s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +61s tool.client_result tool="companionAct"
- +63s ws.send type="session_state" state="SPEAKING"
- +63s turn.state_changed state="SPEAKING"
- +63s ws.send type="session_state" state="IDLE"
- +63s turn.state_changed state="IDLE"
- +73s session.ending turnState="IDLE" roundNumber=7 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=14

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 7,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "7a09355e-b9d8-43ba-9095-76282ccab935",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 14
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 14,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
