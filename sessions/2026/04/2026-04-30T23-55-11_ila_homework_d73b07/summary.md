# Sunny Session Debug Summary

sessionId: d73b07b0-f748-493a-b691-3c0912bb0fe8
date: 2026-04-30T23:55:11.384Z
endedAt: 2026-05-01T00:11:59.115Z
child: Ila
subject: homework
mode: default
gitCommit: 484e23a
command: npm run npx
duration_ms: 1007731
result: completed

## Env Flags
- TTS_ENABLED: 
- SUNNY_MODE: 
- SUNNY_CHILD: 
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: 
- SUNNY_STATELESS: 

## Timeline
- +678s turn.state_changed state="LOADING"
- +678s ws.send type="session_state" state="PROCESSING"
- +678s turn.state_changed state="PROCESSING"
- +681s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +681s tool.client_result tool="companionAct"
- +682s ws.send type="session_state" state="SPEAKING"
- +682s turn.state_changed state="SPEAKING"
- +686s ws.send type="session_state" state="IDLE"
- +686s turn.state_changed state="IDLE"
- +738s transcript.accepted turnState="IDLE" round=43 transcriptLength=56
- +738s ws.send type="session_state" state="LOADING"
- +738s turn.state_changed state="LOADING"
- +738s ws.send type="session_state" state="PROCESSING"
- +738s turn.state_changed state="PROCESSING"
- +740s tool.called tool="expressCompanion" argsKeys=["emote","intensity"] hasResult=true
- +740s tool.client_result tool="expressCompanion"
- +742s ws.send type="session_state" state="SPEAKING"
- +742s turn.state_changed state="SPEAKING"
- +746s ws.send type="session_state" state="IDLE"
- +746s turn.state_changed state="IDLE"
- +757s transcript.accepted turnState="IDLE" round=44 transcriptLength=140
- +757s ws.send type="session_state" state="LOADING"
- +757s turn.state_changed state="LOADING"
- +757s ws.send type="session_state" state="PROCESSING"
- +757s turn.state_changed state="PROCESSING"
- +759s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +759s tool.client_result tool="companionAct"
- +762s ws.send type="session_state" state="SPEAKING"
- +762s turn.state_changed state="SPEAKING"
- +770s ws.send type="session_state" state="IDLE"
- +770s turn.state_changed state="IDLE"
- +809s transcript.accepted turnState="IDLE" round=45 transcriptLength=16
- +809s ws.send type="session_state" state="LOADING"
- +809s turn.state_changed state="LOADING"
- +809s ws.send type="session_state" state="PROCESSING"
- +809s turn.state_changed state="PROCESSING"
- +813s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +813s tool.client_result tool="companionAct"
- +815s ws.send type="session_state" state="SPEAKING"
- +815s turn.state_changed state="SPEAKING"
- +821s ws.send type="session_state" state="IDLE"
- +821s turn.state_changed state="IDLE"
- +821s transcript.accepted turnState="IDLE" round=46 transcriptLength=88
- +821s ws.send type="session_state" state="LOADING"
- +821s turn.state_changed state="LOADING"
- +821s ws.send type="session_state" state="PROCESSING"
- +821s turn.state_changed state="PROCESSING"
- +823s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +823s tool.client_result tool="companionAct"
- +825s ws.send type="session_state" state="SPEAKING"
- +825s turn.state_changed state="SPEAKING"
- +832s ws.send type="session_state" state="IDLE"
- +832s turn.state_changed state="IDLE"
- +845s transcript.accepted turnState="IDLE" round=47 transcriptLength=25
- +845s ws.send type="session_state" state="LOADING"
- +845s turn.state_changed state="LOADING"
- +845s ws.send type="session_state" state="PROCESSING"
- +845s turn.state_changed state="PROCESSING"
- +848s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +848s tool.client_result tool="companionAct"
- +850s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +850s tool.client_result tool="sessionLog"
- +851s ws.send type="session_state" state="SPEAKING"
- +851s turn.state_changed state="SPEAKING"
- +856s ws.send type="session_state" state="IDLE"
- +856s turn.state_changed state="IDLE"
- +856s transcript.accepted turnState="IDLE" round=48 transcriptLength=45
- +856s ws.send type="session_state" state="LOADING"
- +856s turn.state_changed state="LOADING"
- +856s ws.send type="session_state" state="PROCESSING"
- +856s turn.state_changed state="PROCESSING"
- +858s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +858s tool.client_result tool="companionAct"
- +860s ws.send type="session_state" state="SPEAKING"
- +860s turn.state_changed state="SPEAKING"
- +869s ws.send type="session_state" state="IDLE"
- +869s turn.state_changed state="IDLE"
- +940s session.ending turnState="IDLE" roundNumber=49 isEnding=true childName="Ila" canvasMode="championship" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=583
- +940s engine.session_finalized totalAttempts=0 accuracy=0
- +940s engine.progression_computed level=44 totalXP=4370 wordsMastered=2

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 49,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "d73b07b0-f748-493a-b691-3c0912bb0fe8",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 611
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 611,
  "rewardLogEntries": 29
}
```

## Upload
Session saved locally. Upload not configured yet.
