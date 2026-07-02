# Sunny Session Debug Summary

sessionId: 1a32b233-e7ae-4e35-ac17-8809b404b550
date: 2026-05-31T21:04:45.539Z
endedAt: 2026-05-31T21:12:23.624Z
child: Ila
subject: spelling
mode: default
gitCommit: 55fbee7
command: /Users/jamaltaylor/.cache/codex-runtimes/codex-primary-runtime/dependencies/node/bin/node /Users/jamaltaylor/Development/sunny/src/server.ts
duration_ms: 458085
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
- +2s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +2s canvas.draw mode="idle"
- +2s session.started sessionType="spelling" companionName="Elli"
- +9s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=32
- +444s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=6
- +456s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +456s engine.session_finalized totalAttempts=0 accuracy=0
- +456s engine.progression_computed level=104 totalXP=10385 wordsMastered=20

## Activity Evidence
- activityReadings: 0
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- [2026-05-31T21:12:23.620Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "1a32b233-e7ae-4e35-ac17-8809b404b550",
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
