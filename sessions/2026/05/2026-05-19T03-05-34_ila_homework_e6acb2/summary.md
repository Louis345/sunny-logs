# Sunny Session Debug Summary

sessionId: e6acb21f-e36c-4e32-ad8f-dbc8f57b85e3
date: 2026-05-19T03:05:34.003Z
endedAt: 2026-05-19T03:06:26.354Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 52351
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
- +29s transcript.replay turnState="IDLE" round=2 transcriptLength=6
- +29s transcript.accepted turnState="IDLE" round=2 transcriptLength=6
- +29s ws.send type="session_state" state="LOADING"
- +29s turn.state_changed state="LOADING"
- +29s ws.send type="session_state" state="PROCESSING"
- +29s turn.state_changed state="PROCESSING"
- +31s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +31s tool.client_result tool="sessionLog"
- +31s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +31s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +32s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +32s flow_game.game_state_update game="word-radar" type="game_state_update"
- +32s flow_game.game_state_update game="word-radar" type="game_state_update"
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
- +35s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +35s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +36s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +38s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +38s tool.client_result tool="companionAct"
- +39s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +39s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +39s transcript.replay turnState="PROCESSING" round=4 transcriptLength=5
- +39s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +40s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +40s ws.send type="session_state" state="SPEAKING"
- +40s turn.state_changed state="SPEAKING"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s ws.send type="session_state" state="IDLE"
- +40s turn.state_changed state="IDLE"
- +40s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +40s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +40s ws.send type="session_state" state="LOADING"
- +40s turn.state_changed state="LOADING"
- +40s ws.send type="session_state" state="PROCESSING"
- +40s turn.state_changed state="PROCESSING"
- +43s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +43s tool.client_result tool="sessionLog"
- +43s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +43s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +44s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +45s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +45s tool.client_result tool="companionAct"
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +46s flow_game.game_complete game="word-radar" type="game_complete"
- +47s flow_game.voice_control game="word-radar" type="voice_control"
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
- +47s session.ending turnState="PROCESSING" roundNumber=6 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=25
- +47s ws.send type="session_state" state="IDLE"
- +47s turn.state_changed state="IDLE"
- +47s engine.session_finalized totalAttempts=12 accuracy=1
- +47s engine.progression_computed level=7 totalXP=630 wordsMastered=6
- +50s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +50s tool.client_result tool="sessionLog"
- +52s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +52s tool.client_result tool="companionAct"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 6,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "e6acb21f-e36c-4e32-ad8f-dbc8f57b85e3",
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
