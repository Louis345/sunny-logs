# Sunny Session Debug Summary

sessionId: 09f2cfc1-f192-43c9-a947-cd796310fa93
date: 2026-05-19T06:46:03.193Z
endedAt: 2026-05-19T06:48:00.509Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 117316
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
- +33s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +36s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +40s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +44s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +45s flow_game.game_state_update game="word-radar" type="game_state_update"
- +47s flow_game.game_complete game="word-radar" type="game_complete"
- +47s flow_game.voice_control game="word-radar" type="voice_control"
- +48s game_narration.speak text="Demo_Adaptive, spell check is ready. First target: again." activityId="spell-check" nodeId="n-spell-check-hw-adapt-weak_performance" reason="game_mount_greeting"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +55s transcript.accepted turnState="IDLE" round=1 transcriptLength=16
- +55s ws.send type="session_state" state="LOADING"
- +55s turn.state_changed state="LOADING"
- +55s ws.send type="session_state" state="PROCESSING"
- +55s turn.state_changed state="PROCESSING"
- +56s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +56s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +58s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +58s tool.client_result tool="companionAct"
- +59s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s ws.send type="session_state" state="SPEAKING"
- +59s turn.state_changed state="SPEAKING"
- +60s ws.send type="session_state" state="IDLE"
- +60s turn.state_changed state="IDLE"
- +64s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +65s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +65s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +66s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +66s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +66s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +69s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +70s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +71s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +71s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +74s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +75s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +75s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +76s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +76s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +76s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +80s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +80s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +82s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +82s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +82s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +84s flow_game.game_complete game="unknown" type="game_complete"
- +89s game_narration.speak text="Demo_Adaptive, pronunciation is ready. First target: again." activityId="pronunciation" nodeId="n-pronunciation-hw-adapt-weak_performance" reason="game_mount_greeting"
- +91s flow_game.voice_control game="pronunciation" type="voice_control"
- +91s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +91s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +96s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +96s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +101s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=1
- +101s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +101s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +101s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +106s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=2
- +106s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +106s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +107s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +112s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=3
- +112s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +112s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +113s session.ending turnState="IDLE" roundNumber=2 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=40
- +113s engine.session_finalized totalAttempts=22 accuracy=1
- +113s engine.progression_computed level=30 totalXP=2915 wordsMastered=6

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "09f2cfc1-f192-43c9-a947-cd796310fa93",
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
  "rewardLogEntries": 15
}
```

## Upload
Session saved locally. Upload not configured yet.
