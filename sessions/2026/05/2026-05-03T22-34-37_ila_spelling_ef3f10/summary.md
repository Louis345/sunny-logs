# Sunny Session Debug Summary

sessionId: ef3f1004-8e93-4fef-95d7-a5c0e01498d4
date: 2026-05-03T22:34:37.426Z
endedAt: 2026-05-03T22:49:43.299Z
child: Ila
subject: spelling
mode: as-child
gitCommit: 8e7077a
command: npm run npx
duration_ms: 905873
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: as-child
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: onboarding
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Ila" companionName="Elli"
- +6s canvas.draw mode="worksheet_pdf"
- +6s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Ila! Good to see you — what's new?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +6s canvas.draw mode="idle"
- +6s ws.send type="session_state" state="LOADING"
- +6s turn.state_changed state="LOADING"
- +6s ws.send type="session_state" state="PROCESSING"
- +6s turn.state_changed state="PROCESSING"
- +6s ws.send type="session_state" state="SPEAKING"
- +6s turn.state_changed state="SPEAKING"
- +6s ws.send type="session_state" state="IDLE"
- +6s turn.state_changed state="IDLE"
- +6s session.started sessionType="spelling" companionName="Elli"
- +39s transcript.accepted turnState="IDLE" round=0 transcriptLength=410
- +39s ws.send type="session_state" state="LOADING"
- +39s turn.state_changed state="LOADING"
- +39s ws.send type="session_state" state="PROCESSING"
- +39s turn.state_changed state="PROCESSING"
- +41s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +41s tool.client_result tool="companionAct"
- +43s ws.send type="session_state" state="SPEAKING"
- +43s turn.state_changed state="SPEAKING"
- +43s ws.send type="session_state" state="IDLE"
- +43s turn.state_changed state="IDLE"
- +58s transcript.accepted turnState="IDLE" round=1 transcriptLength=85
- +58s ws.send type="session_state" state="LOADING"
- +58s turn.state_changed state="LOADING"
- +58s ws.send type="session_state" state="PROCESSING"
- +58s turn.state_changed state="PROCESSING"
- +61s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +61s tool.client_result tool="companionAct"
- +63s ws.send type="session_state" state="SPEAKING"
- +63s turn.state_changed state="SPEAKING"
- +63s ws.send type="session_state" state="IDLE"
- +63s turn.state_changed state="IDLE"
- +64s transcript.accepted turnState="IDLE" round=2 transcriptLength=85
- +64s ws.send type="session_state" state="LOADING"
- +64s turn.state_changed state="LOADING"
- +64s ws.send type="session_state" state="PROCESSING"
- +64s turn.state_changed state="PROCESSING"
- +67s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +67s tool.client_result tool="companionAct"
- +72s ws.send type="session_state" state="SPEAKING"
- +72s turn.state_changed state="SPEAKING"
- +72s ws.send type="session_state" state="IDLE"
- +72s turn.state_changed state="IDLE"
- +74s transcript.accepted turnState="IDLE" round=3 transcriptLength=85
- +74s ws.send type="session_state" state="LOADING"
- +74s turn.state_changed state="LOADING"
- +74s ws.send type="session_state" state="PROCESSING"
- +74s turn.state_changed state="PROCESSING"
- +77s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +77s tool.client_result tool="companionAct"
- +81s ws.send type="session_state" state="SPEAKING"
- +81s turn.state_changed state="SPEAKING"
- +81s ws.send type="session_state" state="IDLE"
- +81s turn.state_changed state="IDLE"
- +906s session.ending turnState="IDLE" roundNumber=4 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=8

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 4,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "ef3f1004-8e93-4fef-95d7-a5c0e01498d4",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
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
