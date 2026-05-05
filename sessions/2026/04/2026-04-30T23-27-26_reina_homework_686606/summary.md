# Sunny Session Debug Summary

sessionId: 68660642-d6a3-4dd5-aabd-92f732927d67
date: 2026-04-30T23:27:26.032Z
endedAt: 2026-04-30T23:28:25.360Z
child: Reina
subject: homework
mode: default
gitCommit: 484e23a
command: npm run npx
duration_ms: 59328
result: errored

## Env Flags
- TTS_ENABLED: 
- SUNNY_MODE: 
- SUNNY_CHILD: 
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: 
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +41s canvas.draw mode="worksheet_pdf"
- +41s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Reina! How's your night going?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +41s canvas.draw mode="idle"
- +41s ws.send type="session_state" state="LOADING"
- +41s turn.state_changed state="LOADING"
- +41s ws.send type="session_state" state="PROCESSING"
- +41s turn.state_changed state="PROCESSING"
- +41s ws.send type="session_state" state="SPEAKING"
- +41s turn.state_changed state="SPEAKING"
- +42s ws.send type="session_state" state="IDLE"
- +42s turn.state_changed state="IDLE"
- +42s session.started sessionType="homework" companionName="Matilda"
- +58s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +58s engine.session_finalized totalAttempts=0 accuracy=0
- +58s engine.progression_computed level=15 totalXP=1425 wordsMastered=3

## Errors
- [2026-04-30T23:28:25.357Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "68660642-d6a3-4dd5-aabd-92f732927d67",
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
  "persistedSessionData": true,
  "postSessionError": "messages: text content blocks must be non-empty",
  "shouldPersistSessionData": true,
  "conversationTurns": 0,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
