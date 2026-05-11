# Sunny Session Debug Summary

sessionId: 626f60f2-b0c4-42bc-bdc1-ef028894ac5b
date: 2026-05-11T22:43:06.441Z
endedAt: 2026-05-11T22:44:48.121Z
child: Reina
subject: homework
mode: as-child
gitCommit: 7bbbafb
command: npm run npx
duration_ms: 101680
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
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Reina! How's your night going?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
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
- +34s transcript.accepted turnState="IDLE" round=0 transcriptLength=6
- +34s ws.send type="session_state" state="LOADING"
- +34s turn.state_changed state="LOADING"
- +34s ws.send type="session_state" state="PROCESSING"
- +34s turn.state_changed state="PROCESSING"
- +35s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +35s tool.client_result tool="sessionStatus"
- +37s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +37s tool.client_result tool="companionAct"
- +40s ws.send type="session_state" state="SPEAKING"
- +40s turn.state_changed state="SPEAKING"
- +49s ws.send type="session_state" state="IDLE"
- +49s turn.state_changed state="IDLE"
- +74s transcript.accepted turnState="IDLE" round=1 transcriptLength=35
- +74s ws.send type="session_state" state="LOADING"
- +74s turn.state_changed state="LOADING"
- +74s ws.send type="session_state" state="PROCESSING"
- +74s turn.state_changed state="PROCESSING"
- +76s ws.send type="session_state" state="SPEAKING"
- +76s turn.state_changed state="SPEAKING"
- +83s ws.send type="session_state" state="IDLE"
- +83s turn.state_changed state="IDLE"
- +102s session.ending turnState="IDLE" roundNumber=2 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=4

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "626f60f2-b0c4-42bc-bdc1-ef028894ac5b",
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
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 4,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
