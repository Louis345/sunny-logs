# Sunny Session Debug Summary

sessionId: 613dda19-2129-47fc-9b59-455d453e6882
date: 2026-05-03T22:40:28.521Z
endedAt: 2026-05-03T22:44:12.044Z
child: Ila
subject: spelling
mode: as-child
gitCommit: 8e7077a
command: npm run npx
duration_ms: 223523
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
- +10s canvas.draw mode="worksheet_pdf"
- +10s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="🌟" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Ila! Good to see you — what's new?" goodbye="Bye Ila! You did amazing today. I'm so proud of you! 🌟" debugBrowserTts=false debugMode=false diagKiosk=false
- +10s canvas.draw mode="idle"
- +11s ws.send type="session_state" state="LOADING"
- +11s turn.state_changed state="LOADING"
- +11s ws.send type="session_state" state="PROCESSING"
- +11s turn.state_changed state="PROCESSING"
- +11s ws.send type="session_state" state="SPEAKING"
- +11s turn.state_changed state="SPEAKING"
- +11s ws.send type="session_state" state="IDLE"
- +11s turn.state_changed state="IDLE"
- +11s session.started sessionType="spelling" companionName="Elli"
- +224s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "613dda19-2129-47fc-9b59-455d453e6882",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 0
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 0,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
