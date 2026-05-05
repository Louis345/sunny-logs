# Sunny Session Debug Summary

sessionId: ed2ce53b-bf8b-4cce-afbd-93c249df28da
date: 2026-05-05T00:15:36.868Z
endedAt: 2026-05-05T00:23:19.509Z
child: Reina
subject: homework
mode: real
gitCommit: 8f8e5f8
command: npm run npx
duration_ms: 462641
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +313s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +313s tool.client_result tool="companionAct"
- +316s ws.send type="session_state" state="SPEAKING"
- +316s turn.state_changed state="SPEAKING"
- +317s ws.send type="session_state" state="IDLE"
- +317s turn.state_changed state="IDLE"
- +349s transcript.accepted turnState="IDLE" round=25 transcriptLength=160
- +349s ws.send type="session_state" state="LOADING"
- +349s turn.state_changed state="LOADING"
- +349s ws.send type="session_state" state="PROCESSING"
- +349s turn.state_changed state="PROCESSING"
- +350s transcript.queued turnState="PROCESSING" round=26 transcriptLength=5
- +351s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +351s tool.client_result tool="companionAct"
- +355s transcript.queued turnState="PROCESSING" round=26 transcriptLength=21
- +355s tool.called tool="sessionLog" argsKeys=["correct","observation"] hasResult=false
- +355s tool.client_result tool="sessionLog"
- +358s tool.called tool="sessionLog" argsKeys=["correct","childSaid","observation"] hasResult=true
- +358s tool.client_result tool="sessionLog"
- +360s ws.send type="session_state" state="SPEAKING"
- +360s turn.state_changed state="SPEAKING"
- +362s ws.send type="session_state" state="IDLE"
- +362s turn.state_changed state="IDLE"
- +362s transcript.replay turnState="IDLE" round=26 transcriptLength=21
- +362s transcript.accepted turnState="IDLE" round=26 transcriptLength=21
- +362s ws.send type="session_state" state="LOADING"
- +362s turn.state_changed state="LOADING"
- +362s ws.send type="session_state" state="PROCESSING"
- +362s turn.state_changed state="PROCESSING"
- +364s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +364s tool.client_result tool="companionAct"
- +366s ws.send type="session_state" state="SPEAKING"
- +366s turn.state_changed state="SPEAKING"
- +368s ws.send type="session_state" state="IDLE"
- +368s turn.state_changed state="IDLE"
- +385s transcript.accepted turnState="IDLE" round=27 transcriptLength=287
- +385s ws.send type="session_state" state="LOADING"
- +385s turn.state_changed state="LOADING"
- +386s ws.send type="session_state" state="PROCESSING"
- +386s turn.state_changed state="PROCESSING"
- +388s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +388s tool.client_result tool="companionAct"
- +390s ws.send type="session_state" state="SPEAKING"
- +390s turn.state_changed state="SPEAKING"
- +392s ws.send type="session_state" state="IDLE"
- +392s turn.state_changed state="IDLE"
- +397s transcript.accepted turnState="IDLE" round=28 transcriptLength=342
- +397s ws.send type="session_state" state="LOADING"
- +397s turn.state_changed state="LOADING"
- +397s ws.send type="session_state" state="PROCESSING"
- +397s turn.state_changed state="PROCESSING"
- +399s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +399s tool.client_result tool="companionAct"
- +402s ws.send type="session_state" state="SPEAKING"
- +402s turn.state_changed state="SPEAKING"
- +404s ws.send type="session_state" state="IDLE"
- +404s turn.state_changed state="IDLE"
- +407s transcript.accepted turnState="IDLE" round=29 transcriptLength=472
- +407s ws.send type="session_state" state="LOADING"
- +407s turn.state_changed state="LOADING"
- +407s ws.send type="session_state" state="PROCESSING"
- +407s turn.state_changed state="PROCESSING"
- +409s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +409s tool.client_result tool="companionAct"
- +411s ws.send type="session_state" state="SPEAKING"
- +411s turn.state_changed state="SPEAKING"
- +420s ws.send type="session_state" state="IDLE"
- +420s turn.state_changed state="IDLE"
- +423s transcript.accepted turnState="IDLE" round=30 transcriptLength=16
- +423s ws.send type="session_state" state="LOADING"
- +423s turn.state_changed state="LOADING"
- +423s ws.send type="session_state" state="PROCESSING"
- +423s turn.state_changed state="PROCESSING"
- +423s session.ending turnState="PROCESSING" roundNumber=31 isEnding=true childName="Reina" canvasMode="pronunciation" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=166
- +423s ws.send type="session_state" state="IDLE"
- +423s turn.state_changed state="IDLE"
- +423s engine.session_finalized totalAttempts=0 accuracy=0
- +423s engine.progression_computed level=71 totalXP=7030 wordsMastered=26
- +425s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +425s tool.client_result tool="sessionStatus"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 31,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "ed2ce53b-bf8b-4cce-afbd-93c249df28da",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 168
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 168,
  "rewardLogEntries": 1
}
```

## Upload
Session saved locally. Upload not configured yet.
