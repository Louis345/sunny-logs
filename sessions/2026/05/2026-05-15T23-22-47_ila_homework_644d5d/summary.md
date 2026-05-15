# Sunny Session Debug Summary

sessionId: 644d5d87-de9c-439b-96fd-d362036cce72
date: 2026-05-15T23:22:47.546Z
endedAt: 2026-05-15T23:23:32.825Z
child: Ila
subject: homework
mode: real
gitCommit: ec55b2b
command: npm run npx
duration_ms: 45279
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Ila" companionName="Elli"
- +0s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s transcript.replay turnState="IDLE" round=0 transcriptLength=883
- +1s transcript.accepted turnState="IDLE" round=0 transcriptLength=883
- +1s ws.send type="session_state" state="LOADING"
- +1s turn.state_changed state="LOADING"
- +1s ws.send type="session_state" state="PROCESSING"
- +1s turn.state_changed state="PROCESSING"
- +3s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +3s tool.client_result tool="companionAct"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +6s session.started sessionType="homework" companionName="Elli"
- +9s ws.send type="session_state" state="IDLE"
- +9s turn.state_changed state="IDLE"
- +10s game_narration.speak text="ila, pronunciation is ready. First target: shiny." activityId="pronunciation" nodeId="n-pronunciation-hw-spelling_test-a0d1d9f2" reason="game_mount_greeting"
- +11s flow_game.voice_control game="pronunciation" type="voice_control"
- +11s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +11s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +12s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=1 transcriptLength=23
- +13s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +13s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +13s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +13s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=1 word="shiny" bonusMultiplier=1 wordIndex=0
- +13s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +13s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +14s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +15s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=1 transcriptLength=11
- +19s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="slowly" wordIndex=1 attempt=1
- +19s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +19s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +19s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +21s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=1 transcriptLength=28
- +23s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=1 transcriptLength=35
- +24s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="slowly" wordIndex=1 attempt=2
- +24s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +24s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +25s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +26s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=1 transcriptLength=55
- +29s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=1 transcriptLength=55
- +30s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +30s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +30s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +30s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=1 word="slowly" bonusMultiplier=1 wordIndex=1
- +30s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +30s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +30s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +31s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=1 transcriptLength=15
- +32s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +32s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +32s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +32s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=2 word="lucky" bonusMultiplier=1 wordIndex=2
- +32s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +32s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +32s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +37s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="neatly" wordIndex=3 attempt=1
- +37s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +37s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +38s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +43s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="neatly" wordIndex=3 attempt=2
- +43s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +43s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +43s session.ending turnState="IDLE" roundNumber=1 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=4
- +43s engine.session_finalized totalAttempts=0 accuracy=0
- +43s engine.progression_computed level=71 totalXP=7015 wordsMastered=9

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 1,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "644d5d87-de9c-439b-96fd-d362036cce72",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 4
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 4,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
