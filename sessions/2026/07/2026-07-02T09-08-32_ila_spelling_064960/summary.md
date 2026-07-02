# Sunny Session Debug Summary

sessionId: 06496090-7d31-4619-bc44-1ff0a591f611
date: 2026-07-02T09:08:32.551Z
endedAt: 2026-07-02T09:10:12.377Z
child: Ila
subject: spelling
mode: default
gitCommit: 6e85b75
command: /Users/jamaltaylor/.nvm/versions/node/v20.20.0/bin/node /Users/jamaltaylor/Development/sunny/src/server.ts
duration_ms: 99826
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
- +2s session.started sessionType="spelling" companionName="Elli"
- +10s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=18
- +19s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=11
- +19s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=12
- +32s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=13
- +38s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=17
- +98s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +98s engine.session_finalized totalAttempts=0 accuracy=0
- +98s engine.progression_computed level=86 totalXP=8595 wordsMastered=18

## Errors
- [2026-07-02T09:10:12.377Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "06496090-7d31-4619-bc44-1ff0a591f611",
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
