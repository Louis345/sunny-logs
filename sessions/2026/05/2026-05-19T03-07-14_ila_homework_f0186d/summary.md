# Sunny Session Debug Summary

sessionId: f0186df5-80e0-442b-abb3-84fa86ff89e4
date: 2026-05-19T03:07:14.265Z
endedAt: 2026-05-19T03:08:06.310Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 52045
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
- +32s turn.state_changed state="SPEAKING"
- +32s ws.send type="session_state" state="IDLE"
- +32s turn.state_changed state="IDLE"
- +32s transcript.accepted turnState="IDLE" round=2 transcriptLength=6
- +32s ws.send type="session_state" state="LOADING"
- +32s turn.state_changed state="LOADING"
- +32s ws.send type="session_state" state="PROCESSING"
- +32s turn.state_changed state="PROCESSING"
- +32s flow_game.game_state_update game="word-radar" type="game_state_update"
- +32s flow_game.game_state_update game="word-radar" type="game_state_update"
- +34s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +34s tool.client_result tool="sessionLog"
- +36s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +36s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +36s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +36s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +36s tool.client_result tool="companionAct"
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +38s ws.send type="session_state" state="SPEAKING"
- +38s turn.state_changed state="SPEAKING"
- +38s ws.send type="session_state" state="IDLE"
- +38s turn.state_changed state="IDLE"
- +38s transcript.replay turnState="IDLE" round=3 transcriptLength=4
- +38s transcript.accepted turnState="IDLE" round=3 transcriptLength=4
- +38s ws.send type="session_state" state="LOADING"
- +38s turn.state_changed state="LOADING"
- +38s ws.send type="session_state" state="PROCESSING"
- +38s turn.state_changed state="PROCESSING"
- +40s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +40s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +40s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +40s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +40s tool.client_result tool="sessionLog"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +42s tool.client_result tool="companionAct"
- +43s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +43s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +44s transcript.replay turnState="PROCESSING" round=4 transcriptLength=5
- +44s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +44s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s ws.send type="session_state" state="SPEAKING"
- +44s turn.state_changed state="SPEAKING"
- +45s ws.send type="session_state" state="IDLE"
- +45s turn.state_changed state="IDLE"
- +45s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +45s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +45s ws.send type="session_state" state="LOADING"
- +45s turn.state_changed state="LOADING"
- +45s ws.send type="session_state" state="PROCESSING"
- +45s turn.state_changed state="PROCESSING"
- +47s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +47s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +48s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +48s flow_game.game_state_update game="word-radar" type="game_state_update"
- +48s flow_game.game_state_update game="word-radar" type="game_state_update"
- +48s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +48s tool.client_result tool="companionAct"
- +49s flow_game.game_state_update game="word-radar" type="game_state_update"
- +50s flow_game.game_complete game="word-radar" type="game_complete"
- +50s ws.send type="session_state" state="SPEAKING"
- +50s turn.state_changed state="SPEAKING"
- +50s flow_game.voice_control game="word-radar" type="voice_control"
- +50s ws.send type="session_state" state="IDLE"
- +50s turn.state_changed state="IDLE"
- +50s transcript.replay turnState="IDLE" round=5 transcriptLength=5
- +50s transcript.accepted turnState="IDLE" round=5 transcriptLength=5
- +50s ws.send type="session_state" state="LOADING"
- +50s turn.state_changed state="LOADING"
- +50s ws.send type="session_state" state="PROCESSING"
- +50s turn.state_changed state="PROCESSING"
- +51s session.ending turnState="PROCESSING" roundNumber=6 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=25
- +51s ws.send type="session_state" state="IDLE"
- +51s turn.state_changed state="IDLE"
- +51s engine.session_finalized totalAttempts=12 accuracy=1
- +51s engine.progression_computed level=9 totalXP=880 wordsMastered=6

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 6,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "f0186df5-80e0-442b-abb3-84fa86ff89e4",
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
