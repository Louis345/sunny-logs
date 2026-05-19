# Sunny Session Debug Summary

sessionId: a8126824-11ad-4bfc-8d5f-1ed924d127ed
date: 2026-05-19T23:31:17.182Z
endedAt: 2026-05-19T23:40:46.205Z
child: Reina
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 569023
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +478s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +482s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +485s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +490s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +495s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +498s transcript.accepted turnState="IDLE" round=22 transcriptLength=8
- +498s ws.send type="session_state" state="LOADING"
- +498s turn.state_changed state="LOADING"
- +498s ws.send type="session_state" state="PROCESSING"
- +498s turn.state_changed state="PROCESSING"
- +500s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +500s tool.client_result tool="companionAct"
- +500s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +502s ws.send type="session_state" state="SPEAKING"
- +502s turn.state_changed state="SPEAKING"
- +505s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +510s ws.send type="session_state" state="IDLE"
- +510s turn.state_changed state="IDLE"
- +510s transcript.accepted turnState="IDLE" round=23 transcriptLength=53
- +510s ws.send type="session_state" state="LOADING"
- +510s turn.state_changed state="LOADING"
- +510s ws.send type="session_state" state="PROCESSING"
- +510s turn.state_changed state="PROCESSING"
- +510s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +511s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +511s flow_game.game_state_update game="Project Sunny — Wheel of Fortune" type="game_state_update"
- +514s tool.called tool="sessionLog" argsKeys=["word","correct","observation"] hasResult=false
- +514s tool.client_result tool="sessionLog"
- +514s flow_game.game_complete game="unknown" type="game_complete"
- +516s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word","observation"] hasResult=true
- +516s tool.client_result tool="sessionLog"
- +517s ws.send type="session_state" state="SPEAKING"
- +517s turn.state_changed state="SPEAKING"
- +526s ws.send type="session_state" state="IDLE"
- +526s turn.state_changed state="IDLE"
- +528s transcript.accepted turnState="IDLE" round=24 transcriptLength=39
- +528s ws.send type="session_state" state="LOADING"
- +528s turn.state_changed state="LOADING"
- +528s ws.send type="session_state" state="PROCESSING"
- +528s turn.state_changed state="PROCESSING"
- +529s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +529s tool.client_result tool="sessionStatus"
- +531s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +531s tool.client_result tool="companionAct"
- +533s transcript.queued turnState="PROCESSING" round=25 transcriptLength=69
- +533s ws.send type="session_state" state="SPEAKING"
- +533s turn.state_changed state="SPEAKING"
- +541s ws.send type="session_state" state="IDLE"
- +541s turn.state_changed state="IDLE"
- +541s transcript.replay turnState="IDLE" round=25 transcriptLength=69
- +541s transcript.accepted turnState="IDLE" round=25 transcriptLength=69
- +541s ws.send type="session_state" state="LOADING"
- +541s turn.state_changed state="LOADING"
- +541s ws.send type="session_state" state="PROCESSING"
- +541s turn.state_changed state="PROCESSING"
- +542s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +542s tool.client_result tool="sessionStatus"
- +545s ws.send type="session_state" state="SPEAKING"
- +545s turn.state_changed state="SPEAKING"
- +554s ws.send type="session_state" state="IDLE"
- +554s turn.state_changed state="IDLE"
- +564s transcript.accepted turnState="IDLE" round=26 transcriptLength=16
- +564s ws.send type="session_state" state="LOADING"
- +564s turn.state_changed state="LOADING"
- +564s session.ending turnState="LOADING" roundNumber=26 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=135
- +564s ws.send type="session_state" state="IDLE"
- +564s turn.state_changed state="IDLE"
- +564s engine.session_finalized totalAttempts=55 accuracy=0.7272727272727273
- +564s engine.progression_computed level=83 totalXP=8225 wordsMastered=37
- +564s transcript.accepted turnState="IDLE" round=26 transcriptLength=16
- +564s ws.send type="session_state" state="LOADING"
- +564s turn.state_changed state="LOADING"
- +564s ws.send type="session_state" state="PROCESSING"
- +564s turn.state_changed state="PROCESSING"
- +565s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +565s tool.client_result tool="sessionStatus"
- +567s ws.send type="session_state" state="SPEAKING"
- +567s turn.state_changed state="SPEAKING"
- +567s ws.send type="session_state" state="IDLE"
- +567s turn.state_changed state="IDLE"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 27,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "a8126824-11ad-4bfc-8d5f-1ed924d127ed",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 137
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 137,
  "rewardLogEntries": 30
}
```

## Upload
Session saved locally. Upload not configured yet.
