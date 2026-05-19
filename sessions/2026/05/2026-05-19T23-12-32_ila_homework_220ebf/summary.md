# Sunny Session Debug Summary

sessionId: 220ebffe-30bf-4a5a-99bd-a274bd0755aa
date: 2026-05-19T23:12:32.527Z
endedAt: 2026-05-19T23:19:23.106Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 410579
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
- +341s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="pair" wordIndex=8 attempt=1
- +341s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +341s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=8
- +342s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +342s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +342s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +342s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=1 word="pair" bonusMultiplier=1 wordIndex=8
- +342s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +342s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +342s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=9
- +349s transcript.accepted turnState="IDLE" round=31 transcriptLength=125
- +349s ws.send type="session_state" state="LOADING"
- +349s turn.state_changed state="LOADING"
- +349s ws.send type="session_state" state="IDLE"
- +349s turn.state_changed state="IDLE"
- +350s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=10
- +354s transcript.accepted turnState="IDLE" round=32 transcriptLength=25
- +354s ws.send type="session_state" state="LOADING"
- +354s turn.state_changed state="LOADING"
- +354s ws.send type="session_state" state="IDLE"
- +354s turn.state_changed state="IDLE"
- +362s transcript.accepted turnState="IDLE" round=33 transcriptLength=88
- +362s ws.send type="session_state" state="LOADING"
- +362s turn.state_changed state="LOADING"
- +362s ws.send type="session_state" state="IDLE"
- +362s turn.state_changed state="IDLE"
- +364s transcript.accepted turnState="IDLE" round=34 transcriptLength=121
- +364s ws.send type="session_state" state="LOADING"
- +364s turn.state_changed state="LOADING"
- +364s ws.send type="session_state" state="IDLE"
- +364s turn.state_changed state="IDLE"
- +367s transcript.accepted turnState="IDLE" round=35 transcriptLength=151
- +367s ws.send type="session_state" state="LOADING"
- +367s turn.state_changed state="LOADING"
- +367s ws.send type="session_state" state="IDLE"
- +367s turn.state_changed state="IDLE"
- +371s transcript.accepted turnState="IDLE" round=36 transcriptLength=200
- +371s ws.send type="session_state" state="LOADING"
- +371s turn.state_changed state="LOADING"
- +371s ws.send type="session_state" state="IDLE"
- +371s turn.state_changed state="IDLE"
- +371s flow_game.voice_control game="pronunciation" type="voice_control"
- +374s transcript.accepted turnState="IDLE" round=37 transcriptLength=238
- +374s ws.send type="session_state" state="LOADING"
- +374s turn.state_changed state="LOADING"
- +374s ws.send type="session_state" state="PROCESSING"
- +374s turn.state_changed state="PROCESSING"
- +377s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +377s tool.client_result tool="companionAct"
- +378s transcript.queued turnState="PROCESSING" round=38 transcriptLength=261
- +380s ws.send type="session_state" state="SPEAKING"
- +380s turn.state_changed state="SPEAKING"
- +380s ws.send type="session_state" state="IDLE"
- +380s turn.state_changed state="IDLE"
- +380s transcript.replay turnState="IDLE" round=38 transcriptLength=261
- +380s transcript.accepted turnState="IDLE" round=38 transcriptLength=261
- +380s ws.send type="session_state" state="LOADING"
- +380s turn.state_changed state="LOADING"
- +380s ws.send type="session_state" state="PROCESSING"
- +380s turn.state_changed state="PROCESSING"
- +384s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +384s tool.client_result tool="companionAct"
- +386s ws.send type="session_state" state="SPEAKING"
- +386s turn.state_changed state="SPEAKING"
- +395s ws.send type="session_state" state="IDLE"
- +395s turn.state_changed state="IDLE"
- +397s transcript.accepted turnState="IDLE" round=39 transcriptLength=47
- +397s ws.send type="session_state" state="LOADING"
- +397s turn.state_changed state="LOADING"
- +397s ws.send type="session_state" state="PROCESSING"
- +397s turn.state_changed state="PROCESSING"
- +401s tool.called tool="sessionEnd" argsKeys=["childName","reason"] hasResult=true
- +401s tool.client_result tool="sessionEnd"
- +402s ws.send type="session_state" state="SPEAKING"
- +402s turn.state_changed state="SPEAKING"
- +402s session.ending turnState="SPEAKING" roundNumber=40 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=73
- +402s ws.send type="session_state" state="IDLE"
- +402s turn.state_changed state="IDLE"
- +402s engine.session_finalized totalAttempts=52 accuracy=0.8846153846153846
- +402s engine.progression_computed level=96 totalXP=9515 wordsMastered=20

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 40,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "220ebffe-30bf-4a5a-99bd-a274bd0755aa",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 73
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 73,
  "rewardLogEntries": 17
}
```

## Upload
Session saved locally. Upload not configured yet.
