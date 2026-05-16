# Sunny Session Debug Summary

sessionId: ad627521-09cc-47e0-a8c2-0d4fbf8df31b
date: 2026-05-16T17:22:49.144Z
endedAt: 2026-05-16T17:24:54.260Z
child: Ila
subject: homework
mode: real
gitCommit: ec55b2b
command: npm run npx
duration_ms: 125116
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
- +43s turn.state_changed state="IDLE"
- +44s transcript.urgent_learning_support intent="stop_or_pause" reason="child_requested_pause" stateBefore="IDLE" round=1 transcriptLength=172 currentWord="away" activityId="pronunciation"
- +44s urgent_learning.response intent="stop_or_pause" activityId="pronunciation" currentWord="away" hasGameMessage=true
- +44s ws.send type="session_state" state="LOADING"
- +44s turn.state_changed state="LOADING"
- +44s ws.send type="session_state" state="PROCESSING"
- +44s turn.state_changed state="PROCESSING"
- +44s ws.send type="session_state" state="SPEAKING"
- +44s turn.state_changed state="SPEAKING"
- +44s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +45s ws.send type="session_state" state="IDLE"
- +45s turn.state_changed state="IDLE"
- +46s transcript.urgent_learning_support intent="stop_or_pause" reason="child_requested_pause" stateBefore="IDLE" round=1 transcriptLength=175 currentWord="away" activityId="pronunciation"
- +46s urgent_learning.response intent="stop_or_pause" activityId="pronunciation" currentWord="away" hasGameMessage=true
- +46s ws.send type="session_state" state="LOADING"
- +46s turn.state_changed state="LOADING"
- +46s ws.send type="session_state" state="PROCESSING"
- +46s turn.state_changed state="PROCESSING"
- +46s ws.send type="session_state" state="SPEAKING"
- +46s turn.state_changed state="SPEAKING"
- +46s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +46s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=5
- +46s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=1 word="away" bonusMultiplier=1 wordIndex=4
- +46s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=5
- +47s ws.send type="session_state" state="IDLE"
- +47s turn.state_changed state="IDLE"
- +48s transcript.suppressed reason="pronunciation_active_game" turnState="IDLE" round=1 transcriptLength=5
- +51s transcript.suppressed reason="pronunciation_active_game" turnState="IDLE" round=1 transcriptLength=5
- +54s transcript.suppressed reason="pronunciation_active_game" turnState="IDLE" round=1 transcriptLength=5
- +63s transcript.suppressed reason="pronunciation_active_game" turnState="IDLE" round=1 transcriptLength=5
- +64s transcript.suppressed reason="pronunciation_active_game" turnState="IDLE" round=1 transcriptLength=14
- +70s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=5
- +70s flow_game.pronunciation_complete game="pronunciation" totalWords=5 correctCount=5 accuracyPct=63 wordsAttempted=8 wordsHit=5 xpEarned=70 bestStreak=4
- +74s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=5
- +74s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +74s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=0
- +77s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +77s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +77s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +77s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=1 word="above" bonusMultiplier=1 wordIndex=0
- +77s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +77s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +77s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +79s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +79s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +79s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +79s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=2 word="ago" bonusMultiplier=1 wordIndex=1
- +79s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +79s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +79s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +80s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +80s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +80s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +80s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=3 word="about" bonusMultiplier=1 wordIndex=2
- +80s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +80s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +81s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +82s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +82s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +82s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +82s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=4 word="ahead" bonusMultiplier=1 wordIndex=3
- +82s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +82s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +83s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +85s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=5
- +85s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=5 word="away" bonusMultiplier=1 wordIndex=4
- +85s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=5
- +86s transcript.suppressed reason="pronunciation_active_game" turnState="IDLE" round=1 transcriptLength=74
- +93s transcript.suppressed reason="pronunciation_active_game" turnState="IDLE" round=1 transcriptLength=28
- +94s transcript.suppressed reason="pronunciation_active_game" turnState="IDLE" round=1 transcriptLength=34
- +97s transcript.suppressed reason="pronunciation_active_game" turnState="IDLE" round=1 transcriptLength=26
- +103s flow_game.voice_control game="pronunciation" type="voice_control"
- +118s transcript.accepted turnState="IDLE" round=1 transcriptLength=38
- +118s ws.send type="session_state" state="LOADING"
- +118s turn.state_changed state="LOADING"
- +118s session.ending turnState="LOADING" roundNumber=1 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=13
- +118s ws.send type="session_state" state="IDLE"
- +118s turn.state_changed state="IDLE"
- +118s engine.session_finalized totalAttempts=0 accuracy=0
- +118s engine.progression_computed level=77 totalXP=7620 wordsMastered=14

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 1,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "ad627521-09cc-47e0-a8c2-0d4fbf8df31b",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 13
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 13,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
