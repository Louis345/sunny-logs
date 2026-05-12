# Sunny Session Debug Summary

sessionId: d5770ab4-99b9-4189-86bc-e1e862b0def1
date: 2026-05-12T00:23:03.549Z
endedAt: 2026-05-12T00:30:41.773Z
child: Reina
subject: review
mode: real
gitCommit: 7bbbafb
command: npm run npx
duration_ms: 458224
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
- +340s transcript.accepted turnState="IDLE" round=18 transcriptLength=12
- +340s ws.send type="session_state" state="LOADING"
- +340s turn.state_changed state="LOADING"
- +340s ws.send type="session_state" state="PROCESSING"
- +340s turn.state_changed state="PROCESSING"
- +342s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +342s tool.client_result tool="companionAct"
- +343s ws.send type="session_state" state="SPEAKING"
- +343s turn.state_changed state="SPEAKING"
- +346s ws.send type="session_state" state="IDLE"
- +346s turn.state_changed state="IDLE"
- +346s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=19 tts="on"
- +346s canvas.draw mode="idle"
- +349s transcript.accepted turnState="IDLE" round=19 transcriptLength=5
- +349s ws.send type="session_state" state="LOADING"
- +349s turn.state_changed state="LOADING"
- +349s ws.send type="session_state" state="PROCESSING"
- +349s turn.state_changed state="PROCESSING"
- +351s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +351s tool.client_result tool="companionAct"
- +351s tool.client_result tool="canvasShow"
- +351s canvas.draw mode="pronunciation" canvasRevision=2
- +352s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="above" wordIndex=0 attempt=1
- +353s ws.send type="session_state" state="SPEAKING"
- +353s turn.state_changed state="SPEAKING"
- +354s ws.send type="session_state" state="IDLE"
- +354s turn.state_changed state="IDLE"
- +354s flow_game.karaoke_progress game="karaoke-reading" event="progress" wordIndex=0 totalWords=4 accuracyPct=0 hesitations=1 flaggedCount=0 skippedCount=0 spelledCount=0
- +355s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=1 word="above" bonusMultiplier=1 wordIndex=0
- +357s flow_game.karaoke_progress game="karaoke-reading" event="progress" wordIndex=1 totalWords=4 accuracyPct=25 hesitations=2 flaggedCount=0 skippedCount=0 spelledCount=1 spelledWords=["above"]
- +357s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=2 word="about" bonusMultiplier=1 wordIndex=1
- +359s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=3 word="ahead" bonusMultiplier=1 wordIndex=2
- +360s flow_game.karaoke_progress game="karaoke-reading" event="progress" wordIndex=3 totalWords=4 accuracyPct=75 hesitations=2 flaggedCount=0 skippedCount=0 spelledCount=3 spelledWords=["above","about","ahead"]
- +361s flow_game.karaoke_complete game="karaoke-reading" event="complete" wordIndex=4 totalWords=4 accuracyPct=100 hesitations=2 flaggedCount=0 skippedCount=0 spelledCount=4 spelledWords=["above","about","ahead","away"]
- +361s transcript.replay turnState="IDLE" round=20 transcriptLength=242
- +361s transcript.accepted turnState="IDLE" round=20 transcriptLength=242
- +361s ws.send type="session_state" state="LOADING"
- +361s turn.state_changed state="LOADING"
- +361s ws.send type="session_state" state="PROCESSING"
- +361s turn.state_changed state="PROCESSING"
- +361s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=4 word="away" bonusMultiplier=1 wordIndex=3
- +361s flow_game.pronunciation_complete game="pronunciation" totalWords=4 correctCount=4 accuracyPct=80 wordsAttempted=5 wordsHit=4 xpEarned=60 bestStreak=4
- +364s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +364s tool.client_result tool="companionAct"
- +365s ws.send type="session_state" state="SPEAKING"
- +365s turn.state_changed state="SPEAKING"
- +369s ws.send type="session_state" state="IDLE"
- +369s turn.state_changed state="IDLE"
- +369s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=21 tts="on"
- +369s canvas.draw mode="idle"
- +370s transcript.accepted turnState="IDLE" round=21 transcriptLength=62
- +370s ws.send type="session_state" state="LOADING"
- +370s turn.state_changed state="LOADING"
- +370s ws.send type="session_state" state="PROCESSING"
- +370s turn.state_changed state="PROCESSING"
- +373s tool.called tool="sessionLog" argsKeys=["observation","correct"] hasResult=false
- +373s tool.client_result tool="sessionLog"
- +375s transcript.queued turnState="PROCESSING" round=22 transcriptLength=34
- +376s tool.called tool="sessionLog" argsKeys=["correct","childSaid","observation"] hasResult=true
- +376s tool.client_result tool="sessionLog"
- +378s ws.send type="session_state" state="SPEAKING"
- +378s turn.state_changed state="SPEAKING"
- +380s ws.send type="session_state" state="IDLE"
- +380s turn.state_changed state="IDLE"
- +380s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=22 tts="on"
- +380s canvas.draw mode="idle"
- +399s transcript.accepted turnState="IDLE" round=22 transcriptLength=247
- +399s ws.send type="session_state" state="LOADING"
- +399s turn.state_changed state="LOADING"
- +399s ws.send type="session_state" state="PROCESSING"
- +399s turn.state_changed state="PROCESSING"
- +401s tool.called tool="sessionEnd" argsKeys=["childName","reason"] hasResult=true
- +401s tool.client_result tool="sessionEnd"
- +404s ws.send type="session_state" state="SPEAKING"
- +404s turn.state_changed state="SPEAKING"
- +404s session.ending turnState="SPEAKING" roundNumber=23 isEnding=true childName="Reina" canvasMode="pronunciation" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=221
- +404s ws.send type="session_state" state="IDLE"
- +404s turn.state_changed state="IDLE"
- +404s engine.session_finalized totalAttempts=0 accuracy=0
- +404s engine.progression_computed level=74 totalXP=7335 wordsMastered=29

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 23,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "d5770ab4-99b9-4189-86bc-e1e862b0def1",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 221
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 221,
  "rewardLogEntries": 17
}
```

## Upload
Session saved locally. Upload not configured yet.
