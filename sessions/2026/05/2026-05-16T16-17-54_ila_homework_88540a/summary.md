# Sunny Session Debug Summary

sessionId: 88540aad-4ff1-4e21-8f3b-76f862e84382
date: 2026-05-16T16:17:54.343Z
endedAt: 2026-05-16T16:26:50.919Z
child: Ila
subject: homework
mode: real
gitCommit: ec55b2b
command: npm run npx
duration_ms: 536576
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: ila
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +349s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=23
- +350s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=24
- +350s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=24
- +350s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=24
- +350s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=24 word="ahead" bonusMultiplier=1 wordIndex=23
- +350s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=24
- +350s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=24
- +351s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=24
- +351s flow_game.pronunciation_complete game="pronunciation" totalWords=5 correctCount=5 accuracyPct=100 wordsAttempted=5 wordsHit=5 xpEarned=480 bestStreak=24
- +354s transcript.accepted turnState="IDLE" round=4 transcriptLength=150
- +354s ws.send type="session_state" state="LOADING"
- +354s turn.state_changed state="LOADING"
- +354s ws.send type="session_state" state="IDLE"
- +354s turn.state_changed state="IDLE"
- +363s transcript.accepted turnState="IDLE" round=5 transcriptLength=24
- +363s ws.send type="session_state" state="LOADING"
- +363s turn.state_changed state="LOADING"
- +363s ws.send type="session_state" state="IDLE"
- +363s turn.state_changed state="IDLE"
- +364s transcript.accepted turnState="IDLE" round=6 transcriptLength=29
- +364s ws.send type="session_state" state="LOADING"
- +364s turn.state_changed state="LOADING"
- +364s ws.send type="session_state" state="IDLE"
- +364s turn.state_changed state="IDLE"
- +364s flow_game.voice_control game="pronunciation" type="voice_control"
- +373s transcript.accepted turnState="IDLE" round=7 transcriptLength=101
- +373s ws.send type="session_state" state="LOADING"
- +373s turn.state_changed state="LOADING"
- +373s ws.send type="session_state" state="PROCESSING"
- +373s turn.state_changed state="PROCESSING"
- +374s game_narration.speak text="Ayla, mystery is ready. First target: above." activityId="mystery" nodeId="n-mystery-hw-spelling_test-bb11de93" reason="game_mount_greeting"
- +376s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +376s tool.client_result tool="companionAct"
- +377s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +380s tool.called tool="sessionLog" argsKeys=["correct","observation"] hasResult=false
- +380s tool.client_result tool="sessionLog"
- +380s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +382s tool.called tool="sessionLog" argsKeys=["correct","childSaid","observation"] hasResult=true
- +382s tool.client_result tool="sessionLog"
- +383s ws.send type="session_state" state="SPEAKING"
- +383s turn.state_changed state="SPEAKING"
- +383s ws.send type="session_state" state="IDLE"
- +383s turn.state_changed state="IDLE"
- +383s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=8 transcriptLength=134
- +385s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +387s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=8 transcriptLength=2
- +389s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +393s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +394s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +396s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +399s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +399s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +401s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +404s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +409s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +412s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +413s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=8 transcriptLength=18
- +414s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +417s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +418s flow_game.game_state_update game="Wheel of Fortune" type="game_state_update"
- +418s flow_game.game_state_update game="Project Sunny — Wheel of Fortune" type="game_state_update"
- +420s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=8 transcriptLength=25
- +422s flow_game.game_complete game="unknown" type="game_complete"
- +431s flow_game.game_state_update game="adventure-map" type="game_state_update"
- +432s flow_game.game_state_update game="adventure-map" type="game_state_update"
- +459s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=8 transcriptLength=389
- +466s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=8 transcriptLength=143
- +479s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=8 transcriptLength=144
- +483s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=8 transcriptLength=191
- +489s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=8 transcriptLength=245
- +520s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=8 transcriptLength=604
- +522s transcript.suppressed reason="karaoke_reading" turnState="IDLE" round=8 transcriptLength=630
- +528s transcript.accepted turnState="IDLE" round=8 transcriptLength=679
- +528s ws.send type="session_state" state="LOADING"
- +528s turn.state_changed state="LOADING"
- +528s session.ending turnState="LOADING" roundNumber=8 isEnding=true childName="Ila" canvasMode="spell-check" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=true activeSpellCheckWord="alone" tts="on" conversationTurns=218
- +528s ws.send type="session_state" state="IDLE"
- +528s turn.state_changed state="IDLE"
- +528s engine.session_finalized totalAttempts=0 accuracy=0
- +528s engine.progression_computed level=76 totalXP=7565 wordsMastered=14

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 8,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "88540aad-4ff1-4e21-8f3b-76f862e84382",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 218
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 218,
  "rewardLogEntries": 18
}
```

## Upload
Session saved locally. Upload not configured yet.
