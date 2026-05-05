# Sunny Session Debug Summary

sessionId: f677a613-0205-4f7f-b7dc-3948301e7fbe
date: 2026-05-05T03:39:29.850Z
endedAt: 2026-05-05T03:40:52.429Z
child: Ila
subject: pronunciation
mode: as-child
gitCommit: 8f8e5f8
command: npm run npx
duration_ms: 82579
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: as-child
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: pronunciation
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +59s ws.send type="session_state" state="LOADING"
- +59s turn.state_changed state="LOADING"
- +59s ws.send type="session_state" state="PROCESSING"
- +59s turn.state_changed state="PROCESSING"
- +61s transcript.queued turnState="PROCESSING" round=10 transcriptLength=6
- +61s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +61s tool.client_result tool="companionAct"
- +63s ws.send type="session_state" state="SPEAKING"
- +63s turn.state_changed state="SPEAKING"
- +63s ws.send type="session_state" state="IDLE"
- +63s turn.state_changed state="IDLE"
- +63s transcript.replay turnState="IDLE" round=10 transcriptLength=6
- +63s transcript.accepted turnState="IDLE" round=10 transcriptLength=6
- +63s ws.send type="session_state" state="LOADING"
- +63s turn.state_changed state="LOADING"
- +63s ws.send type="session_state" state="PROCESSING"
- +63s turn.state_changed state="PROCESSING"
- +63s transcript.queued turnState="PROCESSING" round=11 transcriptLength=9
- +65s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +65s tool.client_result tool="companionAct"
- +65s transcript.queued turnState="PROCESSING" round=11 transcriptLength=4
- +66s ws.send type="session_state" state="SPEAKING"
- +66s turn.state_changed state="SPEAKING"
- +66s ws.send type="session_state" state="IDLE"
- +66s turn.state_changed state="IDLE"
- +66s transcript.replay turnState="IDLE" round=11 transcriptLength=4
- +66s transcript.accepted turnState="IDLE" round=11 transcriptLength=4
- +66s ws.send type="session_state" state="LOADING"
- +66s turn.state_changed state="LOADING"
- +66s ws.send type="session_state" state="PROCESSING"
- +66s turn.state_changed state="PROCESSING"
- +68s transcript.queued turnState="PROCESSING" round=12 transcriptLength=5
- +69s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +69s tool.client_result tool="companionAct"
- +69s transcript.queued turnState="PROCESSING" round=12 transcriptLength=3
- +70s ws.send type="session_state" state="SPEAKING"
- +70s turn.state_changed state="SPEAKING"
- +70s ws.send type="session_state" state="IDLE"
- +70s turn.state_changed state="IDLE"
- +70s transcript.replay turnState="IDLE" round=12 transcriptLength=3
- +70s transcript.accepted turnState="IDLE" round=12 transcriptLength=3
- +70s ws.send type="session_state" state="LOADING"
- +70s turn.state_changed state="LOADING"
- +70s ws.send type="session_state" state="PROCESSING"
- +70s turn.state_changed state="PROCESSING"
- +71s transcript.queued turnState="PROCESSING" round=13 transcriptLength=7
- +71s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +71s tool.client_result tool="companionAct"
- +73s transcript.queued turnState="PROCESSING" round=13 transcriptLength=5
- +74s ws.send type="session_state" state="SPEAKING"
- +74s turn.state_changed state="SPEAKING"
- +74s ws.send type="session_state" state="IDLE"
- +74s turn.state_changed state="IDLE"
- +74s transcript.replay turnState="IDLE" round=13 transcriptLength=5
- +74s transcript.accepted turnState="IDLE" round=13 transcriptLength=5
- +74s ws.send type="session_state" state="LOADING"
- +74s turn.state_changed state="LOADING"
- +74s ws.send type="session_state" state="PROCESSING"
- +74s turn.state_changed state="PROCESSING"
- +74s transcript.queued turnState="PROCESSING" round=14 transcriptLength=6
- +75s transcript.queued turnState="PROCESSING" round=14 transcriptLength=6
- +77s transcript.queued turnState="PROCESSING" round=14 transcriptLength=9
- +77s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +77s tool.client_result tool="companionAct"
- +79s ws.send type="session_state" state="SPEAKING"
- +79s turn.state_changed state="SPEAKING"
- +79s transcript.dropped reason="assistant_owns_turn" turnState="SPEAKING" round=14 transcriptLength=7
- +79s ws.send type="session_state" state="IDLE"
- +79s turn.state_changed state="IDLE"
- +79s transcript.replay turnState="IDLE" round=14 transcriptLength=9
- +79s transcript.accepted turnState="IDLE" round=14 transcriptLength=9
- +79s ws.send type="session_state" state="LOADING"
- +79s turn.state_changed state="LOADING"
- +79s ws.send type="session_state" state="PROCESSING"
- +79s turn.state_changed state="PROCESSING"
- +81s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +81s tool.client_result tool="companionAct"
- +83s session.ending turnState="PROCESSING" roundNumber=15 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=28
- +83s ws.send type="session_state" state="IDLE"
- +83s turn.state_changed state="IDLE"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 15,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "f677a613-0205-4f7f-b7dc-3948301e7fbe",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 28
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 28,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
