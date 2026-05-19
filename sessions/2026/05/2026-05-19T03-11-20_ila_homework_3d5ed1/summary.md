# Sunny Session Debug Summary

sessionId: 3d5ed1a2-61f1-44fe-b652-70508bb0f04a
date: 2026-05-19T03:11:20.420Z
endedAt: 2026-05-19T03:12:11.263Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 50843
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
- +31s ws.send type="session_state" state="PROCESSING"
- +31s turn.state_changed state="PROCESSING"
- +33s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +33s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +33s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +33s tool.client_result tool="companionAct"
- +35s ws.send type="session_state" state="SPEAKING"
- +35s turn.state_changed state="SPEAKING"
- +35s ws.send type="session_state" state="IDLE"
- +35s turn.state_changed state="IDLE"
- +35s transcript.replay turnState="IDLE" round=3 transcriptLength=4
- +35s transcript.accepted turnState="IDLE" round=3 transcriptLength=4
- +35s ws.send type="session_state" state="LOADING"
- +35s turn.state_changed state="LOADING"
- +35s ws.send type="session_state" state="PROCESSING"
- +35s turn.state_changed state="PROCESSING"
- +36s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +36s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +37s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +37s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +37s tool.client_result tool="companionAct"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +38s ws.send type="session_state" state="SPEAKING"
- +38s turn.state_changed state="SPEAKING"
- +38s ws.send type="session_state" state="IDLE"
- +38s turn.state_changed state="IDLE"
- +38s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +38s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +38s ws.send type="session_state" state="LOADING"
- +38s turn.state_changed state="LOADING"
- +38s ws.send type="session_state" state="PROCESSING"
- +38s turn.state_changed state="PROCESSING"
- +40s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +40s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +41s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +41s tool.client_result tool="companionAct"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s ws.send type="session_state" state="SPEAKING"
- +42s turn.state_changed state="SPEAKING"
- +42s ws.send type="session_state" state="IDLE"
- +42s turn.state_changed state="IDLE"
- +42s transcript.replay turnState="IDLE" round=5 transcriptLength=5
- +42s transcript.accepted turnState="IDLE" round=5 transcriptLength=5
- +42s ws.send type="session_state" state="LOADING"
- +42s turn.state_changed state="LOADING"
- +42s ws.send type="session_state" state="PROCESSING"
- +42s turn.state_changed state="PROCESSING"
- +44s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +44s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +44s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +44s tool.client_result tool="companionAct"
- +44s transcript.queued turnState="PROCESSING" round=6 transcriptLength=5
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +46s flow_game.game_complete game="word-radar" type="game_complete"
- +47s ws.send type="session_state" state="SPEAKING"
- +47s turn.state_changed state="SPEAKING"
- +47s flow_game.voice_control game="word-radar" type="voice_control"
- +47s ws.send type="session_state" state="IDLE"
- +47s turn.state_changed state="IDLE"
- +47s transcript.replay turnState="IDLE" round=6 transcriptLength=5
- +47s transcript.accepted turnState="IDLE" round=6 transcriptLength=5
- +47s ws.send type="session_state" state="LOADING"
- +47s turn.state_changed state="LOADING"
- +47s ws.send type="session_state" state="PROCESSING"
- +47s turn.state_changed state="PROCESSING"
- +47s session.ending turnState="PROCESSING" roundNumber=7 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=27
- +47s ws.send type="session_state" state="IDLE"
- +47s turn.state_changed state="IDLE"
- +47s engine.session_finalized totalAttempts=12 accuracy=1
- +47s engine.progression_computed level=16 totalXP=1505 wordsMastered=6
- +51s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +51s tool.client_result tool="companionAct"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 7,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "3d5ed1a2-61f1-44fe-b652-70508bb0f04a",
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
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
