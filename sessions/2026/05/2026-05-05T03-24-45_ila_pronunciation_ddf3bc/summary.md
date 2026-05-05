# Sunny Session Debug Summary

sessionId: ddf3bc23-450c-4ee0-bf10-a1e37f2b4155
date: 2026-05-05T03:24:45.126Z
endedAt: 2026-05-05T03:25:55.288Z
child: Ila
subject: pronunciation
mode: as-child
gitCommit: 8f8e5f8
command: npm run npx
duration_ms: 70162
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: as-child
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: pronunciation
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +37s ws.send type="session_state" state="IDLE"
- +37s turn.state_changed state="IDLE"
- +38s transcript.accepted turnState="IDLE" round=4 transcriptLength=34
- +38s ws.send type="session_state" state="LOADING"
- +38s turn.state_changed state="LOADING"
- +38s ws.send type="session_state" state="PROCESSING"
- +38s turn.state_changed state="PROCESSING"
- +40s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +40s tool.client_result tool="companionAct"
- +40s transcript.queued turnState="PROCESSING" round=5 transcriptLength=5
- +43s transcript.queued turnState="PROCESSING" round=5 transcriptLength=9
- +43s ws.send type="session_state" state="SPEAKING"
- +43s turn.state_changed state="SPEAKING"
- +43s ws.send type="session_state" state="IDLE"
- +43s turn.state_changed state="IDLE"
- +43s transcript.replay turnState="IDLE" round=5 transcriptLength=9
- +43s transcript.accepted turnState="IDLE" round=5 transcriptLength=9
- +43s ws.send type="session_state" state="LOADING"
- +43s turn.state_changed state="LOADING"
- +43s ws.send type="session_state" state="PROCESSING"
- +43s turn.state_changed state="PROCESSING"
- +45s transcript.queued turnState="PROCESSING" round=6 transcriptLength=8
- +47s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +47s tool.client_result tool="companionAct"
- +47s transcript.queued turnState="PROCESSING" round=6 transcriptLength=7
- +47s ws.send type="session_state" state="SPEAKING"
- +47s turn.state_changed state="SPEAKING"
- +47s ws.send type="session_state" state="IDLE"
- +47s turn.state_changed state="IDLE"
- +47s transcript.replay turnState="IDLE" round=6 transcriptLength=7
- +47s transcript.accepted turnState="IDLE" round=6 transcriptLength=7
- +47s ws.send type="session_state" state="LOADING"
- +47s turn.state_changed state="LOADING"
- +47s ws.send type="session_state" state="PROCESSING"
- +47s turn.state_changed state="PROCESSING"
- +49s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +49s tool.client_result tool="companionAct"
- +50s transcript.queued turnState="PROCESSING" round=7 transcriptLength=4
- +51s ws.send type="session_state" state="SPEAKING"
- +51s turn.state_changed state="SPEAKING"
- +51s ws.send type="session_state" state="IDLE"
- +51s turn.state_changed state="IDLE"
- +51s transcript.replay turnState="IDLE" round=7 transcriptLength=4
- +51s transcript.accepted turnState="IDLE" round=7 transcriptLength=4
- +51s ws.send type="session_state" state="LOADING"
- +51s turn.state_changed state="LOADING"
- +51s ws.send type="session_state" state="PROCESSING"
- +51s turn.state_changed state="PROCESSING"
- +53s transcript.queued turnState="PROCESSING" round=8 transcriptLength=12
- +54s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +54s tool.client_result tool="companionAct"
- +57s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +57s tool.client_result tool="sessionStatus"
- +57s transcript.queued turnState="PROCESSING" round=8 transcriptLength=13
- +58s ws.send type="session_state" state="SPEAKING"
- +58s turn.state_changed state="SPEAKING"
- +58s ws.send type="session_state" state="IDLE"
- +58s turn.state_changed state="IDLE"
- +58s transcript.replay turnState="IDLE" round=8 transcriptLength=13
- +58s transcript.accepted turnState="IDLE" round=8 transcriptLength=13
- +58s ws.send type="session_state" state="LOADING"
- +58s turn.state_changed state="LOADING"
- +58s ws.send type="session_state" state="PROCESSING"
- +58s turn.state_changed state="PROCESSING"
- +60s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +60s tool.client_result tool="companionAct"
- +62s ws.send type="session_state" state="SPEAKING"
- +62s turn.state_changed state="SPEAKING"
- +62s ws.send type="session_state" state="IDLE"
- +62s turn.state_changed state="IDLE"
- +67s transcript.accepted turnState="IDLE" round=9 transcriptLength=41
- +67s ws.send type="session_state" state="LOADING"
- +67s turn.state_changed state="LOADING"
- +67s ws.send type="session_state" state="PROCESSING"
- +67s turn.state_changed state="PROCESSING"
- +69s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +69s tool.client_result tool="companionAct"
- +70s session.ending turnState="PROCESSING" roundNumber=10 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=18
- +70s ws.send type="session_state" state="IDLE"
- +70s turn.state_changed state="IDLE"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 10,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "ddf3bc23-450c-4ee0-bf10-a1e37f2b4155",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 18
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 18,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
