# Sunny Session Debug Summary

sessionId: 5d624329-3191-4555-80e2-790344d2ed58
date: 2026-05-05T23:36:28.091Z
endedAt: 2026-05-05T23:42:32.418Z
child: Reina
subject: homework
mode: as-child
gitCommit: 46d65e5
command: npm run npx
duration_ms: 364327
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: as-child
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +301s transcript.accepted turnState="SPEAKING" round=23 transcriptLength=242
- +301s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=1 word="landforms" bonusMultiplier=1 wordIndex=0
- +301s flow_game.pronunciation_complete game="pronunciation" totalWords=1 correctCount=1 accuracyPct=100 wordsAttempted=1 wordsHit=1 xpEarned=10 bestStreak=1
- +302s ws.send type="session_state" state="IDLE"
- +302s turn.state_changed state="IDLE"
- +302s transcript.replay turnState="IDLE" round=24 transcriptLength=185
- +302s transcript.accepted turnState="IDLE" round=24 transcriptLength=185
- +302s ws.send type="session_state" state="LOADING"
- +302s turn.state_changed state="LOADING"
- +302s ws.send type="session_state" state="PROCESSING"
- +302s turn.state_changed state="PROCESSING"
- +303s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +303s tool.client_result tool="companionAct"
- +304s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +304s tool.client_result tool="companionAct"
- +304s ws.send type="session_state" state="SPEAKING"
- +304s turn.state_changed state="SPEAKING"
- +305s transcript.dropped reason="assistant_owns_turn" turnState="SPEAKING" round=25 transcriptLength=34
- +306s ws.send type="session_state" state="IDLE"
- +306s turn.state_changed state="IDLE"
- +308s transcript.accepted turnState="IDLE" round=25 transcriptLength=15
- +308s ws.send type="session_state" state="LOADING"
- +308s turn.state_changed state="LOADING"
- +308s ws.send type="session_state" state="PROCESSING"
- +308s turn.state_changed state="PROCESSING"
- +310s tool.called tool="sessionLog" argsKeys=["word","correct","observation"] hasResult=false
- +310s tool.client_result tool="sessionLog"
- +312s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word","observation"] hasResult=true
- +312s tool.client_result tool="sessionLog"
- +314s ws.send type="session_state" state="SPEAKING"
- +314s turn.state_changed state="SPEAKING"
- +315s ws.send type="session_state" state="IDLE"
- +315s turn.state_changed state="IDLE"
- +328s transcript.accepted turnState="IDLE" round=26 transcriptLength=13
- +328s ws.send type="session_state" state="LOADING"
- +328s turn.state_changed state="LOADING"
- +329s ws.send type="session_state" state="PROCESSING"
- +329s turn.state_changed state="PROCESSING"
- +331s tool.called tool="sessionLog" argsKeys=["word","correct","observation"] hasResult=false
- +331s tool.client_result tool="sessionLog"
- +333s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word","observation"] hasResult=true
- +333s tool.client_result tool="sessionLog"
- +335s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +335s tool.client_result tool="companionAct"
- +336s ws.send type="session_state" state="SPEAKING"
- +336s turn.state_changed state="SPEAKING"
- +338s ws.send type="session_state" state="IDLE"
- +338s turn.state_changed state="IDLE"
- +344s transcript.accepted turnState="IDLE" round=27 transcriptLength=71
- +344s ws.send type="session_state" state="LOADING"
- +344s turn.state_changed state="LOADING"
- +344s ws.send type="session_state" state="PROCESSING"
- +344s turn.state_changed state="PROCESSING"
- +345s transcript.queued turnState="PROCESSING" round=28 transcriptLength=77
- +346s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +346s tool.client_result tool="companionAct"
- +347s ws.send type="session_state" state="SPEAKING"
- +347s turn.state_changed state="SPEAKING"
- +349s ws.send type="session_state" state="IDLE"
- +349s turn.state_changed state="IDLE"
- +349s transcript.replay turnState="IDLE" round=28 transcriptLength=77
- +349s transcript.accepted turnState="IDLE" round=28 transcriptLength=77
- +349s ws.send type="session_state" state="LOADING"
- +349s turn.state_changed state="LOADING"
- +349s ws.send type="session_state" state="PROCESSING"
- +349s turn.state_changed state="PROCESSING"
- +350s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +350s tool.client_result tool="companionAct"
- +352s ws.send type="session_state" state="SPEAKING"
- +352s turn.state_changed state="SPEAKING"
- +354s ws.send type="session_state" state="IDLE"
- +354s turn.state_changed state="IDLE"
- +363s transcript.accepted turnState="IDLE" round=29 transcriptLength=288
- +363s ws.send type="session_state" state="LOADING"
- +363s turn.state_changed state="LOADING"
- +363s ws.send type="session_state" state="PROCESSING"
- +363s turn.state_changed state="PROCESSING"
- +364s session.ending turnState="PROCESSING" roundNumber=30 isEnding=true childName="Reina" canvasMode="pronunciation" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=146
- +364s ws.send type="session_state" state="IDLE"
- +364s turn.state_changed state="IDLE"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 30,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "5d624329-3191-4555-80e2-790344d2ed58",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 146
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 146,
  "rewardLogEntries": 3
}
```

## Upload
Session saved locally. Upload not configured yet.
