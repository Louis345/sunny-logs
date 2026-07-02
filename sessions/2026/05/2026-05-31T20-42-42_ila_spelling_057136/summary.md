# Sunny Session Debug Summary

sessionId: 05713642-18f9-435d-a97a-ebb768ff406c
date: 2026-05-31T20:42:42.688Z
endedAt: 2026-05-31T20:47:03.137Z
child: Ila
subject: spelling
mode: default
gitCommit: 55fbee7
command: /Users/jamaltaylor/.cache/codex-runtimes/codex-primary-runtime/dependencies/node/bin/node /Users/jamaltaylor/Development/sunny/src/server.ts
duration_ms: 260449
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
- +7s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=31
- +15s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +15s canvas.draw mode="idle"
- +15s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=14
- +17s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=30
- +30s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=23
- +61s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=42
- +81s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=30
- +85s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=20
- +246s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=13
- +259s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +259s engine.session_finalized totalAttempts=0 accuracy=0
- +259s engine.progression_computed level=104 totalXP=10380 wordsMastered=20

## Activity Evidence
- activityReadings: 0
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- [2026-05-31T20:47:03.135Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "05713642-18f9-435d-a97a-ebb768ff406c",
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
