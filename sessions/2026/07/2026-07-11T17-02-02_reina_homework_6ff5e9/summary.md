# Sunny Session Debug Summary

sessionId: 6ff5e90f-2382-42de-966d-6ac208c3b76d
date: 2026-07-11T17:02:02.658Z
endedAt: 2026-07-11T17:02:11.255Z
child: Reina
subject: homework
mode: real
gitCommit: 6e85b75
command: npm run npx
duration_ms: 8597
result: errored

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
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s session.started sessionType="homework" companionName="Matilda"
- +5s flow_game.voice_control game="word-radar" type="voice_control" childId="reina"
- +5s flow_game.game_state_update game="word-radar" type="game_state_update" activityId="word-radar" childId="reina"
- +6s flow_game.game_state_update game="word-radar" type="game_state_update" childId="reina"
- +6s flow_game.game_state_update game="word-radar" type="game_state_update" activityId="word-radar" childId="reina"
- +8s flow_game.game_state_update game="word-radar" type="game_state_update" activityId="word-radar" childId="reina"
- +8s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +8s engine.session_finalized totalAttempts=0 accuracy=0
- +8s engine.progression_computed level=78 totalXP=7735 wordsMastered=33

## Errors
- [2026-07-11T17:02:11.255Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "6ff5e90f-2382-42de-966d-6ac208c3b76d",
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
