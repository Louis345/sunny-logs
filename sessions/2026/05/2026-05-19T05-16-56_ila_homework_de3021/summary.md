# Sunny Session Debug Summary

sessionId: de30216a-eaa4-4824-9244-b22c7190b9be
date: 2026-05-19T05:16:56.821Z
endedAt: 2026-05-19T05:18:37.710Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 100889
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
- +70s tool.client_result tool="companionAct"
- +71s transcript.queued turnState="PROCESSING" round=9 transcriptLength=16
- +72s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +73s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +73s tool.client_result tool="companionAct"
- +74s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +75s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +75s transcript.queued turnState="PROCESSING" round=9 transcriptLength=16
- +76s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +77s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +78s ws.send type="session_state" state="SPEAKING"
- +78s turn.state_changed state="SPEAKING"
- +78s ws.send type="session_state" state="IDLE"
- +78s turn.state_changed state="IDLE"
- +78s transcript.replay turnState="IDLE" round=9 transcriptLength=16
- +78s transcript.accepted turnState="IDLE" round=9 transcriptLength=16
- +78s ws.send type="session_state" state="LOADING"
- +78s turn.state_changed state="LOADING"
- +78s ws.send type="session_state" state="PROCESSING"
- +78s turn.state_changed state="PROCESSING"
- +79s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +80s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +80s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +81s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +81s tool.client_result tool="companionAct"
- +82s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +83s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +83s tool.client_result tool="companionAct"
- +83s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +84s ws.send type="session_state" state="SPEAKING"
- +84s turn.state_changed state="SPEAKING"
- +84s ws.send type="session_state" state="IDLE"
- +84s turn.state_changed state="IDLE"
- +84s transcript.replay turnState="IDLE" round=10 transcriptLength=16
- +84s transcript.accepted turnState="IDLE" round=10 transcriptLength=16
- +84s ws.send type="session_state" state="LOADING"
- +84s turn.state_changed state="LOADING"
- +84s ws.send type="session_state" state="PROCESSING"
- +84s turn.state_changed state="PROCESSING"
- +85s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +85s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +86s ws.send type="session_state" state="SPEAKING"
- +86s turn.state_changed state="SPEAKING"
- +86s ws.send type="session_state" state="IDLE"
- +86s turn.state_changed state="IDLE"
- +86s transcript.accepted turnState="IDLE" round=11 transcriptLength=16
- +86s ws.send type="session_state" state="LOADING"
- +86s turn.state_changed state="LOADING"
- +86s ws.send type="session_state" state="PROCESSING"
- +86s turn.state_changed state="PROCESSING"
- +87s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +88s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +88s tool.client_result tool="companionAct"
- +89s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +90s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +90s transcript.queued turnState="PROCESSING" round=12 transcriptLength=16
- +90s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +90s tool.client_result tool="companionAct"
- +91s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +92s ws.send type="session_state" state="SPEAKING"
- +92s turn.state_changed state="SPEAKING"
- +92s ws.send type="session_state" state="IDLE"
- +92s turn.state_changed state="IDLE"
- +92s transcript.replay turnState="IDLE" round=12 transcriptLength=16
- +92s transcript.accepted turnState="IDLE" round=12 transcriptLength=16
- +92s ws.send type="session_state" state="LOADING"
- +92s turn.state_changed state="LOADING"
- +92s ws.send type="session_state" state="PROCESSING"
- +92s turn.state_changed state="PROCESSING"
- +93s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +94s transcript.queued turnState="PROCESSING" round=13 transcriptLength=16
- +94s session.ending turnState="PROCESSING" roundNumber=13 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=16 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=42
- +94s ws.send type="session_state" state="IDLE"
- +94s turn.state_changed state="IDLE"
- +94s engine.session_finalized totalAttempts=15 accuracy=1
- +94s engine.progression_computed level=6 totalXP=575 wordsMastered=6
- +96s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +96s tool.client_result tool="companionAct"
- +98s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +98s tool.client_result tool="companionAct"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 13,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "de30216a-eaa4-4824-9244-b22c7190b9be",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 44
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 44,
  "rewardLogEntries": 3
}
```

## Upload
Session saved locally. Upload not configured yet.
