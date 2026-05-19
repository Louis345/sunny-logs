# Sunny Session Debug Summary

sessionId: 8eedc796-2c1b-49c5-a1db-db5528e6fa5c
date: 2026-05-19T04:34:22.087Z
endedAt: 2026-05-19T04:42:08.596Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 466509
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
- +36s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +39s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +39s tool.client_result tool="sessionLog"
- +39s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +39s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +40s transcript.replay turnState="PROCESSING" round=4 transcriptLength=5
- +40s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +41s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +41s tool.client_result tool="companionAct"
- +41s transcript.queued turnState="PROCESSING" round=4 transcriptLength=5
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s ws.send type="session_state" state="SPEAKING"
- +42s turn.state_changed state="SPEAKING"
- +43s ws.send type="session_state" state="IDLE"
- +43s turn.state_changed state="IDLE"
- +43s transcript.replay turnState="IDLE" round=4 transcriptLength=5
- +43s transcript.accepted turnState="IDLE" round=4 transcriptLength=5
- +43s ws.send type="session_state" state="LOADING"
- +43s turn.state_changed state="LOADING"
- +43s ws.send type="session_state" state="PROCESSING"
- +43s turn.state_changed state="PROCESSING"
- +43s flow_game.game_complete game="word-radar" type="game_complete"
- +43s flow_game.voice_control game="word-radar" type="voice_control"
- +44s game_narration.speak text="Demo_Adaptive, spell check is ready. First target: again." activityId="spell-check" nodeId="n-spell-check-hw-adapt-weak_performance" reason="game_mount_greeting"
- +45s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +45s tool.client_result tool="companionAct"
- +48s ws.send type="session_state" state="SPEAKING"
- +48s turn.state_changed state="SPEAKING"
- +50s ws.send type="session_state" state="IDLE"
- +50s turn.state_changed state="IDLE"
- +50s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +52s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +52s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +53s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +53s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +53s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +56s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +56s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +56s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +58s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +58s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +58s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +61s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +61s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +63s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +63s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +65s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +66s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +66s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +68s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +68s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +68s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +71s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +72s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +72s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +75s flow_game.game_complete game="unknown" type="game_complete"
- +82s flow_game.voice_control game="word-radar" type="voice_control"
- +88s flow_game.game_state_update game="word-radar" type="game_state_update"
- +90s flow_game.narration_request game="word-radar" type="narration_request" word="again" reason="word_radar_response_prompt"
- +90s game_narration.speak text="again." activityId="word-radar" reason="word_radar_response_prompt"
- +459s session.ending turnState="IDLE" roundNumber=5 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=45
- +459s engine.session_finalized totalAttempts=22 accuracy=1
- +459s engine.progression_computed level=11 totalXP=1080 wordsMastered=5

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 5,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "8eedc796-2c1b-49c5-a1db-db5528e6fa5c",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 45
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 45,
  "rewardLogEntries": 17
}
```

## Upload
Session saved locally. Upload not configured yet.
