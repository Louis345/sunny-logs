# Sunny Session Debug Summary

sessionId: f5824fa3-3b24-4a90-9e4c-7d85be58776f
date: 2026-05-19T05:18:31.973Z
endedAt: 2026-05-19T05:19:35.114Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 63141
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
- +31s turn.state_changed state="LOADING"
- +31s ws.send type="session_state" state="PROCESSING"
- +31s turn.state_changed state="PROCESSING"
- +33s flow_game.narration_request game="word-radar" type="narration_request" word="away" reason="word_radar_response_prompt"
- +33s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +34s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +34s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +34s tool.client_result tool="companionAct"
- +34s flow_game.game_state_update game="word-radar" type="game_state_update"
- +34s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +37s tool.client_result tool="sessionLog"
- +37s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +37s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +37s transcript.replay turnState="PROCESSING" round=3 transcriptLength=4
- +37s transcript.queued turnState="PROCESSING" round=3 transcriptLength=4
- +37s transcript.queued turnState="PROCESSING" round=3 transcriptLength=5
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +38s ws.send type="session_state" state="SPEAKING"
- +38s turn.state_changed state="SPEAKING"
- +38s ws.send type="session_state" state="IDLE"
- +38s turn.state_changed state="IDLE"
- +38s transcript.replay turnState="IDLE" round=3 transcriptLength=5
- +38s transcript.accepted turnState="IDLE" round=3 transcriptLength=5
- +38s ws.send type="session_state" state="LOADING"
- +38s turn.state_changed state="LOADING"
- +38s ws.send type="session_state" state="PROCESSING"
- +38s turn.state_changed state="PROCESSING"
- +40s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +40s tool.client_result tool="companionAct"
- +40s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +40s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +41s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +42s tool.client_result tool="sessionLog"
- +44s ws.send type="session_state" state="SPEAKING"
- +44s turn.state_changed state="SPEAKING"
- +44s ws.send type="session_state" state="IDLE"
- +44s turn.state_changed state="IDLE"
- +44s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +44s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +44s ws.send type="session_state" state="LOADING"
- +44s turn.state_changed state="LOADING"
- +44s ws.send type="session_state" state="PROCESSING"
- +44s turn.state_changed state="PROCESSING"
- +44s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +44s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +45s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +46s flow_game.game_state_update game="word-radar" type="game_state_update"
- +47s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +47s tool.client_result tool="companionAct"
- +47s flow_game.game_complete game="word-radar" type="game_complete"
- +48s flow_game.voice_control game="word-radar" type="voice_control"
- +49s game_narration.speak text="Demo_Adaptive, spell check is ready. First target: again." activityId="spell-check" nodeId="n-spell-check-hw-adapt-weak_performance" reason="game_mount_greeting"
- +49s transcript.replay turnState="PROCESSING" round=5 transcriptLength=5
- +49s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +49s ws.send type="session_state" state="SPEAKING"
- +49s turn.state_changed state="SPEAKING"
- +49s ws.send type="session_state" state="IDLE"
- +49s turn.state_changed state="IDLE"
- +49s transcript.replay turnState="IDLE" round=5 transcriptLength=5
- +49s transcript.accepted turnState="IDLE" round=5 transcriptLength=5
- +49s ws.send type="session_state" state="LOADING"
- +49s turn.state_changed state="LOADING"
- +49s ws.send type="session_state" state="PROCESSING"
- +49s turn.state_changed state="PROCESSING"
- +52s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +52s tool.client_result tool="sessionLog"
- +54s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +54s tool.client_result tool="companionAct"
- +56s session.ending turnState="PROCESSING" roundNumber=6 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=28
- +56s ws.send type="session_state" state="IDLE"
- +56s turn.state_changed state="IDLE"
- +56s engine.session_finalized totalAttempts=15 accuracy=0.9333333333333333
- +56s engine.progression_computed level=7 totalXP=695 wordsMastered=5

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 6,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "f5824fa3-3b24-4a90-9e4c-7d85be58776f",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 30
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 30,
  "rewardLogEntries": 2
}
```

## Upload
Session saved locally. Upload not configured yet.
