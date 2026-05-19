# Sunny Session Debug Summary

sessionId: d980dfc9-8399-432a-8a0f-0baef6af7032
date: 2026-05-19T07:14:33.291Z
endedAt: 2026-05-19T07:16:29.524Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 116233
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
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +33s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +36s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +41s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +42s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s flow_game.game_state_update game="word-radar" type="game_state_update"
- +45s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +45s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +46s flow_game.game_state_update game="word-radar" type="game_state_update"
- +46s flow_game.game_state_update game="word-radar" type="game_state_update"
- +47s flow_game.game_state_update game="word-radar" type="game_state_update"
- +48s flow_game.game_complete game="word-radar" type="game_complete"
- +48s flow_game.voice_control game="word-radar" type="voice_control"
- +49s game_narration.speak text="Demo_Adaptive, spell check is ready. First target: again." activityId="spell-check" nodeId="n-spell-check-hw-adapt-weak_performance" reason="game_mount_greeting"
- +55s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +56s transcript.accepted turnState="IDLE" round=1 transcriptLength=16
- +56s ws.send type="session_state" state="LOADING"
- +56s turn.state_changed state="LOADING"
- +56s ws.send type="session_state" state="PROCESSING"
- +56s turn.state_changed state="PROCESSING"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +58s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +58s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +58s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +59s tool.client_result tool="companionAct"
- +60s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +61s ws.send type="session_state" state="SPEAKING"
- +61s turn.state_changed state="SPEAKING"
- +61s ws.send type="session_state" state="IDLE"
- +61s turn.state_changed state="IDLE"
- +65s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +65s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +65s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +67s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +67s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +67s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +70s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +70s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +72s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +72s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +75s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +75s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +75s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +77s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +77s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +77s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +80s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +80s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +80s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +82s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +82s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +82s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +84s flow_game.game_complete game="unknown" type="game_complete"
- +90s game_narration.speak text="Demo_Adaptive, pronunciation is ready. First target: again." activityId="pronunciation" nodeId="n-pronunciation-hw-adapt-weak_performance" reason="game_mount_greeting"
- +91s flow_game.voice_control game="pronunciation" type="voice_control"
- +91s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +91s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +96s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +96s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +101s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=1
- +101s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +101s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +102s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +107s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=2
- +107s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +107s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +107s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +112s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=3
- +112s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +113s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +113s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +114s session.ending turnState="IDLE" roundNumber=2 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=40
- +114s engine.session_finalized totalAttempts=22 accuracy=1
- +114s engine.progression_computed level=25 totalXP=2405 wordsMastered=6

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "d980dfc9-8399-432a-8a0f-0baef6af7032",
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
