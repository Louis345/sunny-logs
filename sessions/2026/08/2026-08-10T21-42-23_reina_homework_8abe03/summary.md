# Sunny Session Debug Summary

sessionId: 8abe0325-1262-4ff5-9d4a-82e220aa5dbb
date: 2026-08-10T21:42:23.885Z
endedAt: 2026-08-10T21:54:10.764Z
child: Reina
subject: homework
mode: real
gitCommit: 9beac0f
command: npm run npx
duration_ms: 706879
result: errored

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +437s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +438s flow_game.attempt_event game="unknown" type="attempt_event"
- +438s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +439s flow_game.attempt_event game="unknown" type="attempt_event"
- +439s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +442s flow_game.attempt_event game="unknown" type="attempt_event"
- +442s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +482s transcript.accepted turnState="IDLE" round=14 transcriptLength=51
- +482s ws.send type="session_state" state="LOADING"
- +482s turn.state_changed state="LOADING"
- +482s ws.send type="session_state" state="PROCESSING"
- +482s turn.state_changed state="PROCESSING"
- +483s transcript.queued turnState="PROCESSING" round=15 transcriptLength=12
- +486s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +486s tool.client_result tool="companionAct"
- +488s ws.send type="session_state" state="SPEAKING"
- +488s turn.state_changed state="SPEAKING"
- +488s flow_game.attempt_event game="unknown" type="attempt_event"
- +488s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +492s ws.send type="session_state" state="IDLE"
- +492s turn.state_changed state="IDLE"
- +492s transcript.replay turnState="IDLE" round=15 transcriptLength=12
- +492s transcript.accepted turnState="IDLE" round=15 transcriptLength=12
- +492s ws.send type="session_state" state="LOADING"
- +492s turn.state_changed state="LOADING"
- +492s ws.send type="session_state" state="PROCESSING"
- +492s turn.state_changed state="PROCESSING"
- +496s ws.send type="session_state" state="SPEAKING"
- +496s turn.state_changed state="SPEAKING"
- +496s transcript.dropped reason="assistant_owns_turn" turnState="SPEAKING" round=16 transcriptLength=9
- +501s ws.send type="session_state" state="IDLE"
- +501s turn.state_changed state="IDLE"
- +510s transcript.accepted turnState="IDLE" round=16 transcriptLength=11
- +510s ws.send type="session_state" state="LOADING"
- +510s turn.state_changed state="LOADING"
- +510s ws.send type="session_state" state="PROCESSING"
- +510s turn.state_changed state="PROCESSING"
- +514s ws.send type="session_state" state="SPEAKING"
- +514s turn.state_changed state="SPEAKING"
- +519s ws.send type="session_state" state="IDLE"
- +519s turn.state_changed state="IDLE"
- +523s transcript.accepted turnState="IDLE" round=17 transcriptLength=14
- +523s ws.send type="session_state" state="LOADING"
- +523s turn.state_changed state="LOADING"
- +523s ws.send type="session_state" state="PROCESSING"
- +523s turn.state_changed state="PROCESSING"
- +525s ws.send type="session_state" state="SPEAKING"
- +525s turn.state_changed state="SPEAKING"
- +529s ws.send type="session_state" state="IDLE"
- +529s turn.state_changed state="IDLE"
- +532s flow_game.attempt_event game="unknown" type="attempt_event"
- +532s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +539s transcript.accepted turnState="IDLE" round=18 transcriptLength=66
- +539s ws.send type="session_state" state="LOADING"
- +539s turn.state_changed state="LOADING"
- +539s ws.send type="session_state" state="PROCESSING"
- +539s turn.state_changed state="PROCESSING"
- +541s flow_game.attempt_event game="unknown" type="attempt_event"
- +541s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +542s ws.send type="session_state" state="SPEAKING"
- +542s turn.state_changed state="SPEAKING"
- +542s transcript.dropped reason="assistant_owns_turn" turnState="SPEAKING" round=19 transcriptLength=12
- +545s flow_game.attempt_event game="unknown" type="attempt_event"
- +545s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +546s ws.send type="session_state" state="IDLE"
- +546s turn.state_changed state="IDLE"
- +571s flow_game.attempt_event game="unknown" type="attempt_event"
- +571s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +611s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +629s flow_game.game_state_update game="generated-baseline" type="game_state_update" activityId="ACT-SHARED-01"
- +630s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +635s flow_game.attempt_event game="unknown" type="attempt_event"
- +636s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +678s flow_game.attempt_event game="unknown" type="attempt_event"
- +678s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +693s flow_game.attempt_event game="unknown" type="attempt_event"
- +693s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="ACT-SHARED-01"
- +706s session.ending turnState="IDLE" roundNumber=19 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=65
- +707s engine.session_finalized totalAttempts=0 accuracy=0
- +707s engine.progression_computed level=15 totalXP=1405 wordsMastered=4

## Errors
- [2026-08-10T21:54:10.754Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 19,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "8abe0325-1262-4ff5-9d4a-82e220aa5dbb",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 65
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "postSessionError": "ENOENT: no such file or directory, open '/Users/jamaltaylor/Development/sunny-feedback-ingestion-proof-2026-08-09-1805/src/context/reina/soul.md'",
  "shouldPersistSessionData": true,
  "conversationTurns": 65,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
