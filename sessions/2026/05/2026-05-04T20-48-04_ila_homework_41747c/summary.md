# Sunny Session Debug Summary

sessionId: 41747c20-b43c-4fff-a673-dac4f98cb098
date: 2026-05-04T20:48:04.744Z
endedAt: 2026-05-04T20:49:45.998Z
child: Ila
subject: homework
mode: real
gitCommit: bf2c552
command: npm run npx
duration_ms: 101254
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Ila" companionName="Elli"
- +40s canvas.draw mode="worksheet_pdf"
- +40s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Ila! Good to see you — what's new?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +40s canvas.draw mode="idle"
- +41s ws.send type="session_state" state="LOADING"
- +41s turn.state_changed state="LOADING"
- +41s ws.send type="session_state" state="PROCESSING"
- +41s turn.state_changed state="PROCESSING"
- +41s ws.send type="session_state" state="SPEAKING"
- +41s turn.state_changed state="SPEAKING"
- +42s ws.send type="session_state" state="IDLE"
- +42s turn.state_changed state="IDLE"
- +42s session.started sessionType="homework" companionName="Elli"
- +48s ws.send type="session_state" state="LOADING"
- +48s turn.state_changed state="LOADING"
- +48s ws.send type="session_state" state="PROCESSING"
- +48s turn.state_changed state="PROCESSING"
- +50s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +50s tool.client_result tool="companionAct"
- +53s ws.send type="session_state" state="SPEAKING"
- +53s turn.state_changed state="SPEAKING"
- +60s ws.send type="session_state" state="IDLE"
- +60s turn.state_changed state="IDLE"
- +61s ws.send type="session_state" state="LOADING"
- +61s turn.state_changed state="LOADING"
- +61s ws.send type="session_state" state="PROCESSING"
- +61s turn.state_changed state="PROCESSING"
- +64s transcript.queued turnState="PROCESSING" round=0 transcriptLength=12
- +64s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +64s tool.client_result tool="companionAct"
- +68s ws.send type="session_state" state="SPEAKING"
- +68s turn.state_changed state="SPEAKING"
- +72s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +72s tool.client_result tool="companionAct"
- +74s ws.send type="session_state" state="IDLE"
- +74s turn.state_changed state="IDLE"
- +74s transcript.replay turnState="IDLE" round=0 transcriptLength=12
- +74s transcript.accepted turnState="IDLE" round=0 transcriptLength=12
- +74s ws.send type="session_state" state="LOADING"
- +74s turn.state_changed state="LOADING"
- +74s ws.send type="session_state" state="PROCESSING"
- +74s turn.state_changed state="PROCESSING"
- +75s ws.send type="session_state" state="SPEAKING"
- +75s turn.state_changed state="SPEAKING"
- +77s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +77s tool.client_result tool="companionAct"
- +82s ws.send type="session_state" state="IDLE"
- +82s turn.state_changed state="IDLE"
- +84s ws.send type="session_state" state="LOADING"
- +84s turn.state_changed state="LOADING"
- +84s ws.send type="session_state" state="PROCESSING"
- +84s turn.state_changed state="PROCESSING"
- +86s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +86s tool.client_result tool="companionAct"
- +88s ws.send type="session_state" state="SPEAKING"
- +88s turn.state_changed state="SPEAKING"
- +99s ws.send type="session_state" state="IDLE"
- +99s turn.state_changed state="IDLE"
- +101s session.ending turnState="IDLE" roundNumber=1 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=14

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 1,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "41747c20-b43c-4fff-a673-dac4f98cb098",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 14
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 14,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
