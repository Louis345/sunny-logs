# Sunny Session Debug Summary

sessionId: 3dfc0336-ebf2-4050-8a56-133515b1bd0e
date: 2026-08-12T21:46:45.292Z
endedAt: 2026-08-12T21:49:40.202Z
child: Ila
subject: spelling
mode: default
gitCommit: 62cd90c
command: npm run npx
duration_ms: 174910
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
- +0s ws.send type="session_state" state="LOADING"
- +0s turn.state_changed state="LOADING"
- +0s ws.send type="session_state" state="PROCESSING"
- +0s turn.state_changed state="PROCESSING"
- +0s ws.send type="session_state" state="SPEAKING"
- +0s turn.state_changed state="SPEAKING"
- +0s ws.send type="session_state" state="IDLE"
- +0s turn.state_changed state="IDLE"
- +0s session.started sessionType="spelling" companionName="Elli"
- +5s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +5s canvas.draw mode="idle"
- +5s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=7
- +9s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=61
- +11s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +11s canvas.draw mode="idle"
- +17s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=88
- +18s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=100
- +33s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=66
- +34s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=62
- +40s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +40s canvas.draw mode="idle"
- +41s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=41
- +42s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=24
- +54s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=100
- +54s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=101
- +64s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=167
- +80s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=9
- +91s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=55
- +95s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=28
- +97s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +97s canvas.draw mode="idle"
- +103s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=43
- +108s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +108s canvas.draw mode="idle"
- +108s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=57
- +131s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=337
- +136s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +136s canvas.draw mode="idle"
- +140s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=58
- +145s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +145s canvas.draw mode="idle"
- +149s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=189
- +159s turn.barge_in stateBefore="IDLE" turnState="IDLE" round=0 tts="on"
- +159s canvas.draw mode="idle"
- +162s transcript.accepted turnState="IDLE" round=0 source="stt_only" transcriptLength=71
- +174s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +174s engine.session_finalized totalAttempts=0 accuracy=0
- +174s engine.progression_computed level=87 totalXP=8695 wordsMastered=18

## Errors
- [2026-08-12T21:49:40.176Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "3dfc0336-ebf2-4050-8a56-133515b1bd0e",
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
