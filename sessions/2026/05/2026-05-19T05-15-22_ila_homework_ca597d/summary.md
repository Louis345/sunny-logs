# Sunny Session Debug Summary

sessionId: ca597d52-5b38-4b30-98b1-43ceec35ccf6
date: 2026-05-19T05:15:22.401Z
endedAt: 2026-05-19T05:16:58.601Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 96200
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
- +70s transcript.queued turnState="PROCESSING" round=8 transcriptLength=16
- +72s ws.send type="session_state" state="SPEAKING"
- +72s turn.state_changed state="SPEAKING"
- +72s ws.send type="session_state" state="IDLE"
- +72s turn.state_changed state="IDLE"
- +72s transcript.replay turnState="IDLE" round=8 transcriptLength=16
- +72s transcript.accepted turnState="IDLE" round=8 transcriptLength=16
- +72s ws.send type="session_state" state="LOADING"
- +72s turn.state_changed state="LOADING"
- +72s ws.send type="session_state" state="PROCESSING"
- +72s turn.state_changed state="PROCESSING"
- +72s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +73s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +74s transcript.queued turnState="PROCESSING" round=9 transcriptLength=16
- +76s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +76s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +76s tool.client_result tool="companionAct"
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
- +78s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +78s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +80s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +80s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +80s tool.client_result tool="companionAct"
- +81s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +82s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +82s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +82s tool.client_result tool="takeGameScreenshot"
- +83s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +84s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
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
- +86s transcript.queued turnState="PROCESSING" round=11 transcriptLength=16
- +86s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +86s tool.client_result tool="companionAct"
- +88s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +88s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +89s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +90s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +90s tool.client_result tool="takeGameScreenshot"
- +90s transcript.queued turnState="PROCESSING" round=11 transcriptLength=16
- +92s ws.send type="session_state" state="SPEAKING"
- +92s turn.state_changed state="SPEAKING"
- +92s transcript.duplicate_suppressed turnState="SPEAKING" round=11 transcriptLength=16
- +92s ws.send type="session_state" state="IDLE"
- +92s turn.state_changed state="IDLE"
- +92s transcript.replay turnState="IDLE" round=11 transcriptLength=16
- +92s transcript.accepted turnState="IDLE" round=11 transcriptLength=16
- +92s ws.send type="session_state" state="LOADING"
- +92s turn.state_changed state="LOADING"
- +92s ws.send type="session_state" state="PROCESSING"
- +92s turn.state_changed state="PROCESSING"
- +93s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +93s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +93s session.ending turnState="PROCESSING" roundNumber=12 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=40
- +93s ws.send type="session_state" state="IDLE"
- +94s turn.state_changed state="IDLE"
- +94s engine.session_finalized totalAttempts=14 accuracy=1
- +94s engine.progression_computed level=4 totalXP=320 wordsMastered=2
- +96s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +96s tool.client_result tool="companionAct"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 12,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "ca597d52-5b38-4b30-98b1-43ceec35ccf6",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 40
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 40,
  "rewardLogEntries": 2
}
```

## Upload
Session saved locally. Upload not configured yet.
