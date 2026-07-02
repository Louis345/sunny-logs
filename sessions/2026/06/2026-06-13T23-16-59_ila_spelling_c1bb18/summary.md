# Sunny Session Debug Summary

sessionId: c1bb1864-1c66-4259-8c7a-b63eeedb3712
date: 2026-06-13T23:16:59.477Z
endedAt: 2026-06-13T23:18:47.951Z
child: Ila
subject: spelling
mode: default
gitCommit: 8c7e236
command: /Users/jamaltaylor/.nvm/versions/node/v20.20.0/bin/node /Users/jamaltaylor/Development/sunny/src/server.ts
duration_ms: 108474
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
- +0s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s session.started sessionType="spelling" companionName="Elli"
- +11s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=24
- +33s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=25
- +63s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=24
- +80s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=33
- +108s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +108s engine.session_finalized totalAttempts=0 accuracy=0
- +108s engine.progression_computed level=86 totalXP=8590 wordsMastered=18

## Errors
- [2026-06-13T23:18:47.950Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "c1bb1864-1c66-4259-8c7a-b63eeedb3712",
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
  "postSessionError": "messages: text content blocks must be non-empty",
  "shouldPersistSessionData": true,
  "conversationTurns": 0,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
