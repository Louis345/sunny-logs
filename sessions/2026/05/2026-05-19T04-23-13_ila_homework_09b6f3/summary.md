# Sunny Session Debug Summary

sessionId: 09b6f316-2e94-454d-a8c3-b955352a2a98
date: 2026-05-19T04:23:13.563Z
endedAt: 2026-05-19T04:25:05.601Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 112038
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
- +84s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +85s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +85s tool.client_result tool="takeGameScreenshot"
- +85s transcript.queued turnState="PROCESSING" round=9 transcriptLength=16
- +87s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +87s ws.send type="session_state" state="SPEAKING"
- +87s turn.state_changed state="SPEAKING"
- +87s ws.send type="session_state" state="IDLE"
- +87s turn.state_changed state="IDLE"
- +87s transcript.replay turnState="IDLE" round=9 transcriptLength=16
- +87s transcript.accepted turnState="IDLE" round=9 transcriptLength=16
- +87s ws.send type="session_state" state="LOADING"
- +87s turn.state_changed state="LOADING"
- +87s ws.send type="session_state" state="PROCESSING"
- +87s turn.state_changed state="PROCESSING"
- +88s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +89s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +90s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +90s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +90s tool.client_result tool="companionAct"
- +91s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +92s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +92s tool.client_result tool="takeGameScreenshot"
- +92s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +94s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +94s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +95s transcript.duplicate_suppressed turnState="PROCESSING" round=10 transcriptLength=16
- +96s ws.send type="session_state" state="SPEAKING"
- +96s turn.state_changed state="SPEAKING"
- +96s ws.send type="session_state" state="IDLE"
- +96s turn.state_changed state="IDLE"
- +96s transcript.replay turnState="IDLE" round=10 transcriptLength=16
- +96s transcript.accepted turnState="IDLE" round=10 transcriptLength=16
- +96s ws.send type="session_state" state="LOADING"
- +96s turn.state_changed state="LOADING"
- +96s ws.send type="session_state" state="PROCESSING"
- +96s turn.state_changed state="PROCESSING"
- +97s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +98s transcript.queued turnState="PROCESSING" round=11 transcriptLength=16
- +99s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +99s tool.client_result tool="takeGameScreenshot"
- +100s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +100s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +100s ws.send type="session_state" state="SPEAKING"
- +100s turn.state_changed state="SPEAKING"
- +100s ws.send type="session_state" state="IDLE"
- +100s turn.state_changed state="IDLE"
- +100s transcript.replay turnState="IDLE" round=11 transcriptLength=16
- +100s transcript.accepted turnState="IDLE" round=11 transcriptLength=16
- +100s ws.send type="session_state" state="LOADING"
- +100s turn.state_changed state="LOADING"
- +100s ws.send type="session_state" state="PROCESSING"
- +100s turn.state_changed state="PROCESSING"
- +101s transcript.queued turnState="PROCESSING" round=12 transcriptLength=16
- +103s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +103s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +103s tool.client_result tool="companionAct"
- +104s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +104s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +105s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +105s tool.client_result tool="takeGameScreenshot"
- +106s transcript.queued turnState="PROCESSING" round=12 transcriptLength=16
- +107s ws.send type="session_state" state="SPEAKING"
- +107s turn.state_changed state="SPEAKING"
- +107s ws.send type="session_state" state="IDLE"
- +107s turn.state_changed state="IDLE"
- +107s transcript.replay turnState="IDLE" round=12 transcriptLength=16
- +107s transcript.accepted turnState="IDLE" round=12 transcriptLength=16
- +107s ws.send type="session_state" state="LOADING"
- +107s turn.state_changed state="LOADING"
- +107s transcript.duplicate_suppressed turnState="LOADING" round=13 transcriptLength=16
- +107s ws.send type="session_state" state="PROCESSING"
- +107s turn.state_changed state="PROCESSING"
- +108s session.ending turnState="PROCESSING" roundNumber=13 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=42
- +108s ws.send type="session_state" state="IDLE"
- +108s turn.state_changed state="IDLE"
- +108s engine.session_finalized totalAttempts=16 accuracy=1
- +108s engine.progression_computed level=4 totalXP=380 wordsMastered=4
- +110s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +110s tool.client_result tool="companionAct"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 13,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "09b6f316-2e94-454d-a8c3-b955352a2a98",
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
  "rewardLogEntries": 4
}
```

## Upload
Session saved locally. Upload not configured yet.
