# Sunny Session Debug Summary

sessionId: 04b66974-07c7-4a26-83a0-6e66979f191f
date: 2026-05-03T21:42:46.119Z
endedAt: 2026-05-03T21:47:20.078Z
child: Ila
subject: spelling
mode: as-child
gitCommit: 8e7077a
command: npm run npx
duration_ms: 273959
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
- +5s canvas.draw mode="worksheet_pdf"
- +5s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Ila! Good to see you — what's new?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +5s canvas.draw mode="idle"
- +5s ws.send type="session_state" state="LOADING"
- +5s turn.state_changed state="LOADING"
- +5s ws.send type="session_state" state="PROCESSING"
- +5s turn.state_changed state="PROCESSING"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +5s ws.send type="session_state" state="IDLE"
- +5s turn.state_changed state="IDLE"
- +5s session.started sessionType="spelling" companionName="Elli"
- +106s transcript.accepted turnState="IDLE" round=0 transcriptLength=16
- +106s ws.send type="session_state" state="LOADING"
- +106s turn.state_changed state="LOADING"
- +106s ws.send type="session_state" state="PROCESSING"
- +106s turn.state_changed state="PROCESSING"
- +108s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +108s tool.client_result tool="companionAct"
- +110s ws.send type="session_state" state="SPEAKING"
- +110s turn.state_changed state="SPEAKING"
- +110s ws.send type="session_state" state="IDLE"
- +110s turn.state_changed state="IDLE"
- +274s session.ending turnState="IDLE" roundNumber=1 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=2

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 1,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "04b66974-07c7-4a26-83a0-6e66979f191f",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 2
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 2,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
