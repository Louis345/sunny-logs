# Sunny Session Debug Summary

sessionId: 0cc536c8-c621-4061-b97e-e2beedb44ace
date: 2026-05-04T20:39:15.891Z
endedAt: 2026-05-04T20:40:19.129Z
child: Ila
subject: homework
mode: real
gitCommit: bf2c552
command: npm run npx
duration_ms: 63238
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Ila" companionName="Elli"
- +40s canvas.draw mode="worksheet_pdf"
- +40s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Hey Ila! What's been happening?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +40s canvas.draw mode="idle"
- +40s ws.send type="session_state" state="LOADING"
- +40s turn.state_changed state="LOADING"
- +40s ws.send type="session_state" state="PROCESSING"
- +40s turn.state_changed state="PROCESSING"
- +40s ws.send type="session_state" state="SPEAKING"
- +40s turn.state_changed state="SPEAKING"
- +41s ws.send type="session_state" state="IDLE"
- +41s turn.state_changed state="IDLE"
- +41s session.started sessionType="homework" companionName="Elli"
- +44s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +44s tool.client_result tool="companionAct"
- +49s ws.send type="session_state" state="LOADING"
- +49s turn.state_changed state="LOADING"
- +49s ws.send type="session_state" state="PROCESSING"
- +49s turn.state_changed state="PROCESSING"
- +52s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +52s tool.client_result tool="companionAct"
- +54s ws.send type="session_state" state="SPEAKING"
- +54s turn.state_changed state="SPEAKING"
- +62s ws.send type="session_state" state="IDLE"
- +62s turn.state_changed state="IDLE"
- +63s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=6

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "0cc536c8-c621-4061-b97e-e2beedb44ace",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 6
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 6,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
