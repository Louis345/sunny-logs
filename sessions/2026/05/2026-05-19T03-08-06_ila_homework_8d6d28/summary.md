# Sunny Session Debug Summary

sessionId: 8d6d28ef-05af-4d3d-9d1f-b00f49a32296
date: 2026-05-19T03:08:06.291Z
endedAt: 2026-05-19T03:09:01.049Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 54758
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: real
- SUNNY_CHILD: demo_adaptive
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +30s turn.state_changed state="SPEAKING"
- +30s ws.send type="session_state" state="IDLE"
- +30s turn.state_changed state="IDLE"
- +31s transcript.accepted turnState="IDLE" round=2 transcriptLength=6
- +31s ws.send type="session_state" state="LOADING"
- +31s turn.state_changed state="LOADING"
- +31s ws.send type="session_state" state="PROCESSING"
- +31s turn.state_changed state="PROCESSING"
- +31s flow_game.game_state_update game="word-radar" type="game_state_update"
- +31s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +33s tool.client_result tool="companionAct"
- +35s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +35s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +35s ws.send type="session_state" state="SPEAKING"
- +35s turn.state_changed state="SPEAKING"
- +35s ws.send type="session_state" state="IDLE"
- +35s turn.state_changed state="IDLE"
- +36s transcript.accepted turnState="IDLE" round=3 transcriptLength=4
- +36s ws.send type="session_state" state="LOADING"
- +36s turn.state_changed state="LOADING"
- +36s ws.send type="session_state" state="PROCESSING"
- +36s turn.state_changed state="PROCESSING"
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +38s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +38s tool.client_result tool="companionAct"
- +39s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +39s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +39s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +39s flow_game.game_state_update game="word-radar" type="game_state_update"
- +39s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s ws.send type="session_state" state="SPEAKING"
- +40s turn.state_changed state="SPEAKING"
- +40s ws.send type="session_state" state="IDLE"
- +40s turn.state_changed state="IDLE"
- +40s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +40s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +40s ws.send type="session_state" state="LOADING"
- +40s turn.state_changed state="LOADING"
- +40s ws.send type="session_state" state="PROCESSING"
- +40s turn.state_changed state="PROCESSING"
- +42s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +42s tool.client_result tool="sessionLog"
- +43s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +43s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +43s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +43s flow_game.game_state_update game="word-radar" type="game_state_update"
- +43s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +44s tool.client_result tool="sessionLog"
- +46s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +46s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +46s transcript.replay turnState="PROCESSING" round=5 transcriptLength=5
- +46s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +46s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +47s flow_game.game_state_update game="word-radar" type="game_state_update"
- +47s flow_game.game_state_update game="word-radar" type="game_state_update"
- +47s ws.send type="session_state" state="SPEAKING"
- +47s turn.state_changed state="SPEAKING"
- +47s ws.send type="session_state" state="IDLE"
- +47s turn.state_changed state="IDLE"
- +47s transcript.replay turnState="IDLE" round=5 transcriptLength=5
- +47s transcript.accepted turnState="IDLE" round=5 transcriptLength=5
- +47s ws.send type="session_state" state="LOADING"
- +47s turn.state_changed state="LOADING"
- +47s ws.send type="session_state" state="PROCESSING"
- +47s turn.state_changed state="PROCESSING"
- +48s flow_game.game_state_update game="word-radar" type="game_state_update"
- +49s flow_game.game_complete game="word-radar" type="game_complete"
- +49s flow_game.voice_control game="word-radar" type="voice_control"
- +50s session.ending turnState="PROCESSING" roundNumber=6 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=25
- +50s ws.send type="session_state" state="IDLE"
- +50s turn.state_changed state="IDLE"
- +50s engine.session_finalized totalAttempts=12 accuracy=1
- +50s engine.progression_computed level=11 totalXP=1005 wordsMastered=6
- +50s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +50s tool.client_result tool="companionAct"
- +52s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +52s tool.client_result tool="sessionLog"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 6,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "8d6d28ef-05af-4d3d-9d1f-b00f49a32296",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 25
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 25,
  "rewardLogEntries": 2
}
```

## Upload
Session saved locally. Upload not configured yet.
