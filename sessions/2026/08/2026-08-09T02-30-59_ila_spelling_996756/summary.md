# Sunny Session Debug Summary

sessionId: 996756e0-7d4c-405b-abde-2d16854ec39f
date: 2026-08-09T02:30:59.291Z
endedAt: 2026-08-09T02:33:23.936Z
child: Ila
subject: spelling
mode: default
gitCommit: d07419f
command: npm run npx
duration_ms: 144645
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
- +80s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=45
- +144s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +144s engine.session_finalized totalAttempts=0 accuracy=0
- +144s engine.progression_computed level=87 totalXP=8660 wordsMastered=18

## Errors
- [2026-08-09T02:33:23.936Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "996756e0-7d4c-405b-abde-2d16854ec39f",
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
