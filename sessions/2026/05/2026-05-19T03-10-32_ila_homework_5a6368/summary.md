# Sunny Session Debug Summary

sessionId: 5a636878-00ce-43e4-ad6f-04a23f684cb3
date: 2026-05-19T03:10:32.478Z
endedAt: 2026-05-19T03:11:24.919Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 52441
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
- +30s ws.send type="session_state" state="SPEAKING"
- +30s turn.state_changed state="SPEAKING"
- +30s ws.send type="session_state" state="IDLE"
- +30s turn.state_changed state="IDLE"
- +30s transcript.replay turnState="IDLE" round=2 transcriptLength=6
- +30s transcript.accepted turnState="IDLE" round=2 transcriptLength=6
- +30s ws.send type="session_state" state="LOADING"
- +30s turn.state_changed state="LOADING"
- +30s ws.send type="session_state" state="PROCESSING"
- +30s turn.state_changed state="PROCESSING"
- +32s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +32s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +33s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +33s tool.client_result tool="sessionLog"
- +33s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +34s ws.send type="session_state" state="SPEAKING"
- +34s turn.state_changed state="SPEAKING"
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
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +37s tool.client_result tool="companionAct"
- +39s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +39s tool.client_result tool="sessionLog"
- +40s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +40s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +40s transcript.replay turnState="PROCESSING" round=4 transcriptLength=5
- +40s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +40s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s ws.send type="session_state" state="SPEAKING"
- +41s turn.state_changed state="SPEAKING"
- +41s ws.send type="session_state" state="IDLE"
- +41s turn.state_changed state="IDLE"
- +41s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +41s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +41s ws.send type="session_state" state="LOADING"
- +41s turn.state_changed state="LOADING"
- +41s ws.send type="session_state" state="PROCESSING"
- +41s turn.state_changed state="PROCESSING"
- +44s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +44s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +44s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +44s tool.client_result tool="companionAct"
- +44s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
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
- +46s flow_game.game_complete game="word-radar" type="game_complete"
- +47s flow_game.voice_control game="word-radar" type="voice_control"
- +47s session.ending turnState="PROCESSING" roundNumber=6 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=25
- +47s ws.send type="session_state" state="IDLE"
- +47s turn.state_changed state="IDLE"
- +47s engine.session_finalized totalAttempts=12 accuracy=1
- +47s engine.progression_computed level=14 totalXP=1380 wordsMastered=6
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
  "sessionId": "5a636878-00ce-43e4-ad6f-04a23f684cb3",
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
  "rewardLogEntries": 2
}
```

## Upload
Session saved locally. Upload not configured yet.
