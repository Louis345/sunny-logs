# Sunny Session Debug Summary

sessionId: 4c1636a0-ca92-4337-94a7-0187a0526e96
date: 2026-06-05T00:37:39.078Z
endedAt: 2026-06-05T00:39:09.760Z
child: Ila
subject: spelling
mode: default
gitCommit: d1008a6
command: npm run npx
duration_ms: 90682
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
- +4s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=16
- +14s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=34
- +22s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=17
- +32s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=31
- +42s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=41
- +55s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=24
- +90s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +90s engine.session_finalized totalAttempts=0 accuracy=0
- +90s engine.progression_computed level=87 totalXP=8645 wordsMastered=18

## Errors
- [2026-06-05T00:39:09.760Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "4c1636a0-ca92-4337-94a7-0187a0526e96",
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
