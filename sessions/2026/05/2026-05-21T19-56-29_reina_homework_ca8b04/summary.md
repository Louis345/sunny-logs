# Sunny Session Debug Summary

sessionId: ca8b043f-8fea-4be6-a485-b1c0c2f8c5bf
date: 2026-05-21T19:56:29.332Z
endedAt: 2026-05-21T20:01:38.276Z
child: Reina
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 308944
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
- +228s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=7
- +228s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=7
- +228s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=7
- +229s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +229s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +229s flow_game.pronunciation_latency_span game="pronunciation" type="pronunciation_latency_span" wordIndex=7 attempt=1
- +229s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +229s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=8 word="nothing" bonusMultiplier=1 wordIndex=7
- +230s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +230s flow_game.combo_breaker game="pronunciation" type="combo_breaker" streak=8 bonusWord="special" bonusMultiplier=2 difficulty="super_hard" reason="huge_streak"
- +230s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +230s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +230s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +231s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +231s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +231s flow_game.pronunciation_latency_span game="pronunciation" type="pronunciation_latency_span" wordIndex=8 attempt=1
- +231s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +231s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=9 word="special" bonusMultiplier=2 wordIndex=8
- +231s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +231s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +231s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +233s flow_game.pronunciation_latency_span game="pronunciation" type="pronunciation_latency_span" wordIndex=9 attempt=1
- +233s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=10
- +233s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=10 word="wheel" bonusMultiplier=1 wordIndex=9
- +233s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=10
- +233s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +233s flow_game.pronunciation_complete game="pronunciation" totalWords=10 correctCount=10 accuracyPct=100 wordsAttempted=10 wordsHit=10 xpEarned=200 bestStreak=10
- +235s transcript.accepted turnState="IDLE" round=6 transcriptLength=107
- +235s ws.send type="session_state" state="LOADING"
- +235s turn.state_changed state="LOADING"
- +235s ws.send type="session_state" state="IDLE"
- +235s turn.state_changed state="IDLE"
- +248s flow_game.voice_control game="pronunciation" type="voice_control"
- +249s transcript.urgent_learning_organic intent="bug_report" reason="child_reported_product_issue" stateBefore="IDLE" round=7 transcriptLength=153 currentWord="wheel" activityId="pronunciation"
- +249s transcript.accepted turnState="IDLE" round=7 transcriptLength=153
- +249s ws.send type="session_state" state="LOADING"
- +249s turn.state_changed state="LOADING"
- +249s ws.send type="session_state" state="PROCESSING"
- +249s turn.state_changed state="PROCESSING"
- +253s tool.called tool="recordProductIssue" argsKeys=["issueType","severity","childUtterance","evidenceText","confidence","source"] hasResult=true
- +253s tool.client_result tool="recordProductIssue"
- +255s ws.send type="session_state" state="SPEAKING"
- +255s turn.state_changed state="SPEAKING"
- +256s ws.send type="session_state" state="IDLE"
- +256s turn.state_changed state="IDLE"
- +265s transcript.accepted turnState="IDLE" round=8 transcriptLength=251
- +265s ws.send type="session_state" state="LOADING"
- +265s turn.state_changed state="LOADING"
- +265s ws.send type="session_state" state="PROCESSING"
- +265s turn.state_changed state="PROCESSING"
- +270s tool.called tool="recordProductIssue" argsKeys=["issueType","severity","childUtterance","evidenceText","confidence","source"] hasResult=true
- +270s tool.client_result tool="recordProductIssue"
- +272s ws.send type="session_state" state="SPEAKING"
- +272s turn.state_changed state="SPEAKING"
- +274s ws.send type="session_state" state="IDLE"
- +274s turn.state_changed state="IDLE"
- +274s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=9 tts="on"
- +274s canvas.draw mode="idle"
- +290s transcript.accepted turnState="IDLE" round=9 transcriptLength=564
- +290s ws.send type="session_state" state="LOADING"
- +290s turn.state_changed state="LOADING"
- +290s ws.send type="session_state" state="PROCESSING"
- +290s turn.state_changed state="PROCESSING"
- +292s transcript.queued turnState="PROCESSING" round=10 transcriptLength=576
- +296s tool.called tool="recordProductIssue" argsKeys=["issueType","severity","childUtterance","evidenceText","confidence","source"] hasResult=true
- +296s tool.client_result tool="recordProductIssue"
- +297s transcript.queued turnState="PROCESSING" round=10 transcriptLength=16
- +298s ws.send type="session_state" state="SPEAKING"
- +298s turn.state_changed state="SPEAKING"
- +308s ws.send type="session_state" state="IDLE"
- +308s turn.state_changed state="IDLE"
- +308s transcript.replay turnState="IDLE" round=10 transcriptLength=16
- +308s transcript.accepted turnState="IDLE" round=10 transcriptLength=16
- +308s ws.send type="session_state" state="LOADING"
- +308s turn.state_changed state="LOADING"
- +308s session.ending turnState="LOADING" roundNumber=10 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=32
- +308s ws.send type="session_state" state="IDLE"
- +308s turn.state_changed state="IDLE"
- +308s engine.session_finalized totalAttempts=0 accuracy=0
- +308s engine.progression_computed level=92 totalXP=9100 wordsMastered=41

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 10,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "ca8b043f-8fea-4be6-a485-b1c0c2f8c5bf",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 32
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 32,
  "rewardLogEntries": 1
}
```

## Upload
Session saved locally. Upload not configured yet.
