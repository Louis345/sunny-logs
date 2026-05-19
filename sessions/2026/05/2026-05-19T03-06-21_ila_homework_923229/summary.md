# Sunny Session Debug Summary

sessionId: 9232292e-3f23-46cf-ad75-d39c9b924fab
date: 2026-05-19T03:06:21.996Z
endedAt: 2026-05-19T03:07:18.468Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 56472
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
- +27s transcript.accepted turnState="IDLE" round=1 transcriptLength=5
- +27s ws.send type="session_state" state="LOADING"
- +27s turn.state_changed state="LOADING"
- +27s ws.send type="session_state" state="PROCESSING"
- +27s turn.state_changed state="PROCESSING"
- +27s flow_game.game_state_update game="word-radar" type="game_state_update"
- +27s flow_game.game_state_update game="word-radar" type="game_state_update"
- +29s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +29s tool.client_result tool="companionAct"
- +31s flow_game.narration_request game="word-radar" type="narration_request" word="around" reason="word_radar_response_prompt"
- +31s game_narration.speak text="around." activityId="word-radar" reason="word_radar_response_prompt"
- +31s transcript.queued turnState="PROCESSING" round=2 transcriptLength=6
- +31s flow_game.game_state_update game="word-radar" type="game_state_update"
- +31s flow_game.game_state_update game="word-radar" type="game_state_update"
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
- +34s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +34s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +34s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +34s tool.client_result tool="companionAct"
- +35s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +35s flow_game.game_state_update game="word-radar" type="game_state_update"
- +35s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +36s tool.client_result tool="sessionLog"
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
- +38s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +38s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +39s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +40s tool.client_result tool="companionAct"
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
- +42s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +42s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +43s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +47s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +47s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +47s transcript.replay turnState="PROCESSING" round=5 transcriptLength=5
- +47s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +47s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +47s flow_game.game_state_update game="word-radar" type="game_state_update"
- +47s flow_game.game_state_update game="word-radar" type="game_state_update"
- +48s flow_game.game_state_update game="word-radar" type="game_state_update"
- +49s flow_game.game_complete game="word-radar" type="game_complete"
- +50s flow_game.voice_control game="word-radar" type="voice_control"
- +51s session.ending turnState="PROCESSING" roundNumber=5 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=5 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=23
- +51s ws.send type="session_state" state="IDLE"
- +51s turn.state_changed state="IDLE"
- +51s engine.session_finalized totalAttempts=12 accuracy=1
- +51s engine.progression_computed level=8 totalXP=755 wordsMastered=6

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 5,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "9232292e-3f23-46cf-ad75-d39c9b924fab",
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
