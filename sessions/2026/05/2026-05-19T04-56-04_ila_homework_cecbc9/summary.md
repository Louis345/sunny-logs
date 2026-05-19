# Sunny Session Debug Summary

sessionId: cecbc9f3-8202-4018-83ab-3733b2551e98
date: 2026-05-19T04:56:04.433Z
endedAt: 2026-05-19T04:57:40.086Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 95653
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
- +72s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +72s transcript.queued turnState="PROCESSING" round=9 transcriptLength=16
- +73s ws.send type="session_state" state="SPEAKING"
- +73s turn.state_changed state="SPEAKING"
- +73s ws.send type="session_state" state="IDLE"
- +73s turn.state_changed state="IDLE"
- +73s transcript.replay turnState="IDLE" round=9 transcriptLength=16
- +73s transcript.accepted turnState="IDLE" round=9 transcriptLength=16
- +73s ws.send type="session_state" state="LOADING"
- +73s turn.state_changed state="LOADING"
- +73s ws.send type="session_state" state="PROCESSING"
- +73s turn.state_changed state="PROCESSING"
- +73s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +75s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +76s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +76s tool.client_result tool="companionAct"
- +77s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +77s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +77s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +77s tool.client_result tool="companionAct"
- +78s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +78s ws.send type="session_state" state="SPEAKING"
- +78s turn.state_changed state="SPEAKING"
- +78s ws.send type="session_state" state="IDLE"
- +78s turn.state_changed state="IDLE"
- +78s transcript.replay turnState="IDLE" round=10 transcriptLength=16
- +78s transcript.accepted turnState="IDLE" round=10 transcriptLength=16
- +78s ws.send type="session_state" state="LOADING"
- +78s turn.state_changed state="LOADING"
- +78s ws.send type="session_state" state="PROCESSING"
- +78s turn.state_changed state="PROCESSING"
- +79s transcript.queued turnState="PROCESSING" round=11 transcriptLength=16
- +80s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +81s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +81s tool.client_result tool="companionAct"
- +82s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +82s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +83s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +83s tool.client_result tool="companionAct"
- +83s transcript.queued turnState="PROCESSING" round=11 transcriptLength=16
- +84s ws.send type="session_state" state="SPEAKING"
- +84s turn.state_changed state="SPEAKING"
- +84s ws.send type="session_state" state="IDLE"
- +84s turn.state_changed state="IDLE"
- +84s transcript.replay turnState="IDLE" round=11 transcriptLength=16
- +84s transcript.accepted turnState="IDLE" round=11 transcriptLength=16
- +84s ws.send type="session_state" state="LOADING"
- +84s turn.state_changed state="LOADING"
- +84s ws.send type="session_state" state="PROCESSING"
- +84s turn.state_changed state="PROCESSING"
- +84s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +86s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +86s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +86s tool.client_result tool="companionAct"
- +87s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +87s transcript.queued turnState="PROCESSING" round=12 transcriptLength=16
- +88s ws.send type="session_state" state="SPEAKING"
- +88s turn.state_changed state="SPEAKING"
- +88s ws.send type="session_state" state="IDLE"
- +88s turn.state_changed state="IDLE"
- +88s transcript.replay turnState="IDLE" round=12 transcriptLength=16
- +88s transcript.accepted turnState="IDLE" round=12 transcriptLength=16
- +88s ws.send type="session_state" state="LOADING"
- +88s turn.state_changed state="LOADING"
- +88s ws.send type="session_state" state="PROCESSING"
- +88s turn.state_changed state="PROCESSING"
- +89s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +90s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +91s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +91s tool.client_result tool="companionAct"
- +91s transcript.queued turnState="PROCESSING" round=13 transcriptLength=16
- +92s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +93s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +93s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +93s tool.client_result tool="companionAct"
- +93s session.ending turnState="PROCESSING" roundNumber=13 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=16 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=40
- +93s ws.send type="session_state" state="IDLE"
- +93s turn.state_changed state="IDLE"
- +93s engine.session_finalized totalAttempts=13 accuracy=1
- +93s engine.progression_computed level=20 totalXP=1925 wordsMastered=4

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 13,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "cecbc9f3-8202-4018-83ab-3733b2551e98",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 42
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 42,
  "rewardLogEntries": 3
}
```

## Upload
Session saved locally. Upload not configured yet.
