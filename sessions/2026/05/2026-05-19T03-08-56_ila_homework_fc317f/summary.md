# Sunny Session Debug Summary

sessionId: fc317f2e-679d-4704-864a-1325453985da
date: 2026-05-19T03:08:56.702Z
endedAt: 2026-05-19T03:09:48.682Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 51980
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
- +25s turn.state_changed state="PROCESSING"
- +25s flow_game.game_state_update game="word-radar" type="game_state_update"
- +25s flow_game.game_state_update game="word-radar" type="game_state_update"
- +27s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +27s tool.client_result tool="companionAct"
- +28s flow_game.narration_request game="word-radar" type="narration_request" word="around" reason="word_radar_response_prompt"
- +28s game_narration.speak text="around." activityId="word-radar" reason="word_radar_response_prompt"
- +29s transcript.queued turnState="PROCESSING" round=2 transcriptLength=6
- +29s ws.send type="session_state" state="SPEAKING"
- +29s turn.state_changed state="SPEAKING"
- +29s flow_game.game_state_update game="word-radar" type="game_state_update"
- +29s flow_game.game_state_update game="word-radar" type="game_state_update"
- +29s ws.send type="session_state" state="IDLE"
- +29s turn.state_changed state="IDLE"
- +29s transcript.replay turnState="IDLE" round=2 transcriptLength=6
- +29s transcript.accepted turnState="IDLE" round=2 transcriptLength=6
- +29s ws.send type="session_state" state="LOADING"
- +29s turn.state_changed state="LOADING"
- +29s ws.send type="session_state" state="PROCESSING"
- +29s turn.state_changed state="PROCESSING"
- +31s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +31s tool.client_result tool="companionAct"
- +32s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +32s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +32s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +32s flow_game.game_state_update game="word-radar" type="game_state_update"
- +32s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +33s tool.client_result tool="sessionLog"
- +35s tool.called tool="sessionLog" argsKeys=["correct","childSaid"] hasResult=true
- +35s tool.client_result tool="sessionLog"
- +35s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +35s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +36s transcript.replay turnState="PROCESSING" round=3 transcriptLength=4
- +36s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +36s transcript.queued turnState="PROCESSING" round=3 transcriptLength=5
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s ws.send type="session_state" state="SPEAKING"
- +36s turn.state_changed state="SPEAKING"
- +37s ws.send type="session_state" state="IDLE"
- +37s turn.state_changed state="IDLE"
- +37s transcript.replay turnState="IDLE" round=3 transcriptLength=5
- +37s transcript.accepted turnState="IDLE" round=3 transcriptLength=5
- +37s ws.send type="session_state" state="LOADING"
- +37s turn.state_changed state="LOADING"
- +37s ws.send type="session_state" state="PROCESSING"
- +37s turn.state_changed state="PROCESSING"
- +39s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +39s tool.client_result tool="companionAct"
- +39s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +39s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +40s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s ws.send type="session_state" state="SPEAKING"
- +42s turn.state_changed state="SPEAKING"
- +42s ws.send type="session_state" state="IDLE"
- +42s turn.state_changed state="IDLE"
- +42s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +42s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +42s ws.send type="session_state" state="LOADING"
- +42s turn.state_changed state="LOADING"
- +42s ws.send type="session_state" state="PROCESSING"
- +42s turn.state_changed state="PROCESSING"
- +43s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +43s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +44s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +46s flow_game.game_complete game="word-radar" type="game_complete"
- +46s flow_game.voice_control game="word-radar" type="voice_control"
- +47s session.ending turnState="PROCESSING" roundNumber=5 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=5 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=23
- +47s ws.send type="session_state" state="IDLE"
- +47s turn.state_changed state="IDLE"
- +47s engine.session_finalized totalAttempts=12 accuracy=1
- +47s engine.progression_computed level=12 totalXP=1130 wordsMastered=6
- +52s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +52s tool.client_result tool="companionAct"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 5,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "fc317f2e-679d-4704-864a-1325453985da",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 23
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 23,
  "rewardLogEntries": 2
}
```

## Upload
Session saved locally. Upload not configured yet.
