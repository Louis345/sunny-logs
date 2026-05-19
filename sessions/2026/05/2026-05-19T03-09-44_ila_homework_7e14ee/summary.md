# Sunny Session Debug Summary

sessionId: 7e14ee7a-fbb4-4a5c-a8d4-63c3b0d5101e
date: 2026-05-19T03:09:44.192Z
endedAt: 2026-05-19T03:10:38.379Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 54187
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
- +32s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +32s tool.client_result tool="sessionLog"
- +33s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +35s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +35s tool.client_result tool="companionAct"
- +36s ws.send type="session_state" state="SPEAKING"
- +36s turn.state_changed state="SPEAKING"
- +36s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +36s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +36s ws.send type="session_state" state="IDLE"
- +36s turn.state_changed state="IDLE"
- +36s transcript.replay turnState="IDLE" round=3 transcriptLength=4
- +36s transcript.accepted turnState="IDLE" round=3 transcriptLength=4
- +36s ws.send type="session_state" state="LOADING"
- +36s turn.state_changed state="LOADING"
- +36s ws.send type="session_state" state="PROCESSING"
- +36s turn.state_changed state="PROCESSING"
- +37s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +39s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +39s tool.client_result tool="companionAct"
- +40s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +40s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +40s transcript.replay turnState="PROCESSING" round=4 transcriptLength=5
- +40s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
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
- +40s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +42s tool.client_result tool="companionAct"
- +44s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +44s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +44s transcript.replay turnState="PROCESSING" round=5 transcriptLength=5
- +44s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +44s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +44s ws.send type="session_state" state="SPEAKING"
- +44s turn.state_changed state="SPEAKING"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s ws.send type="session_state" state="IDLE"
- +44s turn.state_changed state="IDLE"
- +44s transcript.replay turnState="IDLE" round=5 transcriptLength=5
- +44s transcript.accepted turnState="IDLE" round=5 transcriptLength=5
- +44s ws.send type="session_state" state="LOADING"
- +44s turn.state_changed state="LOADING"
- +44s ws.send type="session_state" state="PROCESSING"
- +44s turn.state_changed state="PROCESSING"
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +46s flow_game.game_complete game="word-radar" type="game_complete"
- +47s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +47s tool.client_result tool="companionAct"
- +47s flow_game.voice_control game="word-radar" type="voice_control"
- +47s session.ending turnState="PROCESSING" roundNumber=6 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=25
- +47s ws.send type="session_state" state="IDLE"
- +47s turn.state_changed state="IDLE"
- +47s engine.session_finalized totalAttempts=12 accuracy=1
- +47s engine.progression_computed level=13 totalXP=1255 wordsMastered=6

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 6,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "7e14ee7a-fbb4-4a5c-a8d4-63c3b0d5101e",
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
