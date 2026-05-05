# Sunny Session Debug Summary

sessionId: 97238901-a6d3-4b7d-a1f8-b166caee46e1
date: 2026-05-04T21:17:04.056Z
endedAt: 2026-05-04T21:28:03.852Z
child: Reina
subject: homework
mode: as-child
gitCommit: 8f8e5f8
command: npm run npx
duration_ms: 659796
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: as-child
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +511s transcript.queued turnState="PROCESSING" round=25 transcriptLength=33
- +513s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +513s tool.client_result tool="companionAct"
- +515s ws.send type="session_state" state="SPEAKING"
- +515s turn.state_changed state="SPEAKING"
- +517s ws.send type="session_state" state="IDLE"
- +517s turn.state_changed state="IDLE"
- +517s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=25 tts="on"
- +517s canvas.draw mode="idle"
- +518s transcript.accepted turnState="IDLE" round=25 transcriptLength=41
- +518s ws.send type="session_state" state="LOADING"
- +518s turn.state_changed state="LOADING"
- +518s ws.send type="session_state" state="PROCESSING"
- +518s turn.state_changed state="PROCESSING"
- +520s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +520s tool.client_result tool="companionAct"
- +522s ws.send type="session_state" state="SPEAKING"
- +522s turn.state_changed state="SPEAKING"
- +530s transcript.dropped reason="assistant_owns_turn" turnState="SPEAKING" round=26 transcriptLength=162
- +532s ws.send type="session_state" state="IDLE"
- +532s turn.state_changed state="IDLE"
- +532s transcript.accepted turnState="IDLE" round=26 transcriptLength=34
- +532s ws.send type="session_state" state="LOADING"
- +532s turn.state_changed state="LOADING"
- +532s ws.send type="session_state" state="PROCESSING"
- +532s turn.state_changed state="PROCESSING"
- +533s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +533s tool.client_result tool="sessionStatus"
- +536s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +536s tool.client_result tool="companionAct"
- +538s transcript.queued turnState="PROCESSING" round=27 transcriptLength=41
- +539s ws.send type="session_state" state="SPEAKING"
- +539s turn.state_changed state="SPEAKING"
- +550s ws.send type="session_state" state="IDLE"
- +550s turn.state_changed state="IDLE"
- +550s transcript.replay turnState="IDLE" round=27 transcriptLength=41
- +550s transcript.accepted turnState="IDLE" round=27 transcriptLength=41
- +550s ws.send type="session_state" state="LOADING"
- +550s turn.state_changed state="LOADING"
- +550s ws.send type="session_state" state="PROCESSING"
- +550s turn.state_changed state="PROCESSING"
- +551s transcript.queued turnState="PROCESSING" round=28 transcriptLength=21
- +552s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +552s tool.client_result tool="companionAct"
- +555s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +555s tool.client_result tool="sessionStatus"
- +558s ws.send type="session_state" state="SPEAKING"
- +558s turn.state_changed state="SPEAKING"
- +559s ws.send type="session_state" state="IDLE"
- +559s turn.state_changed state="IDLE"
- +559s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=28 tts="on"
- +559s canvas.draw mode="idle"
- +560s transcript.accepted turnState="IDLE" round=28 transcriptLength=72
- +560s ws.send type="session_state" state="LOADING"
- +560s turn.state_changed state="LOADING"
- +560s ws.send type="session_state" state="PROCESSING"
- +560s turn.state_changed state="PROCESSING"
- +563s tool.called tool="sessionLog" argsKeys=["correct","observation"] hasResult=false
- +563s tool.client_result tool="sessionLog"
- +565s tool.called tool="sessionLog" argsKeys=["correct","childSaid","observation"] hasResult=true
- +565s tool.client_result tool="sessionLog"
- +568s ws.send type="session_state" state="SPEAKING"
- +568s turn.state_changed state="SPEAKING"
- +581s ws.send type="session_state" state="IDLE"
- +581s turn.state_changed state="IDLE"
- +648s transcript.accepted turnState="IDLE" round=29 transcriptLength=33
- +648s ws.send type="session_state" state="LOADING"
- +648s turn.state_changed state="LOADING"
- +648s ws.send type="session_state" state="PROCESSING"
- +648s turn.state_changed state="PROCESSING"
- +648s transcript.queued turnState="PROCESSING" round=30 transcriptLength=8
- +650s tool.called tool="sessionLog" argsKeys=["correct","observation"] hasResult=false
- +650s tool.client_result tool="sessionLog"
- +652s tool.called tool="sessionLog" argsKeys=["correct","childSaid","observation"] hasResult=true
- +652s tool.client_result tool="sessionLog"
- +655s ws.send type="session_state" state="SPEAKING"
- +655s turn.state_changed state="SPEAKING"
- +660s session.ending turnState="SPEAKING" roundNumber=30 isEnding=true childName="Reina" canvasMode="karaoke" activeGame=null pendingTranscript=true pendingTranscriptLength=8 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=170
- +660s ws.send type="session_state" state="IDLE"
- +660s turn.state_changed state="IDLE"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 30,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "97238901-a6d3-4b7d-a1f8-b166caee46e1",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 170
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 170,
  "rewardLogEntries": 4
}
```

## Upload
Session saved locally. Upload not configured yet.
