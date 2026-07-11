# Sunny Session Debug Summary

sessionId: 1e6ba248-b695-4ad1-8221-d68801c5a64b
date: 2026-07-11T18:39:19.406Z
endedAt: 2026-07-11T18:44:25.510Z
child: Reina
subject: review
mode: real
gitCommit: 6e85b75
command: npm run npx
duration_ms: 306104
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: 
- SUNNY_SUBJECT: review
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false chartChildId="reina"
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +44s canvas.draw mode="worksheet_pdf"
- +44s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +44s canvas.draw mode="idle"
- +45s session.started sessionType="freeform" companionName="Matilda"
- +283s transcript.accepted turnState="IDLE" round=0 transcriptLength=5
- +283s ws.send type="session_state" state="LOADING"
- +283s turn.state_changed state="LOADING"
- +283s ws.send type="session_state" state="PROCESSING"
- +283s turn.state_changed state="PROCESSING"
- +285s ws.send type="session_state" state="SPEAKING"
- +285s turn.state_changed state="SPEAKING"
- +285s transcript.dropped reason="assistant_owns_turn" turnState="SPEAKING" round=1 transcriptLength=17
- +287s ws.send type="session_state" state="IDLE"
- +287s turn.state_changed state="IDLE"
- +291s transcript.accepted turnState="IDLE" round=1 transcriptLength=14
- +291s ws.send type="session_state" state="LOADING"
- +291s turn.state_changed state="LOADING"
- +291s ws.send type="session_state" state="PROCESSING"
- +291s turn.state_changed state="PROCESSING"
- +293s ws.send type="session_state" state="SPEAKING"
- +293s turn.state_changed state="SPEAKING"
- +299s ws.send type="session_state" state="IDLE"
- +299s turn.state_changed state="IDLE"
- +303s session.ending turnState="IDLE" roundNumber=2 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=4
- +303s engine.session_finalized totalAttempts=0 accuracy=0
- +303s engine.progression_computed level=78 totalXP=7745 wordsMastered=33

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "1e6ba248-b695-4ad1-8221-d68801c5a64b",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 4
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 4,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
