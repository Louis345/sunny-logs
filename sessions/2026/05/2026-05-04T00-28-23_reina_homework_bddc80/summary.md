# Sunny Session Debug Summary

sessionId: bddc80e6-2bd7-40f0-bb16-ac61c570ec77
date: 2026-05-04T00:28:23.170Z
endedAt: 2026-05-04T00:37:32.588Z
child: Reina
subject: homework
mode: as-child
gitCommit: fe66966
command: npm run npx
duration_ms: 549418
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: as-child
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +446s ws.send type="session_state" state="LOADING"
- +446s turn.state_changed state="LOADING"
- +446s ws.send type="session_state" state="IDLE"
- +446s turn.state_changed state="IDLE"
- +448s transcript.accepted turnState="IDLE" round=41 transcriptLength=5
- +448s ws.send type="session_state" state="LOADING"
- +448s turn.state_changed state="LOADING"
- +448s ws.send type="session_state" state="IDLE"
- +448s turn.state_changed state="IDLE"
- +459s transcript.accepted turnState="IDLE" round=42 transcriptLength=47
- +459s ws.send type="session_state" state="LOADING"
- +459s turn.state_changed state="LOADING"
- +459s ws.send type="session_state" state="IDLE"
- +459s turn.state_changed state="IDLE"
- +466s transcript.accepted turnState="IDLE" round=43 transcriptLength=67
- +466s ws.send type="session_state" state="LOADING"
- +466s turn.state_changed state="LOADING"
- +466s ws.send type="session_state" state="IDLE"
- +466s turn.state_changed state="IDLE"
- +474s transcript.accepted turnState="IDLE" round=44 transcriptLength=81
- +474s ws.send type="session_state" state="LOADING"
- +474s turn.state_changed state="LOADING"
- +474s ws.send type="session_state" state="IDLE"
- +474s turn.state_changed state="IDLE"
- +497s transcript.accepted turnState="IDLE" round=45 transcriptLength=76
- +497s ws.send type="session_state" state="LOADING"
- +497s turn.state_changed state="LOADING"
- +497s ws.send type="session_state" state="IDLE"
- +497s turn.state_changed state="IDLE"
- +497s transcript.accepted turnState="IDLE" round=46 transcriptLength=76
- +497s ws.send type="session_state" state="LOADING"
- +497s turn.state_changed state="LOADING"
- +497s ws.send type="session_state" state="IDLE"
- +497s turn.state_changed state="IDLE"
- +507s transcript.accepted turnState="IDLE" round=47 transcriptLength=141
- +507s ws.send type="session_state" state="LOADING"
- +507s turn.state_changed state="LOADING"
- +507s ws.send type="session_state" state="IDLE"
- +507s turn.state_changed state="IDLE"
- +518s transcript.accepted turnState="IDLE" round=48 transcriptLength=183
- +518s ws.send type="session_state" state="LOADING"
- +518s turn.state_changed state="LOADING"
- +518s ws.send type="session_state" state="IDLE"
- +518s turn.state_changed state="IDLE"
- +528s transcript.replay turnState="IDLE" round=49 transcriptLength=242
- +528s transcript.accepted turnState="IDLE" round=49 transcriptLength=242
- +528s ws.send type="session_state" state="LOADING"
- +528s turn.state_changed state="LOADING"
- +528s ws.send type="session_state" state="IDLE"
- +528s turn.state_changed state="IDLE"
- +529s transcript.accepted turnState="IDLE" round=50 transcriptLength=225
- +529s ws.send type="session_state" state="LOADING"
- +529s turn.state_changed state="LOADING"
- +529s ws.send type="session_state" state="PROCESSING"
- +529s turn.state_changed state="PROCESSING"
- +530s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +530s tool.client_result tool="companionAct"
- +533s ws.send type="session_state" state="SPEAKING"
- +533s turn.state_changed state="SPEAKING"
- +534s ws.send type="session_state" state="IDLE"
- +534s turn.state_changed state="IDLE"
- +539s transcript.accepted turnState="IDLE" round=51 transcriptLength=10
- +539s ws.send type="session_state" state="LOADING"
- +539s turn.state_changed state="LOADING"
- +539s ws.send type="session_state" state="PROCESSING"
- +539s turn.state_changed state="PROCESSING"
- +541s tool.called tool="launchGame" argsKeys=["name","type","word"] hasResult=true
- +541s tool.client_result tool="launchGame"
- +543s tool.called tool="launchGame" argsKeys=["name","type","word"] hasResult=true
- +543s tool.client_result tool="launchGame"
- +543s ws.send type="session_state" state="WORD_BUILDER"
- +543s turn.state_changed state="WORD_BUILDER"
- +543s canvas.draw mode="word-builder" canvasRevision=1
- +545s ws.send type="session_state" state="SPEAKING"
- +545s turn.state_changed state="SPEAKING"
- +549s ws.send type="session_state" state="WORD_BUILDER"
- +549s turn.state_changed state="WORD_BUILDER"
- +549s session.ending turnState="WORD_BUILDER" roundNumber=52 isEnding=true childName="Reina" canvasMode="word-builder" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=true wbRound=1 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=167
- +549s ws.send type="session_state" state="IDLE"
- +549s turn.state_changed state="IDLE"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 52,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "bddc80e6-2bd7-40f0-bb16-ac61c570ec77",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 167
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 167,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
