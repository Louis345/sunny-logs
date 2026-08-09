# Sunny Session Debug Summary

sessionId: 636f1af7-d2a5-45dc-b9bd-bfb39239d281
date: 2026-08-09T02:34:29.897Z
endedAt: 2026-08-09T02:35:26.421Z
child: Ila
subject: spelling
mode: default
gitCommit: d07419f
command: npm run npx
duration_ms: 56524
result: errored

## Env Flags
- TTS_ENABLED: 
- SUNNY_MODE: 
- SUNNY_CHILD: 
- SUNNY_SUBJECT: 
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: 
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=true sttOnly=true chartChildId="ila"
- +0s session.start_requested childName="Ila" companionName="Elli"
- +0s companion.greeting_generated source="live_homework_context" words=9
- +0s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Your Above challenge is ready. Want to try it?" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +0s ws.send type="session_state" state="LOADING"
- +0s turn.state_changed state="LOADING"
- +0s ws.send type="session_state" state="PROCESSING"
- +0s turn.state_changed state="PROCESSING"
- +0s ws.send type="session_state" state="SPEAKING"
- +0s turn.state_changed state="SPEAKING"
- +0s ws.send type="session_state" state="IDLE"
- +0s turn.state_changed state="IDLE"
- +0s session.started sessionType="spelling" companionName="Elli"
- +42s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=5
- +56s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +56s engine.session_finalized totalAttempts=0 accuracy=0
- +56s engine.progression_computed level=87 totalXP=8665 wordsMastered=18

## Errors
- [2026-08-09T02:35:26.421Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "636f1af7-d2a5-45dc-b9bd-bfb39239d281",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 0
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "postSessionError": "Your credit balance is too low to access the Anthropic API. Please go to Plans & Billing to upgrade or purchase credits.",
  "shouldPersistSessionData": true,
  "conversationTurns": 0,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
