# Sunny Session Debug Summary

sessionId: 80c6cbe0-b0b6-4506-84e5-0e22a14ffe8b
date: 2026-05-14T23:43:33.097Z
endedAt: 2026-05-14T23:58:45.581Z
child: Reina
subject: review
mode: real
gitCommit: ec55b2b
command: npm run npx
duration_ms: 912484
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: 
- SUNNY_SUBJECT: review
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +795s ws.send type="session_state" state="PROCESSING"
- +795s turn.state_changed state="PROCESSING"
- +796s transcript.queued turnState="PROCESSING" round=12 transcriptLength=15
- +797s transcript.queued turnState="PROCESSING" round=12 transcriptLength=9
- +797s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +797s tool.client_result tool="companionAct"
- +799s ws.send type="session_state" state="SPEAKING"
- +799s turn.state_changed state="SPEAKING"
- +803s ws.send type="session_state" state="IDLE"
- +803s turn.state_changed state="IDLE"
- +803s transcript.replay turnState="IDLE" round=12 transcriptLength=9
- +803s transcript.accepted turnState="IDLE" round=12 transcriptLength=9
- +803s ws.send type="session_state" state="LOADING"
- +803s turn.state_changed state="LOADING"
- +803s ws.send type="session_state" state="PROCESSING"
- +803s turn.state_changed state="PROCESSING"
- +803s transcript.queued turnState="PROCESSING" round=13 transcriptLength=25
- +805s transcript.queued turnState="PROCESSING" round=13 transcriptLength=12
- +805s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +805s tool.client_result tool="companionAct"
- +807s ws.send type="session_state" state="SPEAKING"
- +807s turn.state_changed state="SPEAKING"
- +809s ws.send type="session_state" state="IDLE"
- +809s turn.state_changed state="IDLE"
- +809s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=13 tts="on"
- +809s canvas.draw mode="idle"
- +813s transcript.accepted turnState="IDLE" round=13 transcriptLength=115
- +813s ws.send type="session_state" state="LOADING"
- +813s turn.state_changed state="LOADING"
- +813s ws.send type="session_state" state="PROCESSING"
- +813s turn.state_changed state="PROCESSING"
- +814s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +814s tool.client_result tool="sessionStatus"
- +817s ws.send type="session_state" state="SPEAKING"
- +817s turn.state_changed state="SPEAKING"
- +817s ws.send type="session_state" state="IDLE"
- +817s turn.state_changed state="IDLE"
- +817s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=14 tts="on"
- +817s canvas.draw mode="idle"
- +825s transcript.urgent_learning_support intent="companion_name_call" reason="child_called_companion" stateBefore="IDLE" round=14 transcriptLength=274 currentWord="ago" activityId="project-sunny-—-wheel-of-fortune"
- +825s urgent_learning.response intent="companion_name_call" activityId="project-sunny-—-wheel-of-fortune" currentWord="ago" hasGameMessage=true
- +825s ws.send type="session_state" state="LOADING"
- +825s turn.state_changed state="LOADING"
- +825s ws.send type="session_state" state="PROCESSING"
- +825s turn.state_changed state="PROCESSING"
- +825s ws.send type="session_state" state="SPEAKING"
- +825s turn.state_changed state="SPEAKING"
- +826s ws.send type="session_state" state="IDLE"
- +826s turn.state_changed state="IDLE"
- +829s transcript.urgent_learning_support intent="companion_name_call" reason="child_called_companion" stateBefore="IDLE" round=14 transcriptLength=274 currentWord="ago" activityId="project-sunny-—-wheel-of-fortune"
- +829s urgent_learning.response intent="companion_name_call" activityId="project-sunny-—-wheel-of-fortune" currentWord="ago" hasGameMessage=true
- +829s ws.send type="session_state" state="LOADING"
- +829s turn.state_changed state="LOADING"
- +829s ws.send type="session_state" state="PROCESSING"
- +829s turn.state_changed state="PROCESSING"
- +829s ws.send type="session_state" state="SPEAKING"
- +829s turn.state_changed state="SPEAKING"
- +830s ws.send type="session_state" state="IDLE"
- +830s turn.state_changed state="IDLE"
- +833s transcript.accepted turnState="IDLE" round=14 transcriptLength=10
- +833s ws.send type="session_state" state="LOADING"
- +833s turn.state_changed state="LOADING"
- +833s ws.send type="session_state" state="PROCESSING"
- +833s turn.state_changed state="PROCESSING"
- +835s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +835s tool.client_result tool="companionAct"
- +836s transcript.queued turnState="PROCESSING" round=15 transcriptLength=25
- +837s ws.send type="session_state" state="SPEAKING"
- +837s turn.state_changed state="SPEAKING"
- +841s ws.send type="session_state" state="IDLE"
- +841s turn.state_changed state="IDLE"
- +841s transcript.replay turnState="IDLE" round=15 transcriptLength=25
- +841s transcript.accepted turnState="IDLE" round=15 transcriptLength=25
- +841s ws.send type="session_state" state="LOADING"
- +841s turn.state_changed state="LOADING"
- +841s session.ending turnState="LOADING" roundNumber=15 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=511
- +841s ws.send type="session_state" state="IDLE"
- +841s turn.state_changed state="IDLE"
- +842s engine.session_finalized totalAttempts=0 accuracy=0
- +842s engine.progression_computed level=78 totalXP=7720 wordsMastered=33

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 15,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "80c6cbe0-b0b6-4506-84e5-0e22a14ffe8b",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 511
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 511,
  "rewardLogEntries": 27
}
```

## Upload
Session saved locally. Upload not configured yet.
