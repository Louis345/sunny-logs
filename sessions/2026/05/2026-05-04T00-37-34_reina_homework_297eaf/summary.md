# Sunny Session Debug Summary

sessionId: 297eaf6c-e008-43a5-8004-2c4ba439af1b
date: 2026-05-04T00:37:34.857Z
endedAt: 2026-05-04T00:37:54.731Z
child: Reina
subject: homework
mode: as-child
gitCommit: fe66966
command: npm run npx
duration_ms: 19874
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: as-child
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +4s canvas.draw mode="worksheet_pdf"
- +4s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Reina! Good to see you — what's new?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +4s canvas.draw mode="idle"
- +5s ws.send type="session_state" state="LOADING"
- +5s turn.state_changed state="LOADING"
- +5s ws.send type="session_state" state="PROCESSING"
- +5s turn.state_changed state="PROCESSING"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +6s ws.send type="session_state" state="IDLE"
- +6s turn.state_changed state="IDLE"
- +6s session.started sessionType="homework" companionName="Matilda"
- +8s transcript.accepted turnState="IDLE" round=0 transcriptLength=3
- +8s ws.send type="session_state" state="LOADING"
- +8s turn.state_changed state="LOADING"
- +8s ws.send type="session_state" state="PROCESSING"
- +8s turn.state_changed state="PROCESSING"
- +10s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +10s tool.client_result tool="companionAct"
- +12s transcript.queued turnState="PROCESSING" round=1 transcriptLength=162
- +12s ws.send type="session_state" state="SPEAKING"
- +12s turn.state_changed state="SPEAKING"
- +20s session.ending turnState="SPEAKING" roundNumber=1 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=162 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=2
- +20s ws.send type="session_state" state="IDLE"
- +20s turn.state_changed state="IDLE"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 1,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "297eaf6c-e008-43a5-8004-2c4ba439af1b",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 2
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 2,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
