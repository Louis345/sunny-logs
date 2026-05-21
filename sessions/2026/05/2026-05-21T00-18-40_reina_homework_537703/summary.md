# Sunny Session Debug Summary

sessionId: 53770372-a3b6-4949-a21e-37a23f257b54
date: 2026-05-21T00:18:40.912Z
endedAt: 2026-05-21T00:30:13.027Z
child: Reina
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 692115
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
- +592s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +592s tool.client_result tool="companionAct"
- +592s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +595s ws.send type="session_state" state="SPEAKING"
- +595s turn.state_changed state="SPEAKING"
- +596s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +598s ws.send type="session_state" state="IDLE"
- +598s turn.state_changed state="IDLE"
- +598s transcript.replay turnState="IDLE" round=18 transcriptLength=37
- +598s transcript.accepted turnState="IDLE" round=18 transcriptLength=37
- +598s ws.send type="session_state" state="LOADING"
- +598s turn.state_changed state="LOADING"
- +598s ws.send type="session_state" state="PROCESSING"
- +598s turn.state_changed state="PROCESSING"
- +599s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +599s flow_game.game_state_update game="Project Sunny — Wheel of Fortune" type="game_state_update"
- +599s transcript.queued turnState="PROCESSING" round=19 transcriptLength=26
- +602s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +602s tool.client_result tool="companionAct"
- +602s flow_game.game_complete game="unknown" type="game_complete"
- +604s ws.send type="session_state" state="SPEAKING"
- +604s turn.state_changed state="SPEAKING"
- +605s ws.send type="session_state" state="IDLE"
- +605s turn.state_changed state="IDLE"
- +605s transcript.replay turnState="IDLE" round=19 transcriptLength=26
- +605s transcript.accepted turnState="IDLE" round=19 transcriptLength=26
- +605s ws.send type="session_state" state="LOADING"
- +605s turn.state_changed state="LOADING"
- +605s ws.send type="session_state" state="PROCESSING"
- +605s turn.state_changed state="PROCESSING"
- +608s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +608s tool.client_result tool="companionAct"
- +609s transcript.queued turnState="PROCESSING" round=20 transcriptLength=49
- +610s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +610s tool.client_result tool="sessionStatus"
- +611s ws.send type="session_state" state="SPEAKING"
- +611s turn.state_changed state="SPEAKING"
- +622s ws.send type="session_state" state="IDLE"
- +622s turn.state_changed state="IDLE"
- +622s transcript.replay turnState="IDLE" round=20 transcriptLength=49
- +622s transcript.accepted turnState="IDLE" round=20 transcriptLength=49
- +622s ws.send type="session_state" state="LOADING"
- +622s turn.state_changed state="LOADING"
- +622s ws.send type="session_state" state="PROCESSING"
- +622s turn.state_changed state="PROCESSING"
- +623s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +623s tool.client_result tool="sessionStatus"
- +627s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +627s tool.client_result tool="companionAct"
- +634s ws.send type="session_state" state="SPEAKING"
- +634s turn.state_changed state="SPEAKING"
- +642s ws.send type="session_state" state="IDLE"
- +642s turn.state_changed state="IDLE"
- +648s transcript.accepted turnState="IDLE" round=21 transcriptLength=82
- +648s ws.send type="session_state" state="LOADING"
- +648s turn.state_changed state="LOADING"
- +648s ws.send type="session_state" state="PROCESSING"
- +648s turn.state_changed state="PROCESSING"
- +652s tool.called tool="recordProductIssue" argsKeys=["issueType","severity","childUtterance","evidenceText","confidence","source"] hasResult=true
- +652s tool.client_result tool="recordProductIssue"
- +654s ws.send type="session_state" state="SPEAKING"
- +654s turn.state_changed state="SPEAKING"
- +657s ws.send type="session_state" state="IDLE"
- +657s turn.state_changed state="IDLE"
- +672s transcript.accepted turnState="IDLE" round=22 transcriptLength=55
- +672s ws.send type="session_state" state="LOADING"
- +672s turn.state_changed state="LOADING"
- +672s ws.send type="session_state" state="PROCESSING"
- +672s turn.state_changed state="PROCESSING"
- +676s tool.called tool="recordProductIssue" argsKeys=["issueType","severity","childUtterance","evidenceText","confidence","source"] hasResult=true
- +676s tool.client_result tool="recordProductIssue"
- +682s tool.called tool="sessionEnd" argsKeys=["childName","reason"] hasResult=true
- +682s tool.client_result tool="sessionEnd"
- +684s ws.send type="session_state" state="SPEAKING"
- +684s turn.state_changed state="SPEAKING"
- +684s session.ending turnState="SPEAKING" roundNumber=23 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=143
- +684s ws.send type="session_state" state="IDLE"
- +684s turn.state_changed state="IDLE"
- +684s engine.session_finalized totalAttempts=58 accuracy=0.7586206896551724
- +684s engine.progression_computed level=88 totalXP=8745 wordsMastered=40

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 23,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "53770372-a3b6-4949-a21e-37a23f257b54",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 143
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 143,
  "rewardLogEntries": 29
}
```

## Upload
Session saved locally. Upload not configured yet.
