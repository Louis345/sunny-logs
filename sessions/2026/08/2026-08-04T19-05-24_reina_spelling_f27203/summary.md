# Sunny Session Debug Summary

sessionId: f27203da-157b-49a2-b5fd-954a06c87e34
date: 2026-08-04T19:05:24.173Z
endedAt: 2026-08-04T19:07:02.711Z
child: Reina
subject: spelling
mode: default
gitCommit: ec18b68
command: npm run npx
duration_ms: 98538
result: completed

## Env Flags
- TTS_ENABLED: 
- SUNNY_MODE: 
- SUNNY_CHILD: 
- SUNNY_SUBJECT: 
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: 
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false chartChildId="reina"
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +0s companion.greeting_generated source="live_homework_context" words=9
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Your first challenge is ready. Want to try it?" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s ws.send type="session_state" state="LOADING"
- +1s turn.state_changed state="LOADING"
- +1s ws.send type="session_state" state="PROCESSING"
- +1s turn.state_changed state="PROCESSING"
- +1s ws.send type="session_state" state="SPEAKING"
- +1s turn.state_changed state="SPEAKING"
- +2s ws.send type="session_state" state="IDLE"
- +2s turn.state_changed state="IDLE"
- +2s session.started sessionType="freeform" companionName="Matilda"
- +66s transcript.accepted turnState="IDLE" round=0 transcriptLength=15
- +66s ws.send type="session_state" state="LOADING"
- +66s turn.state_changed state="LOADING"
- +66s ws.send type="session_state" state="PROCESSING"
- +66s turn.state_changed state="PROCESSING"
- +70s tool.called tool="expressCompanion" argsKeys=["emote","intensity"] hasResult=true
- +70s tool.client_result tool="expressCompanion"
- +73s ws.send type="session_state" state="SPEAKING"
- +73s turn.state_changed state="SPEAKING"
- +75s ws.send type="session_state" state="IDLE"
- +75s turn.state_changed state="IDLE"
- +82s transcript.accepted turnState="IDLE" round=1 transcriptLength=96
- +82s ws.send type="session_state" state="LOADING"
- +82s turn.state_changed state="LOADING"
- +82s ws.send type="session_state" state="PROCESSING"
- +82s turn.state_changed state="PROCESSING"
- +85s ws.send type="session_state" state="SPEAKING"
- +85s turn.state_changed state="SPEAKING"
- +89s ws.send type="session_state" state="IDLE"
- +89s turn.state_changed state="IDLE"
- +92s transcript.accepted turnState="IDLE" round=2 transcriptLength=23
- +92s ws.send type="session_state" state="LOADING"
- +92s turn.state_changed state="LOADING"
- +92s ws.send type="session_state" state="PROCESSING"
- +92s turn.state_changed state="PROCESSING"
- +96s ws.send type="session_state" state="SPEAKING"
- +96s turn.state_changed state="SPEAKING"
- +96s session.ending turnState="SPEAKING" roundNumber=3 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=6
- +96s ws.send type="session_state" state="IDLE"
- +96s turn.state_changed state="IDLE"
- +96s engine.progression_computed level=78 totalXP=7755 wordsMastered=33

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 3,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "f27203da-157b-49a2-b5fd-954a06c87e34",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 6
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 6,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
