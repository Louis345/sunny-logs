# Sunny Session Debug Summary

sessionId: 9eb26743-7e19-49af-bbc2-ebcd5648d737
date: 2026-05-23T14:33:14.716Z
endedAt: 2026-05-23T14:33:55.785Z
child: Reina
subject: homework
mode: real
gitCommit: cc49f2b
command: npm run npx
duration_ms: 41069
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: reina
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
- +12s flow_game.voice_control game="word-radar" type="voice_control"
- +12s transcript.suppressed reason="word-radar_active_game" turnState="IDLE" round=0 transcriptLength=64
- +13s flow_game.game_state_update game="word-radar" type="game_state_update"
- +19s flow_game.game_state_update game="word-radar" type="game_state_update"
- +19s flow_game.game_state_update game="word-radar" type="game_state_update"
- +20s flow_game.game_state_update game="word-radar" type="game_state_update"
- +20s flow_game.game_state_update game="word-radar" type="game_state_update"
- +20s flow_game.game_state_update game="word-radar" type="game_state_update"
- +20s flow_game.game_state_update game="word-radar" type="game_state_update"
- +21s transcript.suppressed reason="word-radar_active_game" turnState="IDLE" round=0 transcriptLength=10
- +22s transcript.suppressed reason="word-radar_active_game" turnState="IDLE" round=0 transcriptLength=16
- +24s flow_game.game_state_update game="word-radar" type="game_state_update"
- +25s flow_game.game_state_update game="word-radar" type="game_state_update"
- +25s flow_game.game_state_update game="word-radar" type="game_state_update"
- +26s flow_game.game_state_update game="word-radar" type="game_state_update"
- +27s flow_game.game_state_update game="word-radar" type="game_state_update"
- +28s flow_game.game_state_update game="word-radar" type="game_state_update"
- +29s flow_game.game_state_update game="word-radar" type="game_state_update"
- +30s flow_game.game_state_update game="word-radar" type="game_state_update"
- +30s flow_game.game_state_update game="word-radar" type="game_state_update"
- +31s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +34s transcript.suppressed reason="word-radar_active_game" turnState="IDLE" round=0 transcriptLength=18
- +35s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=2
- +35s engine.session_finalized totalAttempts=0 accuracy=0
- +35s engine.progression_computed level=111 totalXP=11085 wordsMastered=49

## Activity Evidence
- activityReadings: 1
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "9eb26743-7e19-49af-bbc2-ebcd5648d737",
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
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 2,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
