# Sunny Session Debug Summary

sessionId: cf06ff1c-eca0-49af-9ffb-6261848bf956
date: 2026-05-19T05:13:46.124Z
endedAt: 2026-05-19T05:15:26.993Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 100869
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
- +74s turn.state_changed state="PROCESSING"
- +74s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +76s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +77s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +77s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +77s tool.client_result tool="companionAct"
- +78s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +79s ws.send type="session_state" state="SPEAKING"
- +79s turn.state_changed state="SPEAKING"
- +79s ws.send type="session_state" state="IDLE"
- +79s turn.state_changed state="IDLE"
- +79s transcript.replay turnState="IDLE" round=10 transcriptLength=16
- +79s transcript.accepted turnState="IDLE" round=10 transcriptLength=16
- +79s ws.send type="session_state" state="LOADING"
- +79s turn.state_changed state="LOADING"
- +79s ws.send type="session_state" state="PROCESSING"
- +79s turn.state_changed state="PROCESSING"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +80s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +81s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +81s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +81s tool.client_result tool="companionAct"
- +82s transcript.queued turnState="PROCESSING" round=11 transcriptLength=16
- +83s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +83s tool.client_result tool="takeGameScreenshot"
- +84s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +84s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +85s ws.send type="session_state" state="SPEAKING"
- +85s turn.state_changed state="SPEAKING"
- +85s ws.send type="session_state" state="IDLE"
- +85s turn.state_changed state="IDLE"
- +85s transcript.replay turnState="IDLE" round=11 transcriptLength=16
- +85s transcript.accepted turnState="IDLE" round=11 transcriptLength=16
- +85s ws.send type="session_state" state="LOADING"
- +85s turn.state_changed state="LOADING"
- +85s ws.send type="session_state" state="PROCESSING"
- +85s turn.state_changed state="PROCESSING"
- +85s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +86s transcript.queued turnState="PROCESSING" round=12 transcriptLength=16
- +87s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +87s tool.client_result tool="takeGameScreenshot"
- +88s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
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
- +89s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +89s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +90s transcript.queued turnState="PROCESSING" round=13 transcriptLength=16
- +91s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +91s tool.client_result tool="takeGameScreenshot"
- +92s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +93s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +93s tool.client_result tool="companionAct"
- +94s transcript.queued turnState="PROCESSING" round=13 transcriptLength=16
- +94s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +94s ws.send type="session_state" state="SPEAKING"
- +94s turn.state_changed state="SPEAKING"
- +94s ws.send type="session_state" state="IDLE"
- +94s turn.state_changed state="IDLE"
- +94s transcript.replay turnState="IDLE" round=13 transcriptLength=16
- +94s transcript.accepted turnState="IDLE" round=13 transcriptLength=16
- +94s ws.send type="session_state" state="LOADING"
- +94s turn.state_changed state="LOADING"
- +95s ws.send type="session_state" state="PROCESSING"
- +95s turn.state_changed state="PROCESSING"
- +95s transcript.duplicate_suppressed turnState="PROCESSING" round=14 transcriptLength=16
- +95s session.ending turnState="PROCESSING" roundNumber=14 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=42
- +95s ws.send type="session_state" state="IDLE"
- +95s turn.state_changed state="IDLE"
- +95s engine.session_finalized totalAttempts=12 accuracy=1
- +95s engine.progression_computed level=2 totalXP=125 wordsMastered=0
- +98s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +98s tool.client_result tool="takeGameScreenshot"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 14,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "cf06ff1c-eca0-49af-9ffb-6261848bf956",
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
