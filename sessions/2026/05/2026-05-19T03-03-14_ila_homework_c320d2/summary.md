# Sunny Session Debug Summary

sessionId: c320d25c-0848-4222-b2c3-4e3b3d3361e3
date: 2026-05-19T03:03:14.138Z
endedAt: 2026-05-19T03:04:02.849Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 48711
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
- +24s flow_game.game_state_update game="word-radar" type="game_state_update"
- +25s flow_game.narration_request game="word-radar" type="narration_request" word="again" reason="word_radar_response_prompt"
- +25s game_narration.speak text="again." activityId="word-radar" reason="word_radar_response_prompt"
- +26s transcript.accepted turnState="IDLE" round=1 transcriptLength=5
- +26s ws.send type="session_state" state="LOADING"
- +26s turn.state_changed state="LOADING"
- +26s ws.send type="session_state" state="PROCESSING"
- +26s turn.state_changed state="PROCESSING"
- +26s flow_game.game_state_update game="word-radar" type="game_state_update"
- +26s flow_game.game_state_update game="word-radar" type="game_state_update"
- +28s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +28s tool.client_result tool="companionAct"
- +29s flow_game.narration_request game="word-radar" type="narration_request" word="around" reason="word_radar_response_prompt"
- +29s game_narration.speak text="around." activityId="word-radar" reason="word_radar_response_prompt"
- +29s transcript.queued turnState="PROCESSING" round=2 transcriptLength=6
- +29s flow_game.game_state_update game="word-radar" type="game_state_update"
- +29s flow_game.game_state_update game="word-radar" type="game_state_update"
- +31s ws.send type="session_state" state="SPEAKING"
- +31s turn.state_changed state="SPEAKING"
- +31s ws.send type="session_state" state="IDLE"
- +31s turn.state_changed state="IDLE"
- +31s transcript.replay turnState="IDLE" round=2 transcriptLength=6
- +31s transcript.accepted turnState="IDLE" round=2 transcriptLength=6
- +31s ws.send type="session_state" state="LOADING"
- +31s turn.state_changed state="LOADING"
- +31s ws.send type="session_state" state="PROCESSING"
- +31s turn.state_changed state="PROCESSING"
- +32s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +32s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +33s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +33s tool.client_result tool="sessionLog"
- +33s transcript.queued turnState="PROCESSING" round=3 transcriptLength=5
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +36s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +36s transcript.replay turnState="PROCESSING" round=3 transcriptLength=5
- +36s transcript.queued turnState="PROCESSING" round=3 transcriptLength=5
- +36s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +37s tool.client_result tool="companionAct"
- +39s ws.send type="session_state" state="SPEAKING"
- +39s turn.state_changed state="SPEAKING"
- +39s ws.send type="session_state" state="IDLE"
- +39s turn.state_changed state="IDLE"
- +39s transcript.replay turnState="IDLE" round=3 transcriptLength=4
- +39s transcript.accepted turnState="IDLE" round=3 transcriptLength=4
- +39s ws.send type="session_state" state="LOADING"
- +39s turn.state_changed state="LOADING"
- +39s ws.send type="session_state" state="PROCESSING"
- +39s turn.state_changed state="PROCESSING"
- +39s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +39s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +40s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +41s tool.client_result tool="companionAct"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s flow_game.game_complete game="word-radar" type="game_complete"
- +43s ws.send type="session_state" state="SPEAKING"
- +43s turn.state_changed state="SPEAKING"
- +43s flow_game.voice_control game="word-radar" type="voice_control"
- +43s ws.send type="session_state" state="IDLE"
- +43s turn.state_changed state="IDLE"
- +43s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +43s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +43s ws.send type="session_state" state="LOADING"
- +43s turn.state_changed state="LOADING"
- +43s ws.send type="session_state" state="PROCESSING"
- +43s turn.state_changed state="PROCESSING"
- +43s session.ending turnState="PROCESSING" roundNumber=5 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=21
- +43s ws.send type="session_state" state="IDLE"
- +43s turn.state_changed state="IDLE"
- +43s engine.session_finalized totalAttempts=10 accuracy=1
- +43s engine.progression_computed level=2 totalXP=105 wordsMastered=0
- +45s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +45s tool.client_result tool="companionAct"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 5,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "c320d25c-0848-4222-b2c3-4e3b3d3361e3",
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
  "rewardLogEntries": 1
}
```

## Upload
Session saved locally. Upload not configured yet.
