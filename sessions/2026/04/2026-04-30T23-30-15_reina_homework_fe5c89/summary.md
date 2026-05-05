# Sunny Session Debug Summary

sessionId: fe5c8901-d043-42d2-b5dc-d29f014ff98b
date: 2026-04-30T23:30:15.904Z
endedAt: 2026-04-30T23:40:57.532Z
child: Reina
subject: homework
mode: default
gitCommit: 484e23a
command: npm run npx
duration_ms: 641628
result: completed

## Env Flags
- TTS_ENABLED: 
- SUNNY_MODE: 
- SUNNY_CHILD: 
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: 
- SUNNY_STATELESS: 

## Timeline
- +466s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +466s tool.client_result tool="companionAct"
- +467s ws.send type="session_state" state="SPEAKING"
- +467s turn.state_changed state="SPEAKING"
- +480s ws.send type="session_state" state="IDLE"
- +480s turn.state_changed state="IDLE"
- +482s transcript.accepted turnState="IDLE" round=34 transcriptLength=9
- +482s ws.send type="session_state" state="LOADING"
- +482s turn.state_changed state="LOADING"
- +482s ws.send type="session_state" state="PROCESSING"
- +482s turn.state_changed state="PROCESSING"
- +484s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +484s tool.client_result tool="companionAct"
- +486s ws.send type="session_state" state="SPEAKING"
- +486s turn.state_changed state="SPEAKING"
- +494s ws.send type="session_state" state="IDLE"
- +494s turn.state_changed state="IDLE"
- +494s transcript.accepted turnState="IDLE" round=35 transcriptLength=45
- +494s ws.send type="session_state" state="LOADING"
- +494s turn.state_changed state="LOADING"
- +494s ws.send type="session_state" state="PROCESSING"
- +494s turn.state_changed state="PROCESSING"
- +496s tool.called tool="expressCompanion" argsKeys=["emote"] hasResult=true
- +496s tool.client_result tool="expressCompanion"
- +497s ws.send type="session_state" state="SPEAKING"
- +497s turn.state_changed state="SPEAKING"
- +503s ws.send type="session_state" state="IDLE"
- +503s turn.state_changed state="IDLE"
- +503s transcript.accepted turnState="IDLE" round=36 transcriptLength=21
- +503s ws.send type="session_state" state="LOADING"
- +503s turn.state_changed state="LOADING"
- +503s ws.send type="session_state" state="PROCESSING"
- +503s turn.state_changed state="PROCESSING"
- +505s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +505s tool.client_result tool="companionAct"
- +507s ws.send type="session_state" state="SPEAKING"
- +507s turn.state_changed state="SPEAKING"
- +511s ws.send type="session_state" state="IDLE"
- +511s turn.state_changed state="IDLE"
- +517s transcript.accepted turnState="IDLE" round=37 transcriptLength=20
- +517s ws.send type="session_state" state="LOADING"
- +517s turn.state_changed state="LOADING"
- +517s ws.send type="session_state" state="PROCESSING"
- +517s turn.state_changed state="PROCESSING"
- +520s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +520s tool.client_result tool="companionAct"
- +521s ws.send type="session_state" state="SPEAKING"
- +521s turn.state_changed state="SPEAKING"
- +526s ws.send type="session_state" state="IDLE"
- +526s turn.state_changed state="IDLE"
- +527s transcript.accepted turnState="IDLE" round=38 transcriptLength=56
- +527s ws.send type="session_state" state="LOADING"
- +527s turn.state_changed state="LOADING"
- +527s ws.send type="session_state" state="PROCESSING"
- +527s turn.state_changed state="PROCESSING"
- +529s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +529s tool.client_result tool="companionAct"
- +530s ws.send type="session_state" state="SPEAKING"
- +530s turn.state_changed state="SPEAKING"
- +538s ws.send type="session_state" state="IDLE"
- +538s turn.state_changed state="IDLE"
- +543s transcript.accepted turnState="IDLE" round=39 transcriptLength=51
- +543s ws.send type="session_state" state="LOADING"
- +543s turn.state_changed state="LOADING"
- +543s ws.send type="session_state" state="PROCESSING"
- +543s turn.state_changed state="PROCESSING"
- +545s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +545s tool.client_result tool="companionAct"
- +547s ws.send type="session_state" state="SPEAKING"
- +547s turn.state_changed state="SPEAKING"
- +554s ws.send type="session_state" state="IDLE"
- +554s turn.state_changed state="IDLE"
- +580s transcript.accepted turnState="IDLE" round=40 transcriptLength=441
- +580s ws.send type="session_state" state="LOADING"
- +580s turn.state_changed state="LOADING"
- +580s session.ending turnState="LOADING" roundNumber=40 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=447
- +580s ws.send type="session_state" state="IDLE"
- +580s turn.state_changed state="IDLE"
- +580s engine.session_finalized totalAttempts=0 accuracy=0
- +580s engine.progression_computed level=17 totalXP=1600 wordsMastered=3

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 40,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "fe5c8901-d043-42d2-b5dc-d29f014ff98b",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 447
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 447,
  "rewardLogEntries": 31
}
```

## Upload
Session saved locally. Upload not configured yet.
