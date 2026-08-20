# Sunny Session Debug Summary

sessionId: 8c295786-43e5-4aff-93ea-39aa2a416219
date: 2026-08-20T23:01:25.184Z
endedAt: 2026-08-20T23:04:13.423Z
child: Ila
subject: spelling
mode: default
gitCommit: a96f9d6
command: npm run npx
duration_ms: 168239
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
- +1s companion.greeting_generated source="live_homework_context" words=9
- +1s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Your Above challenge is ready. Want to try it?" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +1s canvas.draw mode="idle"
- +1s ws.send type="session_state" state="LOADING"
- +1s turn.state_changed state="LOADING"
- +1s ws.send type="session_state" state="PROCESSING"
- +1s turn.state_changed state="PROCESSING"
- +1s ws.send type="session_state" state="SPEAKING"
- +1s turn.state_changed state="SPEAKING"
- +1s ws.send type="session_state" state="IDLE"
- +1s turn.state_changed state="IDLE"
- +1s session.started sessionType="spelling" companionName="Elli"
- +7s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=16
- +18s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=38
- +28s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=24
- +36s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=5
- +53s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=75
- +147s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=52
- +152s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=21
- +153s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=39
- +157s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +157s canvas.draw mode="idle"
- +158s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=20
- +167s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +167s engine.session_finalized totalAttempts=0 accuracy=0
- +167s engine.progression_computed level=88 totalXP=8740 wordsMastered=18

## Errors
- [2026-08-20T23:04:13.423Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "8c295786-43e5-4aff-93ea-39aa2a416219",
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
