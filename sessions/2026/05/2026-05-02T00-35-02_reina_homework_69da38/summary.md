# Sunny Session Debug Summary

sessionId: 69da38b6-9cac-4fb3-b1c8-c208febedd3b
date: 2026-05-02T00:35:02.343Z
endedAt: 2026-05-02T00:37:18.635Z
child: Reina
subject: homework
mode: as-child
gitCommit: 97dd20e
command: npm run npx
duration_ms: 136292
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
- +5s canvas.draw mode="worksheet_pdf"
- +5s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Reina! How's your night going?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +5s canvas.draw mode="idle"
- +5s ws.send type="session_state" state="LOADING"
- +5s turn.state_changed state="LOADING"
- +5s ws.send type="session_state" state="PROCESSING"
- +5s turn.state_changed state="PROCESSING"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +6s ws.send type="session_state" state="IDLE"
- +6s turn.state_changed state="IDLE"
- +6s session.started sessionType="homework" companionName="Matilda"
- +69s transcript.accepted turnState="IDLE" round=0 transcriptLength=344
- +69s ws.send type="session_state" state="LOADING"
- +69s turn.state_changed state="LOADING"
- +69s ws.send type="session_state" state="IDLE"
- +69s turn.state_changed state="IDLE"
- +84s transcript.accepted turnState="IDLE" round=1 transcriptLength=446
- +84s ws.send type="session_state" state="LOADING"
- +84s turn.state_changed state="LOADING"
- +84s ws.send type="session_state" state="IDLE"
- +84s turn.state_changed state="IDLE"
- +118s transcript.replay turnState="IDLE" round=2 transcriptLength=242
- +118s transcript.accepted turnState="IDLE" round=2 transcriptLength=242
- +118s ws.send type="session_state" state="LOADING"
- +118s turn.state_changed state="LOADING"
- +118s ws.send type="session_state" state="IDLE"
- +118s turn.state_changed state="IDLE"
- +126s transcript.accepted turnState="IDLE" round=3 transcriptLength=726
- +126s ws.send type="session_state" state="LOADING"
- +126s turn.state_changed state="LOADING"
- +126s ws.send type="session_state" state="IDLE"
- +126s turn.state_changed state="IDLE"
- +136s session.ending turnState="IDLE" roundNumber=4 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 4,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "69da38b6-9cac-4fb3-b1c8-c208febedd3b",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 0
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 0,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
