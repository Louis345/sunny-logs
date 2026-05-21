# Sunny Session Debug Summary

sessionId: c6e41b03-2d63-43e2-81c7-193ac98d059f
date: 2026-05-21T23:05:36.356Z
endedAt: 2026-05-21T23:06:28.546Z
child: Reina
subject: homework
mode: real
gitCommit: cc49f2b
command: npm run npx
duration_ms: 52190
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
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s transcript.replay turnState="IDLE" round=0 transcriptLength=949
- +1s transcript.accepted turnState="IDLE" round=0 transcriptLength=949
- +1s ws.send type="session_state" state="LOADING"
- +1s turn.state_changed state="LOADING"
- +1s ws.send type="session_state" state="PROCESSING"
- +1s turn.state_changed state="PROCESSING"
- +3s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +3s tool.client_result tool="companionAct"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +6s session.started sessionType="homework" companionName="Matilda"
- +10s ws.send type="session_state" state="IDLE"
- +10s turn.state_changed state="IDLE"
- +22s transcript.accepted turnState="IDLE" round=1 transcriptLength=5
- +22s ws.send type="session_state" state="LOADING"
- +22s turn.state_changed state="LOADING"
- +22s ws.send type="session_state" state="PROCESSING"
- +22s turn.state_changed state="PROCESSING"
- +24s tool.called tool="launchGame" argsKeys=["name","type"] hasResult=true
- +24s tool.client_result tool="launchGame"
- +26s tool.called tool="launchGame" argsKeys=["name","type"] hasResult=true
- +26s tool.client_result tool="launchGame"
- +28s tool.called tool="launchGame" argsKeys=["name","type","word"] hasResult=true
- +28s tool.client_result tool="launchGame"
- +28s transcript.queued turnState="PROCESSING" round=2 transcriptLength=45
- +29s tool.called tool="launchGame" argsKeys=["name","type","word"] hasResult=true
- +29s tool.client_result tool="launchGame"
- +29s canvas.draw mode="spell-check" canvasRevision=1
- +31s flow_game.voice_control game="word-radar" type="voice_control"
- +31s ws.send type="session_state" state="SPEAKING"
- +31s turn.state_changed state="SPEAKING"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s ws.send type="session_state" state="IDLE"
- +36s turn.state_changed state="IDLE"
- +36s transcript.replay turnState="IDLE" round=2 transcriptLength=45
- +36s transcript.accepted turnState="IDLE" round=2 transcriptLength=45
- +36s ws.send type="session_state" state="LOADING"
- +36s turn.state_changed state="LOADING"
- +36s ws.send type="session_state" state="PROCESSING"
- +36s turn.state_changed state="PROCESSING"
- +38s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +38s tool.client_result tool="companionAct"
- +39s flow_game.narration_request game="word-radar" type="narration_request" word="among" reason="word_radar_mic_click"
- +39s game_narration.speak text="among." activityId="word-radar" reason="word_radar_mic_click"
- +39s flow_game.narration_request game="word-radar" type="narration_request" word="among" reason="word_radar_mic_click"
- +40s game_narration.playback_done text="among." activityId="word-radar" reason="word_radar_mic_click"
- +40s ws.send type="session_state" state="SPEAKING"
- +40s turn.state_changed state="SPEAKING"
- +40s ws.send type="session_state" state="IDLE"
- +40s turn.state_changed state="IDLE"
- +42s flow_game.narration_request game="word-radar" type="narration_request" word="among" reason="word_radar_mic_click"
- +42s game_narration.speak text="among." activityId="word-radar" reason="word_radar_mic_click"
- +43s game_narration.playback_done text="among." activityId="word-radar" reason="word_radar_mic_click"
- +45s flow_game.narration_request game="word-radar" type="narration_request" word="among" reason="word_radar_mic_click"
- +45s game_narration.speak text="among." activityId="word-radar" reason="word_radar_mic_click"
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +46s game_narration.playback_done text="among." activityId="word-radar" reason="word_radar_mic_click"
- +46s flow_game.voice_control game="word-radar" type="voice_control"
- +51s session.ending turnState="IDLE" roundNumber=3 isEnding=true childName="Reina" canvasMode="spell-check" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=true activeSpellCheckWord="sign" tts="on" conversationTurns=6
- +51s engine.session_finalized totalAttempts=0 accuracy=0
- +51s engine.progression_computed level=92 totalXP=9105 wordsMastered=41

## Activity Evidence
- activityReadings: 7
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 3,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "c6e41b03-2d63-43e2-81c7-193ac98d059f",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 6
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 6,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
