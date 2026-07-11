# Sunny Session Debug Summary

sessionId: bec69aba-9f7b-4a1f-ace7-d6b059c4b4f5
date: 2026-07-11T23:05:53.849Z
endedAt: 2026-07-11T23:20:39.170Z
child: Reina
subject: homework
mode: real
gitCommit: 6e85b75
command: npm run npx
duration_ms: 885321
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: 
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false chartChildId="reina"
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +0s companion.greeting_generated source="live_homework_context" words=9
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Your first challenge is ready. Want to try it?" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s ws.send type="session_state" state="LOADING"
- +1s turn.state_changed state="LOADING"
- +1s ws.send type="session_state" state="PROCESSING"
- +1s turn.state_changed state="PROCESSING"
- +1s ws.send type="session_state" state="SPEAKING"
- +1s turn.state_changed state="SPEAKING"
- +2s ws.send type="session_state" state="IDLE"
- +2s turn.state_changed state="IDLE"
- +2s session.started sessionType="homework" companionName="Matilda"
- +848s transcript.accepted turnState="IDLE" round=0 transcriptLength=124
- +848s ws.send type="session_state" state="LOADING"
- +848s turn.state_changed state="LOADING"
- +848s ws.send type="session_state" state="PROCESSING"
- +848s turn.state_changed state="PROCESSING"
- +851s tool.called tool="expressCompanion" argsKeys=["emote","intensity"] hasResult=true
- +851s tool.client_result tool="expressCompanion"
- +853s ws.send type="session_state" state="SPEAKING"
- +853s turn.state_changed state="SPEAKING"
- +854s ws.send type="session_state" state="IDLE"
- +854s turn.state_changed state="IDLE"
- +854s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=1 tts="on"
- +854s canvas.draw mode="idle"
- +860s transcript.accepted turnState="IDLE" round=1 transcriptLength=170
- +860s ws.send type="session_state" state="LOADING"
- +860s turn.state_changed state="LOADING"
- +860s ws.send type="session_state" state="PROCESSING"
- +860s turn.state_changed state="PROCESSING"
- +863s ws.send type="session_state" state="SPEAKING"
- +863s turn.state_changed state="SPEAKING"
- +869s ws.send type="session_state" state="IDLE"
- +869s turn.state_changed state="IDLE"
- +869s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=2 tts="on"
- +869s canvas.draw mode="idle"
- +869s transcript.accepted turnState="IDLE" round=2 transcriptLength=48
- +869s ws.send type="session_state" state="LOADING"
- +869s turn.state_changed state="LOADING"
- +869s ws.send type="session_state" state="PROCESSING"
- +869s turn.state_changed state="PROCESSING"
- +870s transcript.queued turnState="PROCESSING" round=3 transcriptLength=66
- +871s ws.send type="session_state" state="SPEAKING"
- +871s turn.state_changed state="SPEAKING"
- +877s ws.send type="session_state" state="IDLE"
- +877s turn.state_changed state="IDLE"
- +877s transcript.replay turnState="IDLE" round=3 transcriptLength=66
- +877s transcript.accepted turnState="IDLE" round=3 transcriptLength=66
- +877s ws.send type="session_state" state="LOADING"
- +877s turn.state_changed state="LOADING"
- +877s ws.send type="session_state" state="PROCESSING"
- +877s turn.state_changed state="PROCESSING"
- +878s transcript.queued turnState="PROCESSING" round=4 transcriptLength=45
- +880s ws.send type="session_state" state="SPEAKING"
- +880s turn.state_changed state="SPEAKING"
- +884s session.ending turnState="SPEAKING" roundNumber=4 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=45 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=8
- +884s ws.send type="session_state" state="IDLE"
- +884s turn.state_changed state="IDLE"
- +884s engine.session_finalized totalAttempts=0 accuracy=0
- +884s engine.progression_computed level=78 totalXP=7755 wordsMastered=33

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 4,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "bec69aba-9f7b-4a1f-ace7-d6b059c4b4f5",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 8
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 8,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
