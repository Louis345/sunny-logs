# Sunny Session Debug Summary

sessionId: faf6cbd7-cd4b-4e2f-a5a9-d4d9e55c0326
date: 2026-05-19T03:04:45.289Z
endedAt: 2026-05-19T03:05:37.694Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 52405
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
- +30s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +30s tool.client_result tool="companionAct"
- +32s ws.send type="session_state" state="SPEAKING"
- +32s turn.state_changed state="SPEAKING"
- +32s ws.send type="session_state" state="IDLE"
- +32s turn.state_changed state="IDLE"
- +32s transcript.replay turnState="IDLE" round=2 transcriptLength=6
- +32s transcript.accepted turnState="IDLE" round=2 transcriptLength=6
- +32s ws.send type="session_state" state="LOADING"
- +32s turn.state_changed state="LOADING"
- +32s ws.send type="session_state" state="PROCESSING"
- +32s turn.state_changed state="PROCESSING"
- +33s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +33s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +33s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +34s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +34s tool.client_result tool="sessionLog"
- +36s ws.send type="session_state" state="SPEAKING"
- +36s turn.state_changed state="SPEAKING"
- +36s ws.send type="session_state" state="IDLE"
- +36s turn.state_changed state="IDLE"
- +36s transcript.replay turnState="IDLE" round=3 transcriptLength=4
- +36s transcript.accepted turnState="IDLE" round=3 transcriptLength=4
- +36s ws.send type="session_state" state="LOADING"
- +36s turn.state_changed state="LOADING"
- +36s ws.send type="session_state" state="PROCESSING"
- +36s turn.state_changed state="PROCESSING"
- +36s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +36s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +37s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +39s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +39s tool.client_result tool="companionAct"
- +40s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +40s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +40s transcript.replay turnState="PROCESSING" round=4 transcriptLength=5
- +40s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +41s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +41s ws.send type="session_state" state="SPEAKING"
- +41s turn.state_changed state="SPEAKING"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s ws.send type="session_state" state="IDLE"
- +41s turn.state_changed state="IDLE"
- +41s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +41s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +41s ws.send type="session_state" state="LOADING"
- +41s turn.state_changed state="LOADING"
- +41s ws.send type="session_state" state="PROCESSING"
- +41s turn.state_changed state="PROCESSING"
- +44s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +44s tool.client_result tool="companionAct"
- +44s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +44s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +45s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +46s ws.send type="session_state" state="SPEAKING"
- +46s turn.state_changed state="SPEAKING"
- +46s ws.send type="session_state" state="IDLE"
- +46s turn.state_changed state="IDLE"
- +46s transcript.replay turnState="IDLE" round=5 transcriptLength=5
- +46s transcript.accepted turnState="IDLE" round=5 transcriptLength=5
- +46s ws.send type="session_state" state="LOADING"
- +46s turn.state_changed state="LOADING"
- +46s ws.send type="session_state" state="PROCESSING"
- +46s turn.state_changed state="PROCESSING"
- +46s flow_game.game_state_update game="word-radar" type="game_state_update"
- +47s flow_game.game_complete game="word-radar" type="game_complete"
- +48s flow_game.voice_control game="word-radar" type="voice_control"
- +48s session.ending turnState="PROCESSING" roundNumber=6 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=25
- +48s ws.send type="session_state" state="IDLE"
- +48s turn.state_changed state="IDLE"
- +48s engine.session_finalized totalAttempts=12 accuracy=1
- +48s engine.progression_computed level=5 totalXP=480 wordsMastered=5
- +49s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +49s tool.client_result tool="companionAct"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 6,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "faf6cbd7-cd4b-4e2f-a5a9-d4d9e55c0326",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
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
  "rewardLogEntries": 1
}
```

## Upload
Session saved locally. Upload not configured yet.
