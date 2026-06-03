# Sunny Session Debug Summary

sessionId: df97096e-c7ae-4585-b63d-37f809e0a4cd
date: 2026-06-03T17:42:08.857Z
endedAt: 2026-06-03T17:45:13.917Z
child: Ila
subject: spelling
mode: default
gitCommit: c8230c1
command: /Users/jamaltaylor/.cache/codex-runtimes/codex-primary-runtime/dependencies/node/bin/node /Users/jamaltaylor/Development/sunny-main-onboarding-test/src/server.ts
duration_ms: 185060
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
- +6s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=31
- +34s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=24
- +40s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=14
- +49s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=23
- +92s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=42
- +147s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=35
- +161s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=4
- +169s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=4
- +184s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +184s engine.session_finalized totalAttempts=0 accuracy=0
- +184s engine.progression_computed level=86 totalXP=8595 wordsMastered=18

## Errors
- [2026-06-03T17:45:13.917Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "df97096e-c7ae-4585-b63d-37f809e0a4cd",
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
