# Sunny Session Debug Summary

sessionId: 569281cd-21d8-4c2d-b5a7-324c67ee38a1
date: 2026-05-08T00:18:42.502Z
endedAt: 2026-05-08T00:29:01.772Z
child: Reina
subject: homework
mode: real
gitCommit: 46d65e5
command: npm run npx
duration_ms: 619270
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +416s flow_game.game_state_update game="Letter Rush" type="game_state_update"
- +419s flow_game.game_state_update game="Letter Rush" type="game_state_update"
- +420s flow_game.game_state_update game="Letter Rush" type="game_state_update"
- +420s flow_game.game_state_update game="Letter Rush" type="game_state_update" reason="timeout"
- +439s transcript.accepted turnState="IDLE" round=5 transcriptLength=350
- +439s ws.send type="session_state" state="LOADING"
- +439s turn.state_changed state="LOADING"
- +439s ws.send type="session_state" state="PROCESSING"
- +439s turn.state_changed state="PROCESSING"
- +442s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +442s tool.client_result tool="companionAct"
- +443s transcript.queued turnState="PROCESSING" round=6 transcriptLength=38
- +444s transcript.queued turnState="PROCESSING" round=6 transcriptLength=7
- +445s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +445s tool.client_result tool="sessionStatus"
- +447s ws.send type="session_state" state="SPEAKING"
- +447s turn.state_changed state="SPEAKING"
- +453s ws.send type="session_state" state="IDLE"
- +453s turn.state_changed state="IDLE"
- +453s transcript.replay turnState="IDLE" round=6 transcriptLength=7
- +453s transcript.accepted turnState="IDLE" round=6 transcriptLength=7
- +453s ws.send type="session_state" state="LOADING"
- +453s turn.state_changed state="LOADING"
- +453s ws.send type="session_state" state="PROCESSING"
- +453s turn.state_changed state="PROCESSING"
- +455s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +455s tool.client_result tool="companionAct"
- +457s ws.send type="session_state" state="SPEAKING"
- +457s turn.state_changed state="SPEAKING"
- +463s ws.send type="session_state" state="IDLE"
- +463s turn.state_changed state="IDLE"
- +466s transcript.accepted turnState="IDLE" round=7 transcriptLength=46
- +466s ws.send type="session_state" state="LOADING"
- +466s turn.state_changed state="LOADING"
- +466s ws.send type="session_state" state="PROCESSING"
- +466s turn.state_changed state="PROCESSING"
- +468s tool.called tool="launchGame" argsKeys=["name","type"] hasResult=true
- +468s tool.client_result tool="launchGame"
- +468s canvas.draw mode="space-invaders" canvasRevision=1
- +468s flow_game.game_state_update game="Space Invaders — Project Sunny" type="game_state_update"
- +470s ws.send type="session_state" state="SPEAKING"
- +470s turn.state_changed state="SPEAKING"
- +477s ws.send type="session_state" state="IDLE"
- +477s turn.state_changed state="IDLE"
- +503s transcript.accepted turnState="IDLE" round=8 transcriptLength=16
- +503s ws.send type="session_state" state="LOADING"
- +503s turn.state_changed state="LOADING"
- +503s ws.send type="session_state" state="PROCESSING"
- +503s turn.state_changed state="PROCESSING"
- +505s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +505s tool.client_result tool="companionAct"
- +507s ws.send type="session_state" state="SPEAKING"
- +507s turn.state_changed state="SPEAKING"
- +512s ws.send type="session_state" state="IDLE"
- +512s turn.state_changed state="IDLE"
- +525s transcript.accepted turnState="IDLE" round=9 transcriptLength=153
- +525s ws.send type="session_state" state="LOADING"
- +525s turn.state_changed state="LOADING"
- +525s ws.send type="session_state" state="PROCESSING"
- +525s turn.state_changed state="PROCESSING"
- +530s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +530s tool.client_result tool="companionAct"
- +531s ws.send type="session_state" state="SPEAKING"
- +531s turn.state_changed state="SPEAKING"
- +537s ws.send type="session_state" state="IDLE"
- +537s turn.state_changed state="IDLE"
- +543s transcript.accepted turnState="IDLE" round=10 transcriptLength=301
- +543s ws.send type="session_state" state="LOADING"
- +543s turn.state_changed state="LOADING"
- +543s ws.send type="session_state" state="PROCESSING"
- +543s turn.state_changed state="PROCESSING"
- +545s tool.called tool="sessionEnd" argsKeys=["childName","reason"] hasResult=true
- +545s tool.client_result tool="sessionEnd"
- +548s ws.send type="session_state" state="SPEAKING"
- +548s turn.state_changed state="SPEAKING"
- +548s session.ending turnState="SPEAKING" roundNumber=11 isEnding=true childName="Reina" canvasMode="space-invaders" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=508
- +548s ws.send type="session_state" state="IDLE"
- +548s turn.state_changed state="IDLE"
- +548s engine.session_finalized totalAttempts=0 accuracy=0
- +548s engine.progression_computed level=97 totalXP=9635 wordsMastered=43

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 11,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "569281cd-21d8-4c2d-b5a7-324c67ee38a1",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 508
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 508,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
