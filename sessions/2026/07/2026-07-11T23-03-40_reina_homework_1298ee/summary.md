# Sunny Session Debug Summary

sessionId: 1298ee32-1260-469f-84f3-66a8562382a1
date: 2026-07-11T23:03:40.251Z
endedAt: 2026-07-11T23:05:17.204Z
child: Reina
subject: homework
mode: real
gitCommit: 6e85b75
command: npm run npx
duration_ms: 96953
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: 
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false chartChildId="reina"
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +0s companion.greeting_generated source="live_homework_context" words=9
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Your first challenge is ready. Want to try it?" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +5s ws.send type="session_state" state="LOADING"
- +5s turn.state_changed state="LOADING"
- +5s ws.send type="session_state" state="PROCESSING"
- +5s turn.state_changed state="PROCESSING"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +7s ws.send type="session_state" state="IDLE"
- +7s turn.state_changed state="IDLE"
- +7s session.started sessionType="homework" companionName="Matilda"
- +43s flow_game.attempt_event game="unknown" type="attempt_event" childId="reina" word="10"
- +49s flow_game.attempt_event game="unknown" type="attempt_event" childId="reina" word="25"
- +52s flow_game.attempt_event game="unknown" type="attempt_event" childId="reina" word="50"
- +56s flow_game.attempt_event game="unknown" type="attempt_event" childId="reina" word="14"
- +61s flow_game.attempt_event game="unknown" type="attempt_event" childId="reina" word="40"
- +69s flow_game.attempt_event game="unknown" type="attempt_event" childId="reina" word="20 pencils"
- +73s flow_game.attempt_event game="unknown" type="attempt_event" childId="reina" word="30 stars"
- +75s flow_game.game_complete game="unknown" type="game_complete" childId="reina"
- +89s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=14
- +90s engine.session_finalized totalAttempts=0 accuracy=0
- +90s engine.progression_computed level=78 totalXP=7750 wordsMastered=33

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "1298ee32-1260-469f-84f3-66a8562382a1",
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
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 14,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
