# Sunny Session Debug Summary

sessionId: 3c4eceae-6435-4e0d-b8f7-d2c91bbe85f2
date: 2026-05-22T11:52:55.218Z
endedAt: 2026-05-22T12:03:34.499Z
child: Reina
subject: homework
mode: real
gitCommit: cc49f2b
command: npm run npx
duration_ms: 639281
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
- +525s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=28 tts="on"
- +525s canvas.draw mode="idle"
- +525s transcript.accepted turnState="IDLE" round=28 transcriptLength=31
- +525s ws.send type="session_state" state="LOADING"
- +525s turn.state_changed state="LOADING"
- +525s ws.send type="session_state" state="PROCESSING"
- +525s turn.state_changed state="PROCESSING"
- +529s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +529s tool.client_result tool="companionAct"
- +531s ws.send type="session_state" state="SPEAKING"
- +531s turn.state_changed state="SPEAKING"
- +543s ws.send type="session_state" state="IDLE"
- +543s turn.state_changed state="IDLE"
- +544s transcript.accepted turnState="IDLE" round=29 transcriptLength=114
- +544s ws.send type="session_state" state="LOADING"
- +544s turn.state_changed state="LOADING"
- +544s ws.send type="session_state" state="PROCESSING"
- +544s turn.state_changed state="PROCESSING"
- +548s transcript.queued turnState="PROCESSING" round=30 transcriptLength=148
- +549s tool.called tool="recordProductIssue" argsKeys=["issueType","severity","childUtterance","evidenceText","confidence","source"] hasResult=true
- +549s tool.client_result tool="recordProductIssue"
- +554s ws.send type="session_state" state="SPEAKING"
- +554s turn.state_changed state="SPEAKING"
- +566s ws.send type="session_state" state="IDLE"
- +566s turn.state_changed state="IDLE"
- +566s transcript.replay turnState="IDLE" round=30 transcriptLength=148
- +566s transcript.accepted turnState="IDLE" round=30 transcriptLength=148
- +566s ws.send type="session_state" state="LOADING"
- +566s turn.state_changed state="LOADING"
- +566s ws.send type="session_state" state="PROCESSING"
- +566s turn.state_changed state="PROCESSING"
- +569s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +569s tool.client_result tool="companionAct"
- +571s transcript.queued turnState="PROCESSING" round=31 transcriptLength=26
- +574s ws.send type="session_state" state="SPEAKING"
- +574s turn.state_changed state="SPEAKING"
- +588s ws.send type="session_state" state="IDLE"
- +588s turn.state_changed state="IDLE"
- +588s transcript.replay turnState="IDLE" round=31 transcriptLength=26
- +588s transcript.accepted turnState="IDLE" round=31 transcriptLength=26
- +588s ws.send type="session_state" state="LOADING"
- +588s turn.state_changed state="LOADING"
- +588s ws.send type="session_state" state="PROCESSING"
- +588s turn.state_changed state="PROCESSING"
- +591s transcript.queued turnState="PROCESSING" round=32 transcriptLength=28
- +593s tool.called tool="recordProductIssue" argsKeys=["issueType","severity","childUtterance","evidenceText","confidence","source"] hasResult=true
- +593s tool.client_result tool="recordProductIssue"
- +595s ws.send type="session_state" state="SPEAKING"
- +595s turn.state_changed state="SPEAKING"
- +606s ws.send type="session_state" state="IDLE"
- +606s turn.state_changed state="IDLE"
- +606s transcript.replay turnState="IDLE" round=32 transcriptLength=28
- +606s transcript.accepted turnState="IDLE" round=32 transcriptLength=28
- +606s ws.send type="session_state" state="LOADING"
- +606s turn.state_changed state="LOADING"
- +606s ws.send type="session_state" state="PROCESSING"
- +606s turn.state_changed state="PROCESSING"
- +609s transcript.queued turnState="PROCESSING" round=33 transcriptLength=37
- +610s tool.called tool="recordProductIssue" argsKeys=["issueType","severity","childUtterance","evidenceText","confidence","source"] hasResult=true
- +610s tool.client_result tool="recordProductIssue"
- +614s ws.send type="session_state" state="SPEAKING"
- +614s turn.state_changed state="SPEAKING"
- +624s ws.send type="session_state" state="IDLE"
- +624s turn.state_changed state="IDLE"
- +624s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=33 tts="on"
- +624s canvas.draw mode="idle"
- +626s transcript.accepted turnState="IDLE" round=33 transcriptLength=55
- +626s ws.send type="session_state" state="LOADING"
- +626s turn.state_changed state="LOADING"
- +626s ws.send type="session_state" state="PROCESSING"
- +626s turn.state_changed state="PROCESSING"
- +628s tool.called tool="sessionEnd" argsKeys=["childName","reason"] hasResult=true
- +628s tool.client_result tool="sessionEnd"
- +630s ws.send type="session_state" state="SPEAKING"
- +630s turn.state_changed state="SPEAKING"
- +630s session.ending turnState="SPEAKING" roundNumber=34 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=105
- +630s ws.send type="session_state" state="IDLE"
- +630s turn.state_changed state="IDLE"
- +630s engine.session_finalized totalAttempts=82 accuracy=0.7560975609756098
- +630s engine.progression_computed level=102 totalXP=10190 wordsMastered=41

## Activity Evidence
- activityReadings: 219
- activityAttemptReadings: 189
- activityCorrectReadings: 163

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 34,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "3c4eceae-6435-4e0d-b8f7-d2c91bbe85f2",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 105
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 105,
  "rewardLogEntries": 32
}
```

## Upload
Session saved locally. Upload not configured yet.
