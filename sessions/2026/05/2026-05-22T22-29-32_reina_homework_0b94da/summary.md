# Sunny Session Debug Summary

sessionId: 0b94da05-9f33-43f4-ac90-6e7ef4eca3d7
date: 2026-05-22T22:29:32.722Z
endedAt: 2026-05-22T22:39:07.093Z
child: Reina
subject: homework
mode: real
gitCommit: cc49f2b
command: npm run npx
duration_ms: 574371
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +509s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=8 word="nothing" bonusMultiplier=1 wordIndex=7
- +509s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +509s flow_game.combo_breaker game="pronunciation" type="combo_breaker" streak=8 bonusWord="special" bonusMultiplier=2 difficulty="super_hard" reason="huge_streak"
- +509s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +509s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +509s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +510s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +510s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +510s flow_game.pronunciation_latency_span game="pronunciation" type="pronunciation_latency_span" wordIndex=8 attempt=1
- +510s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +510s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=9 word="special" bonusMultiplier=2 wordIndex=8
- +510s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +510s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +511s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +511s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +514s transcript.accepted turnState="IDLE" round=29 transcriptLength=36
- +514s ws.send type="session_state" state="LOADING"
- +514s turn.state_changed state="LOADING"
- +514s ws.send type="session_state" state="IDLE"
- +514s turn.state_changed state="IDLE"
- +516s transcript.accepted turnState="IDLE" round=30 transcriptLength=42
- +516s ws.send type="session_state" state="LOADING"
- +516s turn.state_changed state="LOADING"
- +516s ws.send type="session_state" state="IDLE"
- +516s turn.state_changed state="IDLE"
- +518s transcript.accepted turnState="IDLE" round=31 transcriptLength=48
- +518s ws.send type="session_state" state="LOADING"
- +518s turn.state_changed state="LOADING"
- +518s ws.send type="session_state" state="IDLE"
- +518s turn.state_changed state="IDLE"
- +519s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +525s flow_game.voice_control game="pronunciation" type="voice_control"
- +529s transcript.accepted turnState="IDLE" round=32 transcriptLength=107
- +529s ws.send type="session_state" state="LOADING"
- +529s turn.state_changed state="LOADING"
- +529s ws.send type="session_state" state="PROCESSING"
- +529s turn.state_changed state="PROCESSING"
- +530s game_narration.speak text="farmer." activityId="letter-rush" nodeId="node-5-silent-mastery" reason="word_prompt"
- +530s flow_game.game_state_update game="Letter Rush" type="game_state_update"
- +530s flow_game.game_state_update game="Letter Rush" type="game_state_update"
- +530s flow_game.game_state_update game="Letter Rush" type="game_state_update"
- +531s game_narration.playback_done text="farmer." activityId="letter-rush" nodeId="node-5-silent-mastery" reason="word_prompt"
- +532s flow_game.game_state_update game="Letter Rush" type="game_state_update"
- +533s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +533s tool.client_result tool="companionAct"
- +533s flow_game.game_state_update game="Letter Rush" type="game_state_update"
- +534s flow_game.game_state_update game="Letter Rush" type="game_state_update"
- +535s tool.called tool="expressCompanion" argsKeys=["emote","intensity"] hasResult=true
- +535s tool.client_result tool="expressCompanion"
- +536s ws.send type="session_state" state="SPEAKING"
- +536s turn.state_changed state="SPEAKING"
- +536s ws.send type="session_state" state="IDLE"
- +536s turn.state_changed state="IDLE"
- +548s transcript.accepted turnState="IDLE" round=33 transcriptLength=120
- +548s ws.send type="session_state" state="LOADING"
- +548s turn.state_changed state="LOADING"
- +548s ws.send type="session_state" state="PROCESSING"
- +548s turn.state_changed state="PROCESSING"
- +550s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +550s tool.client_result tool="companionAct"
- +552s ws.send type="session_state" state="SPEAKING"
- +552s turn.state_changed state="SPEAKING"
- +558s ws.send type="session_state" state="IDLE"
- +558s turn.state_changed state="IDLE"
- +558s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=34 tts="on"
- +558s canvas.draw mode="idle"
- +562s transcript.accepted turnState="IDLE" round=34 transcriptLength=307
- +562s ws.send type="session_state" state="LOADING"
- +562s turn.state_changed state="LOADING"
- +562s ws.send type="session_state" state="PROCESSING"
- +562s turn.state_changed state="PROCESSING"
- +564s tool.called tool="sessionEnd" argsKeys=["childName","reason"] hasResult=true
- +564s tool.client_result tool="sessionEnd"
- +566s ws.send type="session_state" state="SPEAKING"
- +566s turn.state_changed state="SPEAKING"
- +566s session.ending turnState="SPEAKING" roundNumber=35 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=115
- +566s ws.send type="session_state" state="IDLE"
- +566s turn.state_changed state="IDLE"
- +566s engine.session_finalized totalAttempts=89 accuracy=0.7528089887640449
- +566s engine.progression_computed level=111 totalXP=11070 wordsMastered=49

## Activity Evidence
- activityReadings: 243
- activityAttemptReadings: 221
- activityCorrectReadings: 186

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 35,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "0b94da05-9f33-43f4-ac90-6e7ef4eca3d7",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 115
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 115,
  "rewardLogEntries": 29
}
```

## Upload
Session saved locally. Upload not configured yet.
