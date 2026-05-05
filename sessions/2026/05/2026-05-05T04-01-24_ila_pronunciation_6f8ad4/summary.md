# Sunny Session Debug Summary

sessionId: 6f8ad4a6-73f7-4e49-bab4-f6c12c0a206d
date: 2026-05-05T04:01:24.457Z
endedAt: 2026-05-05T04:03:18.678Z
child: Ila
subject: pronunciation
mode: as-child
gitCommit: 8f8e5f8
command: npm run npx
duration_ms: 114221
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: as-child
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: pronunciation
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +86s transcript.replay turnState="IDLE" round=5 transcriptLength=9
- +86s transcript.accepted turnState="IDLE" round=5 transcriptLength=9
- +86s ws.send type="session_state" state="LOADING"
- +86s turn.state_changed state="LOADING"
- +86s ws.send type="session_state" state="PROCESSING"
- +86s turn.state_changed state="PROCESSING"
- +86s transcript.queued turnState="PROCESSING" round=6 transcriptLength=7
- +87s transcript.queued turnState="PROCESSING" round=6 transcriptLength=7
- +88s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +88s tool.client_result tool="companionAct"
- +89s transcript.queued turnState="PROCESSING" round=6 transcriptLength=6
- +90s ws.send type="session_state" state="SPEAKING"
- +90s turn.state_changed state="SPEAKING"
- +90s ws.send type="session_state" state="IDLE"
- +90s turn.state_changed state="IDLE"
- +90s transcript.replay turnState="IDLE" round=6 transcriptLength=6
- +90s transcript.accepted turnState="IDLE" round=6 transcriptLength=6
- +90s ws.send type="session_state" state="LOADING"
- +90s turn.state_changed state="LOADING"
- +90s ws.send type="session_state" state="PROCESSING"
- +90s turn.state_changed state="PROCESSING"
- +90s transcript.queued turnState="PROCESSING" round=7 transcriptLength=4
- +91s transcript.duplicate_suppressed turnState="PROCESSING" round=7 transcriptLength=4
- +92s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +92s tool.client_result tool="companionAct"
- +92s transcript.queued turnState="PROCESSING" round=7 transcriptLength=7
- +94s ws.send type="session_state" state="SPEAKING"
- +94s turn.state_changed state="SPEAKING"
- +94s ws.send type="session_state" state="IDLE"
- +94s turn.state_changed state="IDLE"
- +94s transcript.replay turnState="IDLE" round=7 transcriptLength=7
- +94s transcript.accepted turnState="IDLE" round=7 transcriptLength=7
- +94s ws.send type="session_state" state="LOADING"
- +94s turn.state_changed state="LOADING"
- +94s ws.send type="session_state" state="PROCESSING"
- +94s turn.state_changed state="PROCESSING"
- +96s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +96s tool.client_result tool="companionAct"
- +96s transcript.queued turnState="PROCESSING" round=8 transcriptLength=20
- +98s ws.send type="session_state" state="SPEAKING"
- +98s turn.state_changed state="SPEAKING"
- +98s ws.send type="session_state" state="IDLE"
- +98s turn.state_changed state="IDLE"
- +98s transcript.replay turnState="IDLE" round=8 transcriptLength=20
- +98s transcript.accepted turnState="IDLE" round=8 transcriptLength=20
- +98s ws.send type="session_state" state="LOADING"
- +98s turn.state_changed state="LOADING"
- +98s ws.send type="session_state" state="PROCESSING"
- +98s turn.state_changed state="PROCESSING"
- +99s transcript.queued turnState="PROCESSING" round=9 transcriptLength=11
- +100s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +100s tool.client_result tool="companionAct"
- +102s ws.send type="session_state" state="SPEAKING"
- +102s turn.state_changed state="SPEAKING"
- +102s ws.send type="session_state" state="IDLE"
- +102s turn.state_changed state="IDLE"
- +102s transcript.replay turnState="IDLE" round=9 transcriptLength=11
- +102s transcript.accepted turnState="IDLE" round=9 transcriptLength=11
- +102s ws.send type="session_state" state="LOADING"
- +102s turn.state_changed state="LOADING"
- +102s ws.send type="session_state" state="PROCESSING"
- +102s turn.state_changed state="PROCESSING"
- +104s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +104s tool.client_result tool="companionAct"
- +106s ws.send type="session_state" state="SPEAKING"
- +106s turn.state_changed state="SPEAKING"
- +106s ws.send type="session_state" state="IDLE"
- +106s turn.state_changed state="IDLE"
- +110s transcript.accepted turnState="IDLE" round=10 transcriptLength=39
- +110s ws.send type="session_state" state="LOADING"
- +110s turn.state_changed state="LOADING"
- +110s ws.send type="session_state" state="PROCESSING"
- +110s turn.state_changed state="PROCESSING"
- +111s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +111s tool.client_result tool="companionAct"
- +113s ws.send type="session_state" state="SPEAKING"
- +113s turn.state_changed state="SPEAKING"
- +113s ws.send type="session_state" state="IDLE"
- +113s turn.state_changed state="IDLE"
- +114s session.ending turnState="IDLE" roundNumber=11 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=22

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 11,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "6f8ad4a6-73f7-4e49-bab4-f6c12c0a206d",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 22
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 22,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
