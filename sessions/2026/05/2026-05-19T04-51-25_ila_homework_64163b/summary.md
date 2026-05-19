# Sunny Session Debug Summary

sessionId: 64163b79-425c-4fcc-aab3-0bee23ae488e
date: 2026-05-19T04:51:25.908Z
endedAt: 2026-05-19T04:53:00.631Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 94723
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: real
- SUNNY_CHILD: demo_adaptive
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +68s transcript.duplicate_suppressed turnState="PROCESSING" round=6 transcriptLength=16
- +70s transcript.duplicate_suppressed turnState="PROCESSING" round=6 transcriptLength=16
- +70s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +70s tool.client_result tool="companionAct"
- +71s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +71s transcript.queued turnState="PROCESSING" round=6 transcriptLength=16
- +72s ws.send type="session_state" state="SPEAKING"
- +72s turn.state_changed state="SPEAKING"
- +72s ws.send type="session_state" state="IDLE"
- +72s turn.state_changed state="IDLE"
- +72s transcript.replay turnState="IDLE" round=6 transcriptLength=16
- +72s transcript.accepted turnState="IDLE" round=6 transcriptLength=16
- +72s ws.send type="session_state" state="LOADING"
- +72s turn.state_changed state="LOADING"
- +72s ws.send type="session_state" state="PROCESSING"
- +72s turn.state_changed state="PROCESSING"
- +72s transcript.duplicate_suppressed turnState="PROCESSING" round=7 transcriptLength=16
- +73s transcript.duplicate_suppressed turnState="PROCESSING" round=7 transcriptLength=16
- +75s transcript.queued turnState="PROCESSING" round=7 transcriptLength=16
- +75s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +75s tool.client_result tool="companionAct"
- +76s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +76s transcript.duplicate_suppressed turnState="PROCESSING" round=7 transcriptLength=16
- +77s transcript.duplicate_suppressed turnState="PROCESSING" round=7 transcriptLength=16
- +78s ws.send type="session_state" state="SPEAKING"
- +78s turn.state_changed state="SPEAKING"
- +78s ws.send type="session_state" state="IDLE"
- +78s turn.state_changed state="IDLE"
- +78s transcript.replay turnState="IDLE" round=7 transcriptLength=16
- +78s transcript.accepted turnState="IDLE" round=7 transcriptLength=16
- +78s ws.send type="session_state" state="LOADING"
- +78s turn.state_changed state="LOADING"
- +78s ws.send type="session_state" state="PROCESSING"
- +78s turn.state_changed state="PROCESSING"
- +79s transcript.queued turnState="PROCESSING" round=8 transcriptLength=16
- +80s transcript.duplicate_suppressed turnState="PROCESSING" round=8 transcriptLength=16
- +81s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +81s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +81s tool.client_result tool="companionAct"
- +81s transcript.duplicate_suppressed turnState="PROCESSING" round=8 transcriptLength=16
- +83s transcript.queued turnState="PROCESSING" round=8 transcriptLength=16
- +83s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +83s tool.client_result tool="companionAct"
- +84s ws.send type="session_state" state="SPEAKING"
- +84s turn.state_changed state="SPEAKING"
- +84s transcript.duplicate_suppressed turnState="SPEAKING" round=8 transcriptLength=16
- +84s ws.send type="session_state" state="IDLE"
- +84s turn.state_changed state="IDLE"
- +84s transcript.replay turnState="IDLE" round=8 transcriptLength=16
- +84s transcript.accepted turnState="IDLE" round=8 transcriptLength=16
- +84s ws.send type="session_state" state="LOADING"
- +84s turn.state_changed state="LOADING"
- +84s ws.send type="session_state" state="PROCESSING"
- +84s turn.state_changed state="PROCESSING"
- +85s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +86s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +87s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +87s tool.client_result tool="companionAct"
- +87s transcript.queued turnState="PROCESSING" round=9 transcriptLength=16
- +88s ws.send type="session_state" state="SPEAKING"
- +88s turn.state_changed state="SPEAKING"
- +88s ws.send type="session_state" state="IDLE"
- +88s turn.state_changed state="IDLE"
- +88s transcript.replay turnState="IDLE" round=9 transcriptLength=16
- +88s transcript.accepted turnState="IDLE" round=9 transcriptLength=16
- +88s ws.send type="session_state" state="LOADING"
- +88s turn.state_changed state="LOADING"
- +88s ws.send type="session_state" state="PROCESSING"
- +88s turn.state_changed state="PROCESSING"
- +88s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +89s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +91s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +91s tool.client_result tool="companionAct"
- +91s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +91s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +91s session.ending turnState="PROCESSING" roundNumber=10 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=16 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=34
- +91s ws.send type="session_state" state="IDLE"
- +91s turn.state_changed state="IDLE"
- +91s engine.session_finalized totalAttempts=11 accuracy=1
- +91s engine.progression_computed level=16 totalXP=1540 wordsMastered=4

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 10,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "64163b79-425c-4fcc-aab3-0bee23ae488e",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 36
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 36,
  "rewardLogEntries": 1
}
```

## Upload
Session saved locally. Upload not configured yet.
