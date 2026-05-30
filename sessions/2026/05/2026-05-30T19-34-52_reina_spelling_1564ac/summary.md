# Sunny Session Debug Summary

sessionId: 1564ac3d-740c-41d7-a3e6-6735c2bf921a
date: 2026-05-30T19:34:52.486Z
endedAt: 2026-05-30T19:38:04.496Z
child: Reina
subject: spelling
mode: default
gitCommit: 034f2a3
command: /Users/jamaltaylor/.cache/codex-runtimes/codex-primary-runtime/dependencies/node/bin/node /Users/jamaltaylor/Development/sunny/src/server.ts --serve-static
duration_ms: 192010
result: errored

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: 
- SUNNY_CHILD: 
- SUNNY_SUBJECT: 
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: 
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false chartChildId="reina"
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s session.started sessionType="spelling" companionName="Matilda"
- +10s flow_game.game_state_update game="adventure-map" type="game_state_update"
- +191s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=0
- +191s engine.session_finalized totalAttempts=0 accuracy=0
- +191s engine.progression_computed level=117 totalXP=11605 wordsMastered=53

## Activity Evidence
- activityReadings: 0
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- [2026-05-30T19:38:04.496Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "1564ac3d-740c-41d7-a3e6-6735c2bf921a",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
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
