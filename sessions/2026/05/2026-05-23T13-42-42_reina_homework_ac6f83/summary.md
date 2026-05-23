# Sunny Session Debug Summary

sessionId: ac6f83c3-a824-4498-b725-aaf45deebbd4
date: 2026-05-23T13:42:42.295Z
endedAt: 2026-05-23T13:43:15.909Z
child: Reina
subject: homework
mode: real
gitCommit: cc49f2b
command: npm run npx
duration_ms: 33614
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
- +3s transcript.accepted turnState="IDLE" round=0 transcriptLength=36
- +3s ws.send type="session_state" state="LOADING"
- +3s turn.state_changed state="LOADING"
- +3s ws.send type="session_state" state="PROCESSING"
- +3s turn.state_changed state="PROCESSING"
- +5s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +5s tool.client_result tool="sessionStatus"
- +7s tool.called tool="launchGame" argsKeys=["name","type","word"] hasResult=true
- +7s tool.client_result tool="launchGame"
- +7s canvas.draw mode="spell-check" canvasRevision=1
- +9s transcript.queued turnState="PROCESSING" round=1 transcriptLength=10
- +9s ws.send type="session_state" state="SPEAKING"
- +9s turn.state_changed state="SPEAKING"
- +11s flow_game.voice_control game="word-radar" type="voice_control"
- +13s flow_game.game_state_update game="word-radar" type="game_state_update"
- +13s ws.send type="session_state" state="IDLE"
- +13s turn.state_changed state="IDLE"
- +13s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=1 tts="on"
- +17s flow_game.game_state_update game="word-radar" type="game_state_update"
- +18s flow_game.game_state_update game="word-radar" type="game_state_update"
- +18s flow_game.game_state_update game="word-radar" type="game_state_update"
- +20s flow_game.game_state_update game="word-radar" type="game_state_update"
- +21s flow_game.game_state_update game="word-radar" type="game_state_update"
- +21s flow_game.game_state_update game="word-radar" type="game_state_update"
- +23s flow_game.game_state_update game="word-radar" type="game_state_update"
- +24s flow_game.game_state_update game="word-radar" type="game_state_update"
- +24s flow_game.game_state_update game="word-radar" type="game_state_update"
- +24s flow_game.game_state_update game="word-radar" type="game_state_update"
- +25s transcript.suppressed reason="word-radar_active_game" turnState="IDLE" round=1 transcriptLength=4
- +29s session.ending turnState="IDLE" roundNumber=1 isEnding=true childName="Reina" canvasMode="spell-check" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=true activeSpellCheckWord="sign" tts="on" conversationTurns=2
- +29s engine.session_finalized totalAttempts=0 accuracy=0
- +29s engine.progression_computed level=111 totalXP=11075 wordsMastered=49

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
  "roundNumber": 1,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "ac6f83c3-a824-4498-b725-aaf45deebbd4",
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
