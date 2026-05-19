# Sunny Session Debug Summary

sessionId: 2dfef9a6-a06f-44a3-996e-75a2b7b1f4ac
date: 2026-05-19T04:49:51.672Z
endedAt: 2026-05-19T04:51:29.917Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 98245
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
- +69s ws.send type="session_state" state="IDLE"
- +69s turn.state_changed state="IDLE"
- +69s transcript.replay turnState="IDLE" round=9 transcriptLength=16
- +69s transcript.accepted turnState="IDLE" round=9 transcriptLength=16
- +69s ws.send type="session_state" state="LOADING"
- +69s turn.state_changed state="LOADING"
- +69s ws.send type="session_state" state="PROCESSING"
- +69s turn.state_changed state="PROCESSING"
- +70s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +71s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +71s tool.client_result tool="companionAct"
- +71s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +74s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +75s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +75s tool.client_result tool="takeGameScreenshot"
- +75s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +76s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +77s ws.send type="session_state" state="SPEAKING"
- +77s turn.state_changed state="SPEAKING"
- +77s ws.send type="session_state" state="IDLE"
- +77s turn.state_changed state="IDLE"
- +77s transcript.replay turnState="IDLE" round=10 transcriptLength=16
- +77s transcript.accepted turnState="IDLE" round=10 transcriptLength=16
- +77s ws.send type="session_state" state="LOADING"
- +77s turn.state_changed state="LOADING"
- +77s ws.send type="session_state" state="PROCESSING"
- +77s turn.state_changed state="PROCESSING"
- +78s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +78s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +79s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +80s transcript.queued turnState="PROCESSING" round=11 transcriptLength=16
- +80s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word","observation"] hasResult=true
- +80s tool.client_result tool="sessionLog"
- +81s ws.send type="session_state" state="SPEAKING"
- +81s turn.state_changed state="SPEAKING"
- +81s ws.send type="session_state" state="IDLE"
- +81s turn.state_changed state="IDLE"
- +81s transcript.replay turnState="IDLE" round=11 transcriptLength=16
- +81s transcript.accepted turnState="IDLE" round=11 transcriptLength=16
- +81s ws.send type="session_state" state="LOADING"
- +81s turn.state_changed state="LOADING"
- +81s ws.send type="session_state" state="PROCESSING"
- +81s turn.state_changed state="PROCESSING"
- +82s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +83s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +83s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +83s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +83s tool.client_result tool="companionAct"
- +84s transcript.queued turnState="PROCESSING" round=12 transcriptLength=16
- +85s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +86s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +86s tool.client_result tool="takeGameScreenshot"
- +87s transcript.queued turnState="PROCESSING" round=12 transcriptLength=16
- +87s ws.send type="session_state" state="SPEAKING"
- +87s turn.state_changed state="SPEAKING"
- +88s ws.send type="session_state" state="IDLE"
- +88s turn.state_changed state="IDLE"
- +88s transcript.replay turnState="IDLE" round=12 transcriptLength=16
- +88s transcript.accepted turnState="IDLE" round=12 transcriptLength=16
- +88s ws.send type="session_state" state="LOADING"
- +88s turn.state_changed state="LOADING"
- +88s ws.send type="session_state" state="PROCESSING"
- +88s turn.state_changed state="PROCESSING"
- +88s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +89s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +90s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +90s tool.client_result tool="companionAct"
- +90s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +92s transcript.queued turnState="PROCESSING" round=13 transcriptLength=16
- +92s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +92s tool.client_result tool="takeGameScreenshot"
- +93s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +93s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +93s session.ending turnState="PROCESSING" roundNumber=13 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=16 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=40
- +93s ws.send type="session_state" state="IDLE"
- +93s turn.state_changed state="IDLE"
- +93s engine.session_finalized totalAttempts=16 accuracy=0.8125
- +93s engine.progression_computed level=15 totalXP=1425 wordsMastered=4

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 13,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "2dfef9a6-a06f-44a3-996e-75a2b7b1f4ac",
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
