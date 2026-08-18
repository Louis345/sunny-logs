# Sunny Session Debug Summary

sessionId: 7d17dd9c-e33e-4bbb-b704-2d0d78851426
date: 2026-08-18T00:00:48.508Z
endedAt: 2026-08-18T00:01:51.598Z
child: Ila
subject: spelling
mode: default
gitCommit: ae27fb7
command: npm run npx
duration_ms: 63090
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
- +0s companion.greeting_generated source="live_homework_context" words=9
- +0s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="" voiceId="PeNaJO83cBW3Cf3YGzjZ" openingLine="Your Above challenge is ready. Want to try it?" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s ws.send type="session_state" state="LOADING"
- +1s turn.state_changed state="LOADING"
- +1s ws.send type="session_state" state="PROCESSING"
- +1s turn.state_changed state="PROCESSING"
- +1s ws.send type="session_state" state="SPEAKING"
- +1s turn.state_changed state="SPEAKING"
- +1s ws.send type="session_state" state="IDLE"
- +1s turn.state_changed state="IDLE"
- +1s session.started sessionType="spelling" companionName="Elli"
- +8s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=25
- +16s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=55
- +17s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=58
- +21s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +21s canvas.draw mode="idle"
- +33s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=16
- +44s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=27
- +54s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=24
- +62s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +62s engine.session_finalized totalAttempts=0 accuracy=0
- +62s engine.progression_computed level=88 totalXP=8725 wordsMastered=18

## Errors
- [2026-08-18T00:01:51.598Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "7d17dd9c-e33e-4bbb-b704-2d0d78851426",
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
