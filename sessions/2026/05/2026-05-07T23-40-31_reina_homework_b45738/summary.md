# Sunny Session Debug Summary

sessionId: b45738aa-369b-44a5-88bd-9747e508086a
date: 2026-05-07T23:40:31.440Z
endedAt: 2026-05-07T23:41:25.071Z
child: Reina
subject: homework
mode: real
gitCommit: 46d65e5
command: npm run npx
duration_ms: 53631
result: errored

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +46s canvas.draw mode="worksheet_pdf"
- +46s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Reina! How's your night going?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +46s canvas.draw mode="idle"
- +47s ws.send type="session_state" state="LOADING"
- +47s turn.state_changed state="LOADING"
- +47s ws.send type="session_state" state="PROCESSING"
- +47s turn.state_changed state="PROCESSING"
- +47s ws.send type="session_state" state="SPEAKING"
- +47s turn.state_changed state="SPEAKING"
- +48s ws.send type="session_state" state="IDLE"
- +48s turn.state_changed state="IDLE"
- +48s session.started sessionType="homework" companionName="Matilda"
- +53s transcript.accepted turnState="IDLE" round=0 transcriptLength=52
- +53s ws.send type="session_state" state="LOADING"
- +53s turn.state_changed state="LOADING"
- +53s session.ending turnState="LOADING" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +53s ws.send type="session_state" state="IDLE"
- +53s turn.state_changed state="IDLE"
- +53s engine.session_finalized totalAttempts=0 accuracy=0
- +53s engine.progression_computed level=93 totalXP=9265 wordsMastered=39

## Errors
- [2026-05-07T23:41:25.070Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "b45738aa-369b-44a5-88bd-9747e508086a",
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
