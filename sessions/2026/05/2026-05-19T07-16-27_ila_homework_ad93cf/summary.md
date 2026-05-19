# Sunny Session Debug Summary

sessionId: ad93cf07-d20b-42d7-b57d-bc629277969f
date: 2026-05-19T07:16:27.656Z
endedAt: 2026-05-19T07:18:23.564Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 115908
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
- +30s game_narration.speak text="away." activityId="word-radar" reason="word_radar_response_prompt"
- +31s flow_game.game_state_update game="word-radar" type="game_state_update"
- +31s flow_game.game_state_update game="word-radar" type="game_state_update"
- +34s flow_game.narration_request game="word-radar" type="narration_request" word="alone" reason="word_radar_response_prompt"
- +34s game_narration.speak text="alone." activityId="word-radar" reason="word_radar_response_prompt"
- +34s flow_game.game_state_update game="word-radar" type="game_state_update"
- +34s flow_game.game_state_update game="word-radar" type="game_state_update"
- +37s flow_game.narration_request game="word-radar" type="narration_request" word="awake" reason="word_radar_response_prompt"
- +37s game_narration.speak text="awake." activityId="word-radar" reason="word_radar_response_prompt"
- +38s flow_game.game_state_update game="word-radar" type="game_state_update"
- +38s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s flow_game.narration_request game="word-radar" type="narration_request" word="above" reason="word_radar_response_prompt"
- +41s game_narration.speak text="above." activityId="word-radar" reason="word_radar_response_prompt"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +43s flow_game.game_state_update game="word-radar" type="game_state_update"
- +44s flow_game.game_complete game="word-radar" type="game_complete"
- +44s flow_game.voice_control game="word-radar" type="voice_control"
- +45s game_narration.speak text="Demo_Adaptive, spell check is ready. First target: again." activityId="spell-check" nodeId="n-spell-check-hw-adapt-weak_performance" reason="game_mount_greeting"
- +51s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +52s transcript.accepted turnState="IDLE" round=1 transcriptLength=16
- +52s ws.send type="session_state" state="LOADING"
- +52s turn.state_changed state="LOADING"
- +52s ws.send type="session_state" state="PROCESSING"
- +52s turn.state_changed state="PROCESSING"
- +53s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +53s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +55s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +55s tool.client_result tool="companionAct"
- +56s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +58s ws.send type="session_state" state="SPEAKING"
- +58s turn.state_changed state="SPEAKING"
- +58s ws.send type="session_state" state="IDLE"
- +58s turn.state_changed state="IDLE"
- +61s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +62s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +62s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +63s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +63s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +63s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +66s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +67s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +68s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +68s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +71s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +72s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +72s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +76s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +77s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +77s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +79s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +80s flow_game.game_complete game="unknown" type="game_complete"
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
- +104s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +109s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="again" wordIndex=0 attempt=3
- +109s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +109s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +110s session.ending turnState="IDLE" roundNumber=2 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=40
- +110s engine.session_finalized totalAttempts=22 accuracy=1
- +110s engine.progression_computed level=27 totalXP=2630 wordsMastered=6

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "ad93cf07-d20b-42d7-b57d-bc629277969f",
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
