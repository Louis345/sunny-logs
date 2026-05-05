# Sunny Session Debug Summary

sessionId: aa40913a-6927-4028-9289-925bc9c2a703
date: 2026-05-01T23:53:51.775Z
endedAt: 2026-05-02T00:00:30.138Z
child: Reina
subject: homework
mode: as-child
gitCommit: 97dd20e
command: npm run npx
duration_ms: 398363
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: as-child
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +23s ws.send type="session_state" state="PROCESSING"
- +23s turn.state_changed state="PROCESSING"
- +25s transcript.queued turnState="PROCESSING" round=3 transcriptLength=9
- +25s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +25s tool.client_result tool="companionAct"
- +26s transcript.queued turnState="PROCESSING" round=3 transcriptLength=6
- +27s ws.send type="session_state" state="SPEAKING"
- +27s turn.state_changed state="SPEAKING"
- +28s ws.send type="session_state" state="IDLE"
- +28s turn.state_changed state="IDLE"
- +28s transcript.replay turnState="IDLE" round=3 transcriptLength=6
- +28s transcript.accepted turnState="IDLE" round=3 transcriptLength=6
- +28s ws.send type="session_state" state="LOADING"
- +28s turn.state_changed state="LOADING"
- +28s ws.send type="session_state" state="PROCESSING"
- +28s turn.state_changed state="PROCESSING"
- +28s transcript.queued turnState="PROCESSING" round=4 transcriptLength=9
- +30s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +30s tool.client_result tool="companionAct"
- +32s ws.send type="session_state" state="SPEAKING"
- +32s turn.state_changed state="SPEAKING"
- +33s ws.send type="session_state" state="IDLE"
- +33s turn.state_changed state="IDLE"
- +33s transcript.replay turnState="IDLE" round=4 transcriptLength=9
- +33s transcript.accepted turnState="IDLE" round=4 transcriptLength=9
- +33s ws.send type="session_state" state="LOADING"
- +33s turn.state_changed state="LOADING"
- +33s ws.send type="session_state" state="PROCESSING"
- +33s turn.state_changed state="PROCESSING"
- +34s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +34s tool.client_result tool="companionAct"
- +36s ws.send type="session_state" state="SPEAKING"
- +36s turn.state_changed state="SPEAKING"
- +38s ws.send type="session_state" state="IDLE"
- +38s turn.state_changed state="IDLE"
- +86s transcript.accepted turnState="IDLE" round=5 transcriptLength=449
- +86s ws.send type="session_state" state="LOADING"
- +86s turn.state_changed state="LOADING"
- +86s ws.send type="session_state" state="PROCESSING"
- +86s turn.state_changed state="PROCESSING"
- +87s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +87s tool.client_result tool="companionAct"
- +90s ws.send type="session_state" state="SPEAKING"
- +90s turn.state_changed state="SPEAKING"
- +92s ws.send type="session_state" state="IDLE"
- +92s turn.state_changed state="IDLE"
- +206s transcript.accepted turnState="IDLE" round=6 transcriptLength=41
- +206s ws.send type="session_state" state="LOADING"
- +206s turn.state_changed state="LOADING"
- +206s ws.send type="session_state" state="PROCESSING"
- +206s turn.state_changed state="PROCESSING"
- +208s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +208s tool.client_result tool="companionAct"
- +210s ws.send type="session_state" state="SPEAKING"
- +210s turn.state_changed state="SPEAKING"
- +212s ws.send type="session_state" state="IDLE"
- +212s turn.state_changed state="IDLE"
- +281s transcript.accepted turnState="IDLE" round=7 transcriptLength=13
- +281s ws.send type="session_state" state="LOADING"
- +281s turn.state_changed state="LOADING"
- +281s ws.send type="session_state" state="PROCESSING"
- +281s turn.state_changed state="PROCESSING"
- +282s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +282s tool.client_result tool="sessionStatus"
- +284s ws.send type="session_state" state="SPEAKING"
- +284s turn.state_changed state="SPEAKING"
- +286s ws.send type="session_state" state="IDLE"
- +286s turn.state_changed state="IDLE"
- +361s transcript.accepted turnState="IDLE" round=8 transcriptLength=6
- +361s ws.send type="session_state" state="LOADING"
- +361s turn.state_changed state="LOADING"
- +361s ws.send type="session_state" state="PROCESSING"
- +361s turn.state_changed state="PROCESSING"
- +363s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +363s tool.client_result tool="companionAct"
- +365s ws.send type="session_state" state="SPEAKING"
- +365s turn.state_changed state="SPEAKING"
- +366s ws.send type="session_state" state="IDLE"
- +366s turn.state_changed state="IDLE"
- +398s session.ending turnState="IDLE" roundNumber=9 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=18

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 9,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "aa40913a-6927-4028-9289-925bc9c2a703",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 18
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 18,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
