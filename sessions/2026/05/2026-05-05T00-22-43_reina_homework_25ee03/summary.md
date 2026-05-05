# Sunny Session Debug Summary

sessionId: 25ee03ef-44f4-4535-ad68-ae00b81c14bd
date: 2026-05-05T00:22:43.690Z
endedAt: 2026-05-05T00:26:05.689Z
child: Reina
subject: homework
mode: real
gitCommit: 8f8e5f8
command: npm run npx
duration_ms: 201999
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +54s ws.send type="session_state" state="SPEAKING"
- +54s turn.state_changed state="SPEAKING"
- +63s ws.send type="session_state" state="IDLE"
- +63s turn.state_changed state="IDLE"
- +63s transcript.accepted turnState="IDLE" round=1 transcriptLength=34
- +63s ws.send type="session_state" state="LOADING"
- +63s turn.state_changed state="LOADING"
- +63s ws.send type="session_state" state="PROCESSING"
- +63s turn.state_changed state="PROCESSING"
- +65s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +65s tool.client_result tool="companionAct"
- +65s transcript.queued turnState="PROCESSING" round=2 transcriptLength=42
- +68s ws.send type="session_state" state="SPEAKING"
- +68s turn.state_changed state="SPEAKING"
- +72s tool.client_result tool="canvasShow"
- +72s canvas.draw mode="pronunciation" canvasRevision=1
- +72s ws.send type="session_state" state="IDLE"
- +72s turn.state_changed state="IDLE"
- +72s transcript.replay turnState="IDLE" round=2 transcriptLength=42
- +72s transcript.accepted turnState="IDLE" round=2 transcriptLength=42
- +72s ws.send type="session_state" state="LOADING"
- +72s turn.state_changed state="LOADING"
- +72s ws.send type="session_state" state="PROCESSING"
- +72s turn.state_changed state="PROCESSING"
- +72s transcript.queued turnState="PROCESSING" round=3 transcriptLength=15
- +74s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +74s tool.client_result tool="companionAct"
- +76s ws.send type="session_state" state="SPEAKING"
- +76s turn.state_changed state="SPEAKING"
- +78s ws.send type="session_state" state="IDLE"
- +78s turn.state_changed state="IDLE"
- +78s transcript.replay turnState="IDLE" round=3 transcriptLength=15
- +78s transcript.accepted turnState="IDLE" round=3 transcriptLength=15
- +78s ws.send type="session_state" state="LOADING"
- +78s turn.state_changed state="LOADING"
- +78s ws.send type="session_state" state="PROCESSING"
- +78s turn.state_changed state="PROCESSING"
- +80s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +80s tool.client_result tool="companionAct"
- +82s ws.send type="session_state" state="SPEAKING"
- +82s turn.state_changed state="SPEAKING"
- +84s ws.send type="session_state" state="IDLE"
- +84s turn.state_changed state="IDLE"
- +106s transcript.accepted turnState="IDLE" round=4 transcriptLength=363
- +106s ws.send type="session_state" state="LOADING"
- +106s turn.state_changed state="LOADING"
- +106s ws.send type="session_state" state="PROCESSING"
- +106s turn.state_changed state="PROCESSING"
- +108s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +108s tool.client_result tool="companionAct"
- +111s ws.send type="session_state" state="SPEAKING"
- +111s turn.state_changed state="SPEAKING"
- +112s ws.send type="session_state" state="IDLE"
- +112s turn.state_changed state="IDLE"
- +117s transcript.accepted turnState="IDLE" round=5 transcriptLength=440
- +117s ws.send type="session_state" state="LOADING"
- +117s turn.state_changed state="LOADING"
- +117s ws.send type="session_state" state="PROCESSING"
- +117s turn.state_changed state="PROCESSING"
- +119s tool.called tool="sessionLog" argsKeys=["skipped","reason","activity"] hasResult=true
- +119s tool.client_result tool="sessionLog"
- +122s ws.send type="session_state" state="SPEAKING"
- +122s turn.state_changed state="SPEAKING"
- +123s ws.send type="session_state" state="IDLE"
- +123s turn.state_changed state="IDLE"
- +133s transcript.accepted turnState="IDLE" round=6 transcriptLength=223
- +133s ws.send type="session_state" state="LOADING"
- +133s turn.state_changed state="LOADING"
- +133s ws.send type="session_state" state="PROCESSING"
- +133s turn.state_changed state="PROCESSING"
- +135s transcript.queued turnState="PROCESSING" round=7 transcriptLength=220
- +136s tool.called tool="sessionLog" argsKeys=["skipped","reason","activity"] hasResult=true
- +136s tool.client_result tool="sessionLog"
- +140s ws.send type="session_state" state="SPEAKING"
- +140s turn.state_changed state="SPEAKING"
- +153s session.ending turnState="SPEAKING" roundNumber=7 isEnding=true childName="Reina" canvasMode="pronunciation" activeGame=null pendingTranscript=true pendingTranscriptLength=220 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=15
- +153s ws.send type="session_state" state="IDLE"
- +153s turn.state_changed state="IDLE"
- +153s engine.session_finalized totalAttempts=0 accuracy=0
- +153s engine.progression_computed level=71 totalXP=7035 wordsMastered=26

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 7,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "25ee03ef-44f4-4535-ad68-ae00b81c14bd",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 15
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 15,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
