# Sunny Session Debug Summary

sessionId: 3f76b8e9-2fed-4e4c-97ca-56897f7f6e91
date: 2026-05-19T04:52:58.358Z
endedAt: 2026-05-19T04:54:36.382Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 98024
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
- +68s transcript.duplicate_suppressed turnState="PROCESSING" round=8 transcriptLength=16
- +68s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +68s tool.client_result tool="companionAct"
- +69s ws.send type="session_state" state="SPEAKING"
- +69s turn.state_changed state="SPEAKING"
- +69s ws.send type="session_state" state="IDLE"
- +69s turn.state_changed state="IDLE"
- +69s transcript.replay turnState="IDLE" round=8 transcriptLength=16
- +69s transcript.accepted turnState="IDLE" round=8 transcriptLength=16
- +69s ws.send type="session_state" state="LOADING"
- +69s turn.state_changed state="LOADING"
- +69s ws.send type="session_state" state="PROCESSING"
- +69s turn.state_changed state="PROCESSING"
- +69s transcript.queued turnState="PROCESSING" round=9 transcriptLength=16
- +71s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +71s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +71s tool.client_result tool="companionAct"
- +72s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s transcript.queued turnState="PROCESSING" round=9 transcriptLength=16
- +73s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +73s tool.client_result tool="takeGameScreenshot"
- +74s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +76s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +77s transcript.queued turnState="PROCESSING" round=9 transcriptLength=16
- +78s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +78s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +80s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +81s ws.send type="session_state" state="SPEAKING"
- +81s turn.state_changed state="SPEAKING"
- +81s ws.send type="session_state" state="IDLE"
- +81s turn.state_changed state="IDLE"
- +81s transcript.replay turnState="IDLE" round=9 transcriptLength=16
- +81s transcript.accepted turnState="IDLE" round=9 transcriptLength=16
- +81s ws.send type="session_state" state="LOADING"
- +81s turn.state_changed state="LOADING"
- +81s ws.send type="session_state" state="PROCESSING"
- +81s turn.state_changed state="PROCESSING"
- +81s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +82s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +83s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +83s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +83s tool.client_result tool="takeGameScreenshot"
- +84s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +85s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +85s ws.send type="session_state" state="SPEAKING"
- +85s turn.state_changed state="SPEAKING"
- +85s ws.send type="session_state" state="IDLE"
- +85s turn.state_changed state="IDLE"
- +85s transcript.replay turnState="IDLE" round=10 transcriptLength=16
- +85s transcript.accepted turnState="IDLE" round=10 transcriptLength=16
- +85s ws.send type="session_state" state="LOADING"
- +85s turn.state_changed state="LOADING"
- +85s ws.send type="session_state" state="PROCESSING"
- +85s turn.state_changed state="PROCESSING"
- +86s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +87s ws.send type="session_state" state="SPEAKING"
- +87s turn.state_changed state="SPEAKING"
- +87s ws.send type="session_state" state="IDLE"
- +87s turn.state_changed state="IDLE"
- +87s transcript.duplicate_suppressed turnState="IDLE" round=11 transcriptLength=16
- +88s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +89s transcript.accepted turnState="IDLE" round=11 transcriptLength=16
- +89s ws.send type="session_state" state="LOADING"
- +89s turn.state_changed state="LOADING"
- +89s ws.send type="session_state" state="PROCESSING"
- +89s turn.state_changed state="PROCESSING"
- +90s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +92s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +92s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +92s tool.client_result tool="companionAct"
- +93s transcript.queued turnState="PROCESSING" round=12 transcriptLength=16
- +93s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +93s session.ending turnState="PROCESSING" roundNumber=12 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=16 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=38
- +93s ws.send type="session_state" state="IDLE"
- +93s turn.state_changed state="IDLE"
- +93s engine.session_finalized totalAttempts=12 accuracy=1
- +93s engine.progression_computed level=17 totalXP=1665 wordsMastered=4
- +94s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +94s tool.client_result tool="takeGameScreenshot"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 12,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "3f76b8e9-2fed-4e4c-97ca-56897f7f6e91",
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
