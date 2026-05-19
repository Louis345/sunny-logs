# Sunny Session Debug Summary

sessionId: 0213a75a-ab94-48e8-b8ed-20ab82dc269b
date: 2026-05-19T03:03:58.242Z
endedAt: 2026-05-19T03:04:52.587Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 54345
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
- +26s flow_game.game_state_update game="word-radar" type="game_state_update"
- +29s flow_game.narration_request game="word-radar" type="narration_request" word="around" reason="word_radar_response_prompt"
- +29s game_narration.speak text="around." activityId="word-radar" reason="word_radar_response_prompt"
- +29s transcript.queued turnState="PROCESSING" round=2 transcriptLength=6
- +29s flow_game.game_state_update game="word-radar" type="game_state_update"
- +29s flow_game.game_state_update game="word-radar" type="game_state_update"
- +29s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +29s tool.client_result tool="companionAct"
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
- +32s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +32s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +33s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +34s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +34s tool.client_result tool="sessionLog"
- +36s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +36s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +36s transcript.replay turnState="PROCESSING" round=3 transcriptLength=4
- +36s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +36s transcript.queued turnState="PROCESSING" round=3 transcriptLength=5
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +37s tool.client_result tool="companionAct"
- +39s ws.send type="session_state" state="SPEAKING"
- +39s turn.state_changed state="SPEAKING"
- +39s ws.send type="session_state" state="IDLE"
- +39s turn.state_changed state="IDLE"
- +39s transcript.replay turnState="IDLE" round=3 transcriptLength=5
- +39s transcript.accepted turnState="IDLE" round=3 transcriptLength=5
- +39s ws.send type="session_state" state="LOADING"
- +39s turn.state_changed state="LOADING"
- +39s ws.send type="session_state" state="PROCESSING"
- +39s turn.state_changed state="PROCESSING"
- +39s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +39s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +40s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +41s tool.client_result tool="companionAct"
- +43s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +43s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +43s transcript.replay turnState="PROCESSING" round=4 transcriptLength=5
- +43s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +43s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=false
- +43s tool.client_result tool="sessionLog"
- +43s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +45s ws.send type="session_state" state="SPEAKING"
- +45s turn.state_changed state="SPEAKING"
- +45s ws.send type="session_state" state="IDLE"
- +45s turn.state_changed state="IDLE"
- +45s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +45s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +45s ws.send type="session_state" state="LOADING"
- +45s turn.state_changed state="LOADING"
- +45s ws.send type="session_state" state="PROCESSING"
- +45s turn.state_changed state="PROCESSING"
- +45s flow_game.game_complete game="word-radar" type="game_complete"
- +46s flow_game.voice_control game="word-radar" type="voice_control"
- +46s session.ending turnState="PROCESSING" roundNumber=5 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=23
- +46s ws.send type="session_state" state="IDLE"
- +46s turn.state_changed state="IDLE"
- +46s engine.session_finalized totalAttempts=12 accuracy=1
- +46s engine.progression_computed level=3 totalXP=230 wordsMastered=0
- +48s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +48s tool.client_result tool="companionAct"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 5,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "0213a75a-ab94-48e8-b8ed-20ab82dc269b",
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
