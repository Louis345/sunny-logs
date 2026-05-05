# Sunny Session Debug Summary

sessionId: 5165ada8-4676-4b52-85e2-2ba16014519c
date: 2026-05-04T20:57:46.221Z
endedAt: 2026-05-04T20:58:48.821Z
child: Ila
subject: homework
mode: real
gitCommit: bf2c552
command: npm run npx
duration_ms: 62600
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
- +34s ws.send type="session_state" state="LOADING"
- +34s turn.state_changed state="LOADING"
- +34s ws.send type="session_state" state="PROCESSING"
- +34s turn.state_changed state="PROCESSING"
- +35s ws.send type="session_state" state="SPEAKING"
- +35s turn.state_changed state="SPEAKING"
- +35s ws.send type="session_state" state="IDLE"
- +35s turn.state_changed state="IDLE"
- +38s ws.send type="session_state" state="LOADING"
- +38s turn.state_changed state="LOADING"
- +38s ws.send type="session_state" state="PROCESSING"
- +38s turn.state_changed state="PROCESSING"
- +38s ws.send type="session_state" state="SPEAKING"
- +38s turn.state_changed state="SPEAKING"
- +38s ws.send type="session_state" state="IDLE"
- +38s turn.state_changed state="IDLE"
- +42s canvas.draw mode="worksheet_pdf"
- +42s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Ila! Good to see you — what's new?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +42s canvas.draw mode="idle"
- +42s ws.send type="session_state" state="LOADING"
- +42s turn.state_changed state="LOADING"
- +42s ws.send type="session_state" state="PROCESSING"
- +42s turn.state_changed state="PROCESSING"
- +42s ws.send type="session_state" state="SPEAKING"
- +42s turn.state_changed state="SPEAKING"
- +43s ws.send type="session_state" state="IDLE"
- +43s turn.state_changed state="IDLE"
- +43s session.started sessionType="homework" companionName="Elli"
- +44s ws.send type="session_state" state="LOADING"
- +44s turn.state_changed state="LOADING"
- +44s ws.send type="session_state" state="PROCESSING"
- +44s turn.state_changed state="PROCESSING"
- +44s ws.send type="session_state" state="IDLE"
- +44s turn.state_changed state="IDLE"
- +44s turn.barge_in stateBefore="PROCESSING" turnState="IDLE" round=0 tts="on"
- +44s canvas.draw mode="idle"
- +47s ws.send type="session_state" state="LOADING"
- +47s turn.state_changed state="LOADING"
- +47s ws.send type="session_state" state="PROCESSING"
- +47s turn.state_changed state="PROCESSING"
- +50s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +50s tool.client_result tool="companionAct"
- +52s ws.send type="session_state" state="SPEAKING"
- +52s turn.state_changed state="SPEAKING"
- +56s ws.send type="session_state" state="IDLE"
- +56s turn.state_changed state="IDLE"
- +56s ws.send type="session_state" state="LOADING"
- +56s turn.state_changed state="LOADING"
- +56s ws.send type="session_state" state="PROCESSING"
- +56s turn.state_changed state="PROCESSING"
- +58s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +58s tool.client_result tool="companionAct"
- +60s ws.send type="session_state" state="SPEAKING"
- +60s turn.state_changed state="SPEAKING"
- +63s session.ending turnState="SPEAKING" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=15
- +63s ws.send type="session_state" state="IDLE"
- +63s turn.state_changed state="IDLE"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "5165ada8-4676-4b52-85e2-2ba16014519c",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 15
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 15,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
