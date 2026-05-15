# Sunny Session Debug Summary

sessionId: c9b3f353-77c6-4b29-9f1a-f3f4b4c661e0
date: 2026-05-15T23:42:21.422Z
endedAt: 2026-05-15T23:53:17.704Z
child: Ila
subject: homework
mode: real
gitCommit: ec55b2b
command: npm run npx
duration_ms: 656282
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +577s turn.state_changed state="IDLE"
- +577s transcript.replay turnState="IDLE" round=22 transcriptLength=23
- +577s transcript.accepted turnState="IDLE" round=22 transcriptLength=23
- +577s ws.send type="session_state" state="LOADING"
- +577s turn.state_changed state="LOADING"
- +577s ws.send type="session_state" state="PROCESSING"
- +577s turn.state_changed state="PROCESSING"
- +578s transcript.queued turnState="PROCESSING" round=23 transcriptLength=10
- +578s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +579s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +579s tool.client_result tool="companionAct"
- +581s ws.send type="session_state" state="SPEAKING"
- +581s turn.state_changed state="SPEAKING"
- +582s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +586s ws.send type="session_state" state="IDLE"
- +586s turn.state_changed state="IDLE"
- +586s transcript.replay turnState="IDLE" round=23 transcriptLength=10
- +586s transcript.accepted turnState="IDLE" round=23 transcriptLength=10
- +586s ws.send type="session_state" state="LOADING"
- +586s turn.state_changed state="LOADING"
- +586s ws.send type="session_state" state="PROCESSING"
- +586s turn.state_changed state="PROCESSING"
- +587s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +589s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +589s tool.client_result tool="companionAct"
- +590s ws.send type="session_state" state="SPEAKING"
- +590s turn.state_changed state="SPEAKING"
- +592s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +592s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +594s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +595s ws.send type="session_state" state="IDLE"
- +595s turn.state_changed state="IDLE"
- +597s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +602s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +605s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +605s flow_game.game_state_update game="Project Sunny — Wheel of Fortune" type="game_state_update"
- +612s transcript.accepted turnState="IDLE" round=24 transcriptLength=25
- +612s ws.send type="session_state" state="LOADING"
- +612s turn.state_changed state="LOADING"
- +612s ws.send type="session_state" state="PROCESSING"
- +612s turn.state_changed state="PROCESSING"
- +612s transcript.queued turnState="PROCESSING" round=25 transcriptLength=152
- +613s transcript.duplicate_suppressed turnState="PROCESSING" round=25 transcriptLength=152
- +614s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +614s tool.client_result tool="companionAct"
- +617s ws.send type="session_state" state="SPEAKING"
- +617s turn.state_changed state="SPEAKING"
- +625s ws.send type="session_state" state="IDLE"
- +625s turn.state_changed state="IDLE"
- +625s transcript.replay turnState="IDLE" round=25 transcriptLength=152
- +625s transcript.accepted turnState="IDLE" round=25 transcriptLength=152
- +625s ws.send type="session_state" state="LOADING"
- +625s turn.state_changed state="LOADING"
- +625s ws.send type="session_state" state="PROCESSING"
- +625s turn.state_changed state="PROCESSING"
- +627s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +627s tool.client_result tool="companionAct"
- +629s ws.send type="session_state" state="SPEAKING"
- +629s turn.state_changed state="SPEAKING"
- +635s ws.send type="session_state" state="IDLE"
- +635s turn.state_changed state="IDLE"
- +638s transcript.accepted turnState="IDLE" round=26 transcriptLength=129
- +638s ws.send type="session_state" state="LOADING"
- +638s turn.state_changed state="LOADING"
- +638s ws.send type="session_state" state="PROCESSING"
- +638s turn.state_changed state="PROCESSING"
- +640s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +640s tool.client_result tool="companionAct"
- +642s ws.send type="session_state" state="SPEAKING"
- +642s turn.state_changed state="SPEAKING"
- +648s ws.send type="session_state" state="IDLE"
- +648s turn.state_changed state="IDLE"
- +648s transcript.accepted turnState="IDLE" round=27 transcriptLength=55
- +648s ws.send type="session_state" state="LOADING"
- +648s turn.state_changed state="LOADING"
- +648s session.ending turnState="LOADING" roundNumber=27 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=292
- +648s ws.send type="session_state" state="IDLE"
- +648s turn.state_changed state="IDLE"
- +648s engine.session_finalized totalAttempts=0 accuracy=0
- +648s engine.progression_computed level=72 totalXP=7130 wordsMastered=9

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 27,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "c9b3f353-77c6-4b29-9f1a-f3f4b4c661e0",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 292
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 292,
  "rewardLogEntries": 18
}
```

## Upload
Session saved locally. Upload not configured yet.
