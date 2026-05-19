# Sunny Session Debug Summary

sessionId: 1b70004b-8213-4a9e-8898-d31336d2effd
date: 2026-05-19T05:19:30.067Z
endedAt: 2026-05-19T05:20:13.768Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 43701
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
- +4s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +4s tool.client_result tool="companionAct"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +5s session.started sessionType="homework" companionName="Elli"
- +6s ws.send type="session_state" state="IDLE"
- +6s turn.state_changed state="IDLE"
- +16s game_narration.speak text="Demo_Adaptive, word radar is ready." activityId="word-radar" nodeId="n-word-radar-hw-adapt-weak_performance" reason="game_mount_greeting"
- +18s flow_game.voice_control game="word-radar" type="voice_control"
- +23s flow_game.game_state_update game="word-radar" type="game_state_update"
- +25s flow_game.narration_request game="word-radar" type="narration_request" word="again" reason="word_radar_response_prompt"
- +25s game_narration.speak text="again." activityId="word-radar" reason="word_radar_response_prompt"
- +25s transcript.accepted turnState="IDLE" round=1 transcriptLength=5
- +25s ws.send type="session_state" state="LOADING"
- +25s turn.state_changed state="LOADING"
- +25s ws.send type="session_state" state="PROCESSING"
- +25s turn.state_changed state="PROCESSING"
- +26s flow_game.game_state_update game="word-radar" type="game_state_update"
- +26s flow_game.game_state_update game="word-radar" type="game_state_update"
- +27s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +27s tool.client_result tool="companionAct"
- +29s flow_game.narration_request game="word-radar" type="narration_request" word="around" reason="word_radar_response_prompt"
- +29s game_narration.speak text="around." activityId="word-radar" reason="word_radar_response_prompt"
- +29s transcript.queued turnState="PROCESSING" round=2 transcriptLength=6
- +29s flow_game.game_state_update game="word-radar" type="game_state_update"
- +29s flow_game.game_state_update game="word-radar" type="game_state_update"
- +29s ws.send type="session_state" state="SPEAKING"
- +29s turn.state_changed state="SPEAKING"
- +30s ws.send type="session_state" state="IDLE"
- +30s turn.state_changed state="IDLE"
- +30s transcript.replay turnState="IDLE" round=2 transcriptLength=6
- +30s transcript.accepted turnState="IDLE" round=2 transcriptLength=6
- +30s ws.send type="session_state" state="LOADING"
- +30s turn.state_changed state="LOADING"
- +30s ws.send type="session_state" state="PROCESSING"
- +30s turn.state_changed state="PROCESSING"
- +32s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +32s tool.client_result tool="companionAct"
- +32s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +32s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +33s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s ws.send type="session_state" state="SPEAKING"
- +33s turn.state_changed state="SPEAKING"
- +33s ws.send type="session_state" state="IDLE"
- +33s turn.state_changed state="IDLE"
- +33s transcript.replay turnState="IDLE" round=3 transcriptLength=4
- +33s transcript.accepted turnState="IDLE" round=3 transcriptLength=4
- +33s ws.send type="session_state" state="LOADING"
- +33s turn.state_changed state="LOADING"
- +33s ws.send type="session_state" state="PROCESSING"
- +33s turn.state_changed state="PROCESSING"
- +36s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +36s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +37s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +37s tool.client_result tool="companionAct"
- +39s ws.send type="session_state" state="SPEAKING"
- +39s turn.state_changed state="SPEAKING"
- +39s ws.send type="session_state" state="IDLE"
- +39s turn.state_changed state="IDLE"
- +39s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +39s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +39s ws.send type="session_state" state="LOADING"
- +39s turn.state_changed state="LOADING"
- +39s ws.send type="session_state" state="PROCESSING"
- +39s turn.state_changed state="PROCESSING"
- +40s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +40s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +40s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +43s session.ending turnState="PROCESSING" roundNumber=5 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=5 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=20
- +43s ws.send type="session_state" state="IDLE"
- +43s turn.state_changed state="IDLE"
- +43s engine.session_finalized totalAttempts=0 accuracy=0
- +43s engine.progression_computed level=8 totalXP=700 wordsMastered=5

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 5,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "1b70004b-8213-4a9e-8898-d31336d2effd",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 20
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 20,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
