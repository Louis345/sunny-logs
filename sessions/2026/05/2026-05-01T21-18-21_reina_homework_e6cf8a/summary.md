# Sunny Session Debug Summary

sessionId: e6cf8aed-8d2f-4aba-9d4b-a629d8743171
date: 2026-05-01T21:18:21.639Z
endedAt: 2026-05-01T21:32:14.838Z
child: Reina
subject: homework
mode: as-child
gitCommit: 97dd20e
command: npm run npx
duration_ms: 833199
result: completed

## Env Flags
- TTS_ENABLED: 
- SUNNY_MODE: as-child
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +593s turn.state_changed state="PROCESSING"
- +596s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +596s tool.client_result tool="companionAct"
- +598s ws.send type="session_state" state="SPEAKING"
- +598s turn.state_changed state="SPEAKING"
- +604s ws.send type="session_state" state="IDLE"
- +604s turn.state_changed state="IDLE"
- +652s transcript.accepted turnState="IDLE" round=8 transcriptLength=40
- +652s ws.send type="session_state" state="LOADING"
- +652s turn.state_changed state="LOADING"
- +652s ws.send type="session_state" state="PROCESSING"
- +652s turn.state_changed state="PROCESSING"
- +654s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +654s tool.client_result tool="sessionStatus"
- +656s ws.send type="session_state" state="SPEAKING"
- +656s turn.state_changed state="SPEAKING"
- +665s ws.send type="session_state" state="IDLE"
- +665s turn.state_changed state="IDLE"
- +681s transcript.accepted turnState="IDLE" round=9 transcriptLength=115
- +681s ws.send type="session_state" state="LOADING"
- +681s turn.state_changed state="LOADING"
- +681s ws.send type="session_state" state="PROCESSING"
- +681s turn.state_changed state="PROCESSING"
- +682s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +682s tool.client_result tool="companionAct"
- +684s ws.send type="session_state" state="SPEAKING"
- +684s turn.state_changed state="SPEAKING"
- +691s ws.send type="session_state" state="IDLE"
- +691s turn.state_changed state="IDLE"
- +691s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=10 tts="on"
- +691s canvas.draw mode="idle"
- +692s transcript.accepted turnState="IDLE" round=10 transcriptLength=115
- +692s ws.send type="session_state" state="LOADING"
- +692s turn.state_changed state="LOADING"
- +692s ws.send type="session_state" state="PROCESSING"
- +692s turn.state_changed state="PROCESSING"
- +693s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +693s tool.client_result tool="companionAct"
- +696s ws.send type="session_state" state="SPEAKING"
- +696s turn.state_changed state="SPEAKING"
- +705s ws.send type="session_state" state="IDLE"
- +705s turn.state_changed state="IDLE"
- +748s transcript.accepted turnState="IDLE" round=11 transcriptLength=8
- +748s ws.send type="session_state" state="LOADING"
- +748s turn.state_changed state="LOADING"
- +748s ws.send type="session_state" state="PROCESSING"
- +748s turn.state_changed state="PROCESSING"
- +749s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +749s tool.client_result tool="companionAct"
- +752s ws.send type="session_state" state="SPEAKING"
- +752s turn.state_changed state="SPEAKING"
- +760s ws.send type="session_state" state="IDLE"
- +760s turn.state_changed state="IDLE"
- +799s transcript.accepted turnState="IDLE" round=12 transcriptLength=134
- +799s ws.send type="session_state" state="LOADING"
- +799s turn.state_changed state="LOADING"
- +799s ws.send type="session_state" state="PROCESSING"
- +799s turn.state_changed state="PROCESSING"
- +801s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +801s tool.client_result tool="companionAct"
- +803s transcript.queued turnState="PROCESSING" round=13 transcriptLength=9
- +804s ws.send type="session_state" state="SPEAKING"
- +804s turn.state_changed state="SPEAKING"
- +812s ws.send type="session_state" state="IDLE"
- +812s turn.state_changed state="IDLE"
- +812s transcript.replay turnState="IDLE" round=13 transcriptLength=9
- +812s transcript.accepted turnState="IDLE" round=13 transcriptLength=9
- +812s ws.send type="session_state" state="LOADING"
- +812s turn.state_changed state="LOADING"
- +812s ws.send type="session_state" state="PROCESSING"
- +812s turn.state_changed state="PROCESSING"
- +814s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +814s tool.client_result tool="sessionStatus"
- +817s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +817s tool.client_result tool="companionAct"
- +818s ws.send type="session_state" state="SPEAKING"
- +818s turn.state_changed state="SPEAKING"
- +827s ws.send type="session_state" state="IDLE"
- +827s turn.state_changed state="IDLE"
- +833s session.ending turnState="IDLE" roundNumber=14 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=29

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 14,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "e6cf8aed-8d2f-4aba-9d4b-a629d8743171",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 29
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 29,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
