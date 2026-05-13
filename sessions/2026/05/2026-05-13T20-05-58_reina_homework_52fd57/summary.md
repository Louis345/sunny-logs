# Sunny Session Debug Summary

sessionId: 52fd57cb-de8c-416b-b28d-10543a1732f3
date: 2026-05-13T20:05:58.902Z
endedAt: 2026-05-13T20:17:04.008Z
child: Reina
subject: homework
mode: real
gitCommit: 7bbbafb
command: npm run npx
duration_ms: 665106
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: 
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +521s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +521s flow_game.game_state_update game="Project Sunny — Wheel of Fortune" type="game_state_update"
- +522s transcript.accepted turnState="IDLE" round=10 transcriptLength=33
- +522s ws.send type="session_state" state="LOADING"
- +522s turn.state_changed state="LOADING"
- +522s ws.send type="session_state" state="PROCESSING"
- +522s turn.state_changed state="PROCESSING"
- +524s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +524s tool.client_result tool="companionAct"
- +524s transcript.queued turnState="PROCESSING" round=11 transcriptLength=36
- +526s ws.send type="session_state" state="SPEAKING"
- +526s turn.state_changed state="SPEAKING"
- +531s ws.send type="session_state" state="IDLE"
- +531s turn.state_changed state="IDLE"
- +531s transcript.replay turnState="IDLE" round=11 transcriptLength=36
- +531s transcript.accepted turnState="IDLE" round=11 transcriptLength=36
- +531s ws.send type="session_state" state="LOADING"
- +531s turn.state_changed state="LOADING"
- +531s ws.send type="session_state" state="PROCESSING"
- +531s turn.state_changed state="PROCESSING"
- +533s transcript.queued turnState="PROCESSING" round=12 transcriptLength=9
- +533s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +533s tool.client_result tool="companionAct"
- +535s ws.send type="session_state" state="SPEAKING"
- +535s turn.state_changed state="SPEAKING"
- +538s ws.send type="session_state" state="IDLE"
- +538s turn.state_changed state="IDLE"
- +538s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=12 tts="on"
- +538s canvas.draw mode="idle"
- +558s transcript.accepted turnState="IDLE" round=12 transcriptLength=48
- +558s ws.send type="session_state" state="LOADING"
- +558s turn.state_changed state="LOADING"
- +558s ws.send type="session_state" state="PROCESSING"
- +558s turn.state_changed state="PROCESSING"
- +560s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +560s tool.client_result tool="companionAct"
- +562s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +562s tool.client_result tool="takeGameScreenshot"
- +564s ws.send type="session_state" state="SPEAKING"
- +564s turn.state_changed state="SPEAKING"
- +571s ws.send type="session_state" state="IDLE"
- +571s turn.state_changed state="IDLE"
- +571s transcript.accepted turnState="IDLE" round=13 transcriptLength=41
- +571s ws.send type="session_state" state="LOADING"
- +571s turn.state_changed state="LOADING"
- +571s ws.send type="session_state" state="PROCESSING"
- +571s turn.state_changed state="PROCESSING"
- +574s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +574s tool.client_result tool="companionAct"
- +575s ws.send type="session_state" state="SPEAKING"
- +575s turn.state_changed state="SPEAKING"
- +582s ws.send type="session_state" state="IDLE"
- +582s turn.state_changed state="IDLE"
- +595s transcript.accepted turnState="IDLE" round=14 transcriptLength=6
- +595s ws.send type="session_state" state="LOADING"
- +595s turn.state_changed state="LOADING"
- +595s ws.send type="session_state" state="PROCESSING"
- +595s turn.state_changed state="PROCESSING"
- +600s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +600s tool.client_result tool="companionAct"
- +600s transcript.queued turnState="PROCESSING" round=15 transcriptLength=25
- +602s ws.send type="session_state" state="SPEAKING"
- +602s turn.state_changed state="SPEAKING"
- +609s ws.send type="session_state" state="IDLE"
- +609s turn.state_changed state="IDLE"
- +609s transcript.replay turnState="IDLE" round=15 transcriptLength=25
- +609s transcript.accepted turnState="IDLE" round=15 transcriptLength=25
- +609s ws.send type="session_state" state="LOADING"
- +609s turn.state_changed state="LOADING"
- +609s ws.send type="session_state" state="PROCESSING"
- +609s turn.state_changed state="PROCESSING"
- +611s tool.called tool="sessionEnd" argsKeys=["childName","reason"] hasResult=true
- +611s tool.client_result tool="sessionEnd"
- +613s ws.send type="session_state" state="SPEAKING"
- +613s turn.state_changed state="SPEAKING"
- +613s session.ending turnState="SPEAKING" roundNumber=16 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=393
- +613s ws.send type="session_state" state="IDLE"
- +613s turn.state_changed state="IDLE"
- +613s engine.session_finalized totalAttempts=0 accuracy=0
- +613s engine.progression_computed level=74 totalXP=7340 wordsMastered=28

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 16,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "52fd57cb-de8c-416b-b28d-10543a1732f3",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 393
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 393,
  "rewardLogEntries": 27
}
```

## Upload
Session saved locally. Upload not configured yet.
