# Sunny Session Debug Summary

sessionId: 03cfbafa-95e3-4956-a835-e95f731e8fe8
date: 2026-04-30T23:10:30.328Z
endedAt: 2026-04-30T23:12:23.006Z
child: Reina
subject: homework
mode: default
gitCommit: 484e23a
command: npm run npx
duration_ms: 112678
result: completed

## Env Flags
- TTS_ENABLED: 
- SUNNY_MODE: 
- SUNNY_CHILD: 
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: 
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +43s canvas.draw mode="worksheet_pdf"
- +43s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Hey Reina! What's been happening?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +43s canvas.draw mode="idle"
- +44s ws.send type="session_state" state="LOADING"
- +44s turn.state_changed state="LOADING"
- +44s ws.send type="session_state" state="PROCESSING"
- +44s turn.state_changed state="PROCESSING"
- +44s ws.send type="session_state" state="SPEAKING"
- +44s turn.state_changed state="SPEAKING"
- +45s ws.send type="session_state" state="IDLE"
- +45s turn.state_changed state="IDLE"
- +45s session.started sessionType="homework" companionName="Matilda"
- +50s transcript.accepted turnState="IDLE" round=0 transcriptLength=5
- +50s ws.send type="session_state" state="LOADING"
- +50s turn.state_changed state="LOADING"
- +50s ws.send type="session_state" state="PROCESSING"
- +50s turn.state_changed state="PROCESSING"
- +52s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +52s tool.client_result tool="companionAct"
- +54s ws.send type="session_state" state="SPEAKING"
- +54s turn.state_changed state="SPEAKING"
- +61s ws.send type="session_state" state="IDLE"
- +61s turn.state_changed state="IDLE"
- +61s turn.barge_in stateBefore="SPEAKING" turnState="IDLE" round=1 tts="on"
- +61s canvas.draw mode="idle"
- +64s transcript.accepted turnState="IDLE" round=1 transcriptLength=29
- +64s ws.send type="session_state" state="LOADING"
- +64s turn.state_changed state="LOADING"
- +64s ws.send type="session_state" state="PROCESSING"
- +64s turn.state_changed state="PROCESSING"
- +66s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +66s tool.client_result tool="companionAct"
- +68s ws.send type="session_state" state="SPEAKING"
- +68s turn.state_changed state="SPEAKING"
- +74s session.ending turnState="SPEAKING" roundNumber=2 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=4
- +74s ws.send type="session_state" state="IDLE"
- +74s turn.state_changed state="IDLE"
- +74s engine.session_finalized totalAttempts=0 accuracy=0
- +74s engine.progression_computed level=15 totalXP=1410 wordsMastered=3

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "03cfbafa-95e3-4956-a835-e95f731e8fe8",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 4
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 4,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
