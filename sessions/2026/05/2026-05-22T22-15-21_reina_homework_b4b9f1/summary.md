# Sunny Session Debug Summary

sessionId: b4b9f196-ad14-4e21-a51f-c418a58f29b0
date: 2026-05-22T22:15:21.259Z
endedAt: 2026-05-22T22:18:05.171Z
child: Reina
subject: homework
mode: real
gitCommit: cc49f2b
command: npm run npx
duration_ms: 163912
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
- +110s turn.state_changed state="IDLE"
- +113s flow_game.game_state_update game="word-radar" type="game_state_update"
- +116s flow_game.narration_request game="word-radar" type="narration_request" word="include" reason="word_radar_mic_click"
- +116s game_narration.speak text="include." activityId="word-radar" reason="word_radar_mic_click"
- +117s game_narration.playback_done text="include." activityId="word-radar" reason="word_radar_mic_click"
- +123s flow_game.game_state_update game="word-radar" type="game_state_update"
- +124s transcript.accepted turnState="IDLE" round=6 transcriptLength=19
- +124s ws.send type="session_state" state="LOADING"
- +124s turn.state_changed state="LOADING"
- +124s ws.send type="session_state" state="PROCESSING"
- +124s turn.state_changed state="PROCESSING"
- +124s flow_game.game_state_update game="word-radar" type="game_state_update"
- +125s flow_game.game_state_update game="word-radar" type="game_state_update"
- +125s flow_game.game_state_update game="word-radar" type="game_state_update"
- +125s flow_game.game_state_update game="word-radar" type="game_state_update"
- +125s flow_game.game_state_update game="word-radar" type="game_state_update"
- +125s flow_game.game_state_update game="word-radar" type="game_state_update"
- +127s tool.called tool="sessionLog" argsKeys=["correct","childSaid","observation"] hasResult=true
- +127s tool.client_result tool="sessionLog"
- +128s flow_game.game_state_update game="word-radar" type="game_state_update"
- +129s flow_game.narration_request game="word-radar" type="narration_request" word="nothing" reason="word_radar_mic_click"
- +129s game_narration.speak text="nothing." activityId="word-radar" reason="word_radar_mic_click"
- +129s transcript.queued turnState="PROCESSING" round=7 transcriptLength=45
- +129s ws.send type="session_state" state="SPEAKING"
- +129s turn.state_changed state="SPEAKING"
- +130s game_narration.playback_done text="nothing." activityId="word-radar" reason="word_radar_mic_click"
- +130s ws.send type="session_state" state="IDLE"
- +130s turn.state_changed state="IDLE"
- +130s transcript.replay turnState="IDLE" round=7 transcriptLength=45
- +130s transcript.accepted turnState="IDLE" round=7 transcriptLength=45
- +130s ws.send type="session_state" state="LOADING"
- +130s turn.state_changed state="LOADING"
- +130s ws.send type="session_state" state="PROCESSING"
- +130s turn.state_changed state="PROCESSING"
- +131s flow_game.game_state_update game="word-radar" type="game_state_update"
- +132s flow_game.game_state_update game="word-radar" type="game_state_update"
- +132s flow_game.game_state_update game="word-radar" type="game_state_update"
- +132s flow_game.game_state_update game="word-radar" type="game_state_update"
- +132s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +132s tool.client_result tool="companionAct"
- +132s flow_game.game_state_update game="word-radar" type="game_state_update"
- +132s flow_game.game_state_update game="word-radar" type="game_state_update"
- +133s transcript.queued turnState="PROCESSING" round=8 transcriptLength=14
- +135s ws.send type="session_state" state="SPEAKING"
- +135s turn.state_changed state="SPEAKING"
- +136s flow_game.narration_request game="word-radar" type="narration_request" word="special" reason="word_radar_mic_click"
- +136s game_narration.speak text="special." activityId="word-radar" reason="word_radar_mic_click"
- +138s game_narration.playback_done text="special." activityId="word-radar" reason="word_radar_mic_click"
- +141s flow_game.narration_request game="word-radar" type="narration_request" word="special" reason="word_radar_mic_click"
- +141s game_narration.speak text="special." activityId="word-radar" reason="word_radar_mic_click"
- +142s game_narration.playback_done text="special." activityId="word-radar" reason="word_radar_mic_click"
- +145s flow_game.game_state_update game="word-radar" type="game_state_update"
- +145s ws.send type="session_state" state="IDLE"
- +145s turn.state_changed state="IDLE"
- +145s transcript.replay turnState="IDLE" round=8 transcriptLength=14
- +145s transcript.accepted turnState="IDLE" round=8 transcriptLength=14
- +145s ws.send type="session_state" state="LOADING"
- +145s turn.state_changed state="LOADING"
- +145s ws.send type="session_state" state="PROCESSING"
- +145s turn.state_changed state="PROCESSING"
- +149s flow_game.voice_control game="word-radar" type="voice_control"
- +149s tool.called tool="sessionLog" argsKeys=["correct","word","observation"] hasResult=false
- +149s tool.client_result tool="sessionLog"
- +152s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word","observation"] hasResult=true
- +152s tool.client_result tool="sessionLog"
- +153s transcript.queued turnState="PROCESSING" round=9 transcriptLength=44
- +154s ws.send type="session_state" state="SPEAKING"
- +154s turn.state_changed state="SPEAKING"
- +158s ws.send type="session_state" state="IDLE"
- +158s turn.state_changed state="IDLE"
- +158s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=9 tts="on"
- +158s canvas.draw mode="idle"
- +159s transcript.accepted turnState="IDLE" round=9 transcriptLength=24
- +159s ws.send type="session_state" state="LOADING"
- +159s turn.state_changed state="LOADING"
- +159s session.ending turnState="LOADING" roundNumber=9 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=27
- +159s ws.send type="session_state" state="IDLE"
- +159s turn.state_changed state="IDLE"
- +159s engine.session_finalized totalAttempts=4 accuracy=0
- +159s engine.progression_computed level=102 totalXP=10195 wordsMastered=41

## Activity Evidence
- activityReadings: 17
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 9,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "b4b9f196-ad14-4e21-a51f-c418a58f29b0",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 27
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 27,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
