# Sunny Session Debug Summary

sessionId: ec35e8cf-f9e7-4d70-89d4-10a91a662bcc
date: 2026-05-30T00:35:35.483Z
endedAt: 2026-05-30T00:37:29.054Z
child: Ila
subject: spelling
mode: default
gitCommit: bc001a5
command: npm run npx
duration_ms: 113571
result: errored

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: 
- SUNNY_CHILD: 
- SUNNY_SUBJECT: 
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: 
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=true sttOnly=true chartChildId="ila"
- +0s session.start_requested childName="Ila" companionName="Elli"
- +1s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +2s canvas.draw mode="idle"
- +3s session.started sessionType="spelling" companionName="Elli"
- +6s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=28
- +22s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=72
- +41s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=21
- +50s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=23
- +66s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=24
- +74s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=3
- +90s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=38
- +93s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=72
- +112s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +113s engine.session_finalized totalAttempts=0 accuracy=0
- +113s engine.progression_computed level=103 totalXP=10260 wordsMastered=20

## Activity Evidence
- activityReadings: 0
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- [2026-05-30T00:37:29.053Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "ec35e8cf-f9e7-4d70-89d4-10a91a662bcc",
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
