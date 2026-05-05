# Sunny Session Debug Summary

sessionId: a6246606-78b9-4f02-afc5-a86d3e03c1f8
date: 2026-05-02T21:52:35.272Z
endedAt: 2026-05-02T22:26:15.172Z
child: Reina
subject: homework
mode: as-child
gitCommit: 8e7077a
command: npm run npx
duration_ms: 2019900
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: as-child
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +5s canvas.draw mode="worksheet_pdf"
- +5s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Reina! How's your night going?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +5s canvas.draw mode="idle"
- +6s ws.send type="session_state" state="LOADING"
- +6s turn.state_changed state="LOADING"
- +6s ws.send type="session_state" state="PROCESSING"
- +6s turn.state_changed state="PROCESSING"
- +6s ws.send type="session_state" state="SPEAKING"
- +6s turn.state_changed state="SPEAKING"
- +7s ws.send type="session_state" state="IDLE"
- +7s turn.state_changed state="IDLE"
- +7s session.started sessionType="homework" companionName="Matilda"
- +769s transcript.accepted turnState="IDLE" round=0 transcriptLength=5
- +769s ws.send type="session_state" state="LOADING"
- +769s turn.state_changed state="LOADING"
- +769s ws.send type="session_state" state="PROCESSING"
- +769s turn.state_changed state="PROCESSING"
- +771s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +771s tool.client_result tool="companionAct"
- +773s ws.send type="session_state" state="SPEAKING"
- +773s turn.state_changed state="SPEAKING"
- +780s ws.send type="session_state" state="IDLE"
- +780s turn.state_changed state="IDLE"
- +1258s transcript.accepted turnState="IDLE" round=1 transcriptLength=39
- +1258s ws.send type="session_state" state="LOADING"
- +1258s turn.state_changed state="LOADING"
- +1258s ws.send type="session_state" state="PROCESSING"
- +1258s turn.state_changed state="PROCESSING"
- +1260s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +1260s tool.client_result tool="companionAct"
- +1262s ws.send type="session_state" state="SPEAKING"
- +1262s turn.state_changed state="SPEAKING"
- +1265s ws.send type="session_state" state="IDLE"
- +1265s turn.state_changed state="IDLE"
- +1322s transcript.accepted turnState="IDLE" round=2 transcriptLength=8
- +1322s ws.send type="session_state" state="LOADING"
- +1322s turn.state_changed state="LOADING"
- +1322s ws.send type="session_state" state="PROCESSING"
- +1322s turn.state_changed state="PROCESSING"
- +1324s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +1324s tool.client_result tool="companionAct"
- +1326s ws.send type="session_state" state="SPEAKING"
- +1326s turn.state_changed state="SPEAKING"
- +1331s ws.send type="session_state" state="IDLE"
- +1331s turn.state_changed state="IDLE"
- +1996s transcript.accepted turnState="IDLE" round=3 transcriptLength=278
- +1996s ws.send type="session_state" state="LOADING"
- +1996s turn.state_changed state="LOADING"
- +1996s ws.send type="session_state" state="PROCESSING"
- +1996s turn.state_changed state="PROCESSING"
- +1998s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +1998s tool.client_result tool="companionAct"
- +2000s ws.send type="session_state" state="SPEAKING"
- +2000s turn.state_changed state="SPEAKING"
- +2009s ws.send type="session_state" state="IDLE"
- +2009s turn.state_changed state="IDLE"
- +2020s session.ending turnState="IDLE" roundNumber=4 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=8

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 4,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "a6246606-78b9-4f02-afc5-a86d3e03c1f8",
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
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 8,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
