# Sunny Session Debug Summary

sessionId: 6fd1245d-2740-493d-ac8d-bb11e3bdab89
date: 2026-06-10T03:55:55.232Z
endedAt: 2026-06-10T04:01:43.401Z
child: Ila
subject: spelling
mode: default
gitCommit: 3f9fa18
command: /Users/jamaltaylor/.nvm/versions/node/v20.20.0/bin/node /Users/jamaltaylor/Development/sunny/src/server.ts
duration_ms: 348169
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
- +0s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +6s session.started sessionType="spelling" companionName="Elli"
- +11s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=16
- +23s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=21
- +23s transcript.duplicate_suppressed turnState="IDLE" round=0 transcriptLength=21
- +53s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=27
- +65s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=17
- +146s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=29
- +162s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=26
- +187s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=4
- +205s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=37
- +347s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +347s engine.session_finalized totalAttempts=0 accuracy=0
- +348s engine.progression_computed level=105 totalXP=10470 wordsMastered=20

## Activity Evidence
- activityReadings: 0
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- [2026-06-10T04:01:43.385Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "6fd1245d-2740-493d-ac8d-bb11e3bdab89",
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
