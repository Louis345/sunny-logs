# Sunny Session Debug Summary

sessionId: 3cc9ba35-c0c0-4f82-99f6-5132dc4a71dd
date: 2026-05-04T02:37:50.338Z
endedAt: 2026-05-04T02:39:17.743Z
child: Ila
subject: spelling
mode: as-child
gitCommit: bf2c552
command: npm run npx
duration_ms: 87405
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: as-child
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: onboarding
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +23s turn.state_changed state="LOADING"
- +23s ws.send type="session_state" state="PROCESSING"
- +23s turn.state_changed state="PROCESSING"
- +25s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +25s tool.client_result tool="companionAct"
- +27s ws.send type="session_state" state="SPEAKING"
- +27s turn.state_changed state="SPEAKING"
- +27s ws.send type="session_state" state="IDLE"
- +27s turn.state_changed state="IDLE"
- +38s transcript.accepted turnState="IDLE" round=2 transcriptLength=58
- +38s ws.send type="session_state" state="LOADING"
- +38s turn.state_changed state="LOADING"
- +38s ws.send type="session_state" state="PROCESSING"
- +38s turn.state_changed state="PROCESSING"
- +43s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +43s tool.client_result tool="companionAct"
- +45s ws.send type="session_state" state="SPEAKING"
- +45s turn.state_changed state="SPEAKING"
- +45s ws.send type="session_state" state="IDLE"
- +45s turn.state_changed state="IDLE"
- +54s transcript.accepted turnState="IDLE" round=3 transcriptLength=21
- +54s ws.send type="session_state" state="LOADING"
- +54s turn.state_changed state="LOADING"
- +54s ws.send type="session_state" state="PROCESSING"
- +54s turn.state_changed state="PROCESSING"
- +57s transcript.queued turnState="PROCESSING" round=4 transcriptLength=4
- +57s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +57s tool.client_result tool="companionAct"
- +58s ws.send type="session_state" state="SPEAKING"
- +58s turn.state_changed state="SPEAKING"
- +58s ws.send type="session_state" state="IDLE"
- +58s turn.state_changed state="IDLE"
- +58s transcript.replay turnState="IDLE" round=4 transcriptLength=4
- +58s transcript.accepted turnState="IDLE" round=4 transcriptLength=4
- +58s ws.send type="session_state" state="LOADING"
- +58s turn.state_changed state="LOADING"
- +58s ws.send type="session_state" state="PROCESSING"
- +58s turn.state_changed state="PROCESSING"
- +61s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +61s tool.client_result tool="companionAct"
- +62s ws.send type="session_state" state="SPEAKING"
- +62s turn.state_changed state="SPEAKING"
- +62s ws.send type="session_state" state="IDLE"
- +62s turn.state_changed state="IDLE"
- +62s transcript.accepted turnState="IDLE" round=5 transcriptLength=63
- +62s ws.send type="session_state" state="LOADING"
- +62s turn.state_changed state="LOADING"
- +62s ws.send type="session_state" state="PROCESSING"
- +62s turn.state_changed state="PROCESSING"
- +67s transcript.queued turnState="PROCESSING" round=6 transcriptLength=27
- +69s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +69s tool.client_result tool="companionAct"
- +70s ws.send type="session_state" state="SPEAKING"
- +70s turn.state_changed state="SPEAKING"
- +70s ws.send type="session_state" state="IDLE"
- +70s turn.state_changed state="IDLE"
- +70s transcript.replay turnState="IDLE" round=6 transcriptLength=27
- +70s transcript.accepted turnState="IDLE" round=6 transcriptLength=27
- +70s ws.send type="session_state" state="LOADING"
- +70s turn.state_changed state="LOADING"
- +70s ws.send type="session_state" state="PROCESSING"
- +70s turn.state_changed state="PROCESSING"
- +73s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +73s tool.client_result tool="companionAct"
- +74s ws.send type="session_state" state="SPEAKING"
- +74s turn.state_changed state="SPEAKING"
- +74s ws.send type="session_state" state="IDLE"
- +74s turn.state_changed state="IDLE"
- +75s transcript.accepted turnState="IDLE" round=7 transcriptLength=41
- +75s ws.send type="session_state" state="LOADING"
- +75s turn.state_changed state="LOADING"
- +75s ws.send type="session_state" state="PROCESSING"
- +75s turn.state_changed state="PROCESSING"
- +77s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +77s tool.client_result tool="companionAct"
- +81s ws.send type="session_state" state="SPEAKING"
- +81s turn.state_changed state="SPEAKING"
- +81s ws.send type="session_state" state="IDLE"
- +81s turn.state_changed state="IDLE"
- +87s session.ending turnState="IDLE" roundNumber=8 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=16

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 8,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "3cc9ba35-c0c0-4f82-99f6-5132dc4a71dd",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 16
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 16,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
