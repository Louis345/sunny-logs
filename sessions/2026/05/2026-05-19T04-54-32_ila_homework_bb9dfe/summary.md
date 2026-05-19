# Sunny Session Debug Summary

sessionId: bb9dfef9-49d0-4565-9ee7-43f909a09f8f
date: 2026-05-19T04:54:32.529Z
endedAt: 2026-05-19T04:56:07.675Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 95146
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
- +70s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +70s tool.client_result tool="companionAct"
- +72s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +72s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +72s tool.client_result tool="companionAct"
- +73s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +73s ws.send type="session_state" state="SPEAKING"
- +73s turn.state_changed state="SPEAKING"
- +73s ws.send type="session_state" state="IDLE"
- +73s turn.state_changed state="IDLE"
- +73s transcript.replay turnState="IDLE" round=10 transcriptLength=16
- +73s transcript.accepted turnState="IDLE" round=10 transcriptLength=16
- +73s ws.send type="session_state" state="LOADING"
- +73s turn.state_changed state="LOADING"
- +73s ws.send type="session_state" state="PROCESSING"
- +73s turn.state_changed state="PROCESSING"
- +74s transcript.queued turnState="PROCESSING" round=11 transcriptLength=16
- +74s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +75s ws.send type="session_state" state="SPEAKING"
- +75s turn.state_changed state="SPEAKING"
- +75s ws.send type="session_state" state="IDLE"
- +75s turn.state_changed state="IDLE"
- +75s transcript.replay turnState="IDLE" round=11 transcriptLength=16
- +75s transcript.accepted turnState="IDLE" round=11 transcriptLength=16
- +75s ws.send type="session_state" state="LOADING"
- +75s turn.state_changed state="LOADING"
- +75s ws.send type="session_state" state="PROCESSING"
- +75s turn.state_changed state="PROCESSING"
- +76s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +77s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +78s transcript.queued turnState="PROCESSING" round=12 transcriptLength=16
- +79s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +79s tool.client_result tool="companionAct"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +80s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +81s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +81s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +81s tool.client_result tool="companionAct"
- +82s ws.send type="session_state" state="SPEAKING"
- +82s turn.state_changed state="SPEAKING"
- +82s ws.send type="session_state" state="IDLE"
- +82s turn.state_changed state="IDLE"
- +82s transcript.replay turnState="IDLE" round=12 transcriptLength=16
- +82s transcript.accepted turnState="IDLE" round=12 transcriptLength=16
- +82s ws.send type="session_state" state="LOADING"
- +82s turn.state_changed state="LOADING"
- +82s ws.send type="session_state" state="PROCESSING"
- +82s turn.state_changed state="PROCESSING"
- +82s transcript.queued turnState="PROCESSING" round=13 transcriptLength=16
- +84s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +84s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +85s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +85s tool.client_result tool="companionAct"
- +85s transcript.queued turnState="PROCESSING" round=13 transcriptLength=16
- +86s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +86s tool.client_result tool="companionAct"
- +87s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +87s ws.send type="session_state" state="SPEAKING"
- +87s turn.state_changed state="SPEAKING"
- +87s ws.send type="session_state" state="IDLE"
- +87s turn.state_changed state="IDLE"
- +87s transcript.replay turnState="IDLE" round=13 transcriptLength=16
- +87s transcript.accepted turnState="IDLE" round=13 transcriptLength=16
- +87s ws.send type="session_state" state="LOADING"
- +87s turn.state_changed state="LOADING"
- +87s ws.send type="session_state" state="PROCESSING"
- +87s turn.state_changed state="PROCESSING"
- +88s transcript.duplicate_suppressed turnState="PROCESSING" round=14 transcriptLength=16
- +89s transcript.queued turnState="PROCESSING" round=14 transcriptLength=16
- +89s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +90s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +90s tool.client_result tool="companionAct"
- +90s transcript.duplicate_suppressed turnState="PROCESSING" round=14 transcriptLength=16
- +91s session.ending turnState="PROCESSING" roundNumber=14 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=16 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=42
- +91s ws.send type="session_state" state="IDLE"
- +91s turn.state_changed state="IDLE"
- +91s engine.session_finalized totalAttempts=12 accuracy=1
- +91s engine.progression_computed level=18 totalXP=1790 wordsMastered=4
- +92s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +92s tool.client_result tool="takeGameScreenshot"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 14,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "bb9dfef9-49d0-4565-9ee7-43f909a09f8f",
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
  "rewardLogEntries": 2
}
```

## Upload
Session saved locally. Upload not configured yet.
