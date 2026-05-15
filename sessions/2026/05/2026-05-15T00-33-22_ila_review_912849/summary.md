# Sunny Session Debug Summary

sessionId: 912849ea-1aa8-4ff5-bfea-001eec3972ac
date: 2026-05-15T00:33:22.007Z
endedAt: 2026-05-15T00:45:17.348Z
child: Ila
subject: review
mode: real
gitCommit: ec55b2b
command: npm run npx
duration_ms: 715341
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: 
- SUNNY_SUBJECT: review
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +420s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +420s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=2 word="vowel" bonusMultiplier=1 wordIndex=8
- +420s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +421s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +424s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +424s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=3 word="whole" bonusMultiplier=1 wordIndex=9
- +424s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=10
- +424s flow_game.pronunciation_complete game="pronunciation" totalWords=10 correctCount=10 accuracyPct=71 wordsAttempted=14 wordsHit=10 xpEarned=140 bestStreak=5
- +436s transcript.accepted turnState="IDLE" round=4 transcriptLength=176
- +436s ws.send type="session_state" state="LOADING"
- +436s turn.state_changed state="LOADING"
- +436s ws.send type="session_state" state="PROCESSING"
- +436s turn.state_changed state="PROCESSING"
- +438s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +438s tool.client_result tool="companionAct"
- +439s transcript.queued turnState="PROCESSING" round=5 transcriptLength=190
- +439s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +439s game_narration.speak text="shiny." activityId="monster-stampede" nodeId="n-mystery-hw-spelling_test-a0d1d9f2" reason="word_prompt"
- +439s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +440s ws.send type="session_state" state="SPEAKING"
- +440s turn.state_changed state="SPEAKING"
- +440s ws.send type="session_state" state="IDLE"
- +440s turn.state_changed state="IDLE"
- +440s transcript.replay turnState="IDLE" round=5 transcriptLength=190
- +440s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=190
- +447s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +448s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +450s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +450s game_narration.speak text="slowly." activityId="monster-stampede" nodeId="n-mystery-hw-spelling_test-a0d1d9f2" reason="word_prompt"
- +450s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +450s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=20
- +460s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=8
- +460s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +461s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +461s game_narration.speak text="lucky." activityId="monster-stampede" nodeId="n-mystery-hw-spelling_test-a0d1d9f2" reason="word_prompt"
- +461s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +463s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=12
- +469s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +471s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +471s game_narration.speak text="neatly." activityId="monster-stampede" nodeId="n-mystery-hw-spelling_test-a0d1d9f2" reason="word_prompt"
- +471s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +472s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=21
- +479s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +481s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +481s game_narration.speak text="sunny." activityId="monster-stampede" nodeId="n-mystery-hw-spelling_test-a0d1d9f2" reason="word_prompt"
- +481s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +482s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=10
- +487s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +489s flow_game.game_state_update game="monster-stampede" type="game_state_update"
- +489s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=11
- +489s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=12
- +493s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=152
- +493s transcript.duplicate_suppressed turnState="IDLE" round=5 transcriptLength=152
- +494s transcript.duplicate_suppressed turnState="IDLE" round=5 transcriptLength=152
- +509s transcript.urgent_learning_support intent="stop_or_pause" reason="child_requested_pause" stateBefore="IDLE" round=5 transcriptLength=160 activityId="monster-stampede"
- +509s urgent_learning.response intent="stop_or_pause" activityId="monster-stampede" hasGameMessage=true
- +509s ws.send type="session_state" state="LOADING"
- +509s turn.state_changed state="LOADING"
- +509s ws.send type="session_state" state="PROCESSING"
- +509s turn.state_changed state="PROCESSING"
- +509s ws.send type="session_state" state="SPEAKING"
- +509s turn.state_changed state="SPEAKING"
- +512s ws.send type="session_state" state="IDLE"
- +512s turn.state_changed state="IDLE"
- +512s transcript.urgent_learning_support intent="stop_or_pause" reason="child_requested_pause" stateBefore="IDLE" round=5 transcriptLength=160 activityId="monster-stampede"
- +512s urgent_learning.response intent="stop_or_pause" activityId="monster-stampede" hasGameMessage=true
- +512s ws.send type="session_state" state="LOADING"
- +512s turn.state_changed state="LOADING"
- +512s ws.send type="session_state" state="PROCESSING"
- +512s turn.state_changed state="PROCESSING"
- +512s ws.send type="session_state" state="SPEAKING"
- +512s turn.state_changed state="SPEAKING"
- +513s ws.send type="session_state" state="IDLE"
- +513s turn.state_changed state="IDLE"
- +542s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=74
- +545s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=86
- +568s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=5 transcriptLength=29
- +622s session.ending turnState="IDLE" roundNumber=5 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=271
- +622s engine.session_finalized totalAttempts=0 accuracy=0
- +622s engine.progression_computed level=69 totalXP=6815 wordsMastered=10

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 5,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "912849ea-1aa8-4ff5-bfea-001eec3972ac",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 271
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 271,
  "rewardLogEntries": 11
}
```

## Upload
Session saved locally. Upload not configured yet.
