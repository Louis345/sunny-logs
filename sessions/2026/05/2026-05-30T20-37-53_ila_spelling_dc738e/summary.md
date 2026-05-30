# Sunny Session Debug Summary

sessionId: dc738e1b-cc48-4055-b549-5a937d104e6f
date: 2026-05-30T20:37:53.940Z
endedAt: 2026-05-30T20:40:53.372Z
child: Ila
subject: spelling
mode: default
gitCommit: 3782d71
command: npm run npx
duration_ms: 179432
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
- +3s session.started sessionType="spelling" companionName="Elli"
- +7s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=9
- +20s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=19
- +34s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=39
- +68s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=48
- +77s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=46
- +85s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=4
- +93s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=4
- +105s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=60
- +119s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=34
- +120s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=13
- +120s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=14
- +136s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=61
- +148s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=3
- +156s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=5
- +173s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +174s engine.session_finalized totalAttempts=0 accuracy=0
- +174s engine.progression_computed level=103 totalXP=10285 wordsMastered=20

## Activity Evidence
- activityReadings: 0
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- [2026-05-30T20:40:53.366Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "dc738e1b-cc48-4055-b549-5a937d104e6f",
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
