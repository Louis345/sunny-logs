# Sunny Session Debug Summary

sessionId: 5744e696-84d6-4dad-bd4a-8b822ceba3c3
date: 2026-05-31T00:15:16.740Z
endedAt: 2026-05-31T00:16:50.501Z
child: Ila
subject: spelling
mode: default
gitCommit: b79dd19
command: /Users/jamaltaylor/.cache/codex-runtimes/codex-primary-runtime/dependencies/node/bin/node /Users/jamaltaylor/Development/sunny/src/server.ts
duration_ms: 93761
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
- +14s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=22
- +20s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +20s canvas.draw mode="idle"
- +21s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=9
- +22s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=9
- +27s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=24
- +41s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=24
- +65s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +65s canvas.draw mode="idle"
- +66s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=71
- +67s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=74
- +78s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=44
- +93s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +93s engine.session_finalized totalAttempts=0 accuracy=0
- +93s engine.progression_computed level=104 totalXP=10300 wordsMastered=20

## Activity Evidence
- activityReadings: 0
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- [2026-05-31T00:16:50.493Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "5744e696-84d6-4dad-bd4a-8b822ceba3c3",
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
