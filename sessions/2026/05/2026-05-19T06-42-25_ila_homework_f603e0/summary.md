# Sunny Session Debug Summary

sessionId: f603e0e2-78e5-4050-a773-abfc3a7b3667
date: 2026-05-19T06:42:25.475Z
endedAt: 2026-05-19T06:44:17.959Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 112484
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
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +40s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +43s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +43s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +43s flow_game.game_state_update game="word-radar" type="game_state_update"
- +43s flow_game.game_state_update game="word-radar" type="game_state_update"
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +46s flow_game.game_complete game="word-radar" type="game_complete"
- +46s flow_game.voice_control game="word-radar" type="voice_control"
- +46s game_narration.speak text="Demo_Adaptive, spell check is ready. First target: again." activityId="spell-check" nodeId="n-spell-check-hw-adapt-weak_performance" reason="game_mount_greeting"
- +53s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +53s transcript.accepted turnState="IDLE" round=1 transcriptLength=16
- +53s ws.send type="session_state" state="LOADING"
- +53s turn.state_changed state="LOADING"
- +53s ws.send type="session_state" state="PROCESSING"
- +53s turn.state_changed state="PROCESSING"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +55s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +55s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +55s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +55s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +55s tool.client_result tool="companionAct"
- +58s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +59s tool.client_result tool="sessionLog"
- +59s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +60s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +60s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +60s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +61s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +61s tool.client_result tool="sessionLog"
- +63s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +63s tool.client_result tool="sessionLog"
- +63s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +63s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +64s ws.send type="session_state" state="SPEAKING"
- +64s turn.state_changed state="SPEAKING"
- +64s ws.send type="session_state" state="IDLE"
- +64s turn.state_changed state="IDLE"
- +65s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +65s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +68s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +68s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +68s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +70s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +70s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +70s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +75s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +75s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +75s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +77s flow_game.game_complete game="unknown" type="game_complete"
- +83s game_narration.speak text="Demo_Adaptive, pronunciation is ready. First target: again." activityId="pronunciation" nodeId="n-pronunciation-hw-adapt-weak_performance" reason="game_mount_greeting"
- +84s flow_game.voice_control game="pronunciation" type="voice_control"
- +84s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +84s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +89s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +89s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +94s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=1
- +94s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +94s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +95s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +100s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=2
- +100s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +100s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +100s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +105s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=3
- +105s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +106s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +106s session.ending turnState="IDLE" roundNumber=2 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=40
- +106s engine.session_finalized totalAttempts=25 accuracy=1
- +106s engine.progression_computed level=25 totalXP=2465 wordsMastered=6

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "f603e0e2-78e5-4050-a773-abfc3a7b3667",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 40
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 40,
  "rewardLogEntries": 18
}
```

## Upload
Session saved locally. Upload not configured yet.
