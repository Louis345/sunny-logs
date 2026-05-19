# Sunny Session Debug Summary

sessionId: a36ae7f5-556e-4f08-9081-8c8f2c1afd92
date: 2026-05-19T06:44:11.797Z
endedAt: 2026-05-19T06:46:07.101Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 115304
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
- +31s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +32s flow_game.game_state_update game="word-radar" type="game_state_update"
- +32s flow_game.game_state_update game="word-radar" type="game_state_update"
- +35s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +35s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +36s flow_game.game_state_update game="word-radar" type="game_state_update"
- +39s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +39s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +39s flow_game.game_state_update game="word-radar" type="game_state_update"
- +39s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +42s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +42s flow_game.game_state_update game="word-radar" type="game_state_update"
- +42s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.game_state_update game="word-radar" type="game_state_update"
- +45s flow_game.game_complete game="word-radar" type="game_complete"
- +45s flow_game.voice_control game="word-radar" type="voice_control"
- +45s game_narration.speak text="Demo_Adaptive, spell check is ready. First target: again." activityId="spell-check" nodeId="n-spell-check-hw-adapt-weak_performance" reason="game_mount_greeting"
- +52s flow_game.game_state_update game="Spell Check" type="game_state_update"
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
- +56s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +56s tool.client_result tool="companionAct"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s ws.send type="session_state" state="SPEAKING"
- +59s turn.state_changed state="SPEAKING"
- +60s ws.send type="session_state" state="IDLE"
- +60s turn.state_changed state="IDLE"
- +62s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +62s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +62s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +64s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +64s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +64s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +67s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +68s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +69s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +69s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +72s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +74s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +74s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +74s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +77s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +78s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +78s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +81s flow_game.game_complete game="unknown" type="game_complete"
- +87s game_narration.speak text="Demo_Adaptive, pronunciation is ready. First target: again." activityId="pronunciation" nodeId="n-pronunciation-hw-adapt-weak_performance" reason="game_mount_greeting"
- +88s flow_game.voice_control game="pronunciation" type="voice_control"
- +88s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +88s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +93s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +93s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +98s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=1
- +98s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +98s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +99s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +104s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=2
- +104s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +104s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +105s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +110s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=3
- +110s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +110s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +111s session.ending turnState="IDLE" roundNumber=2 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=40
- +111s engine.session_finalized totalAttempts=22 accuracy=1
- +111s engine.progression_computed level=27 totalXP=2690 wordsMastered=6

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "a36ae7f5-556e-4f08-9081-8c8f2c1afd92",
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
