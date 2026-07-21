# Sunny Session Debug Summary

sessionId: b0fad5f4-650c-47e4-a2fd-488c7491fb1e
date: 2026-07-21T00:42:20.088Z
endedAt: 2026-07-21T00:45:38.399Z
child: Reina
subject: homework
mode: real
gitCommit: 8097a27
command: npm run npx
duration_ms: 198311
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: 
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +65s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-factretrieval-speed"
- +69s flow_game.attempt_event game="unknown" type="attempt_event"
- +70s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-factretrieval-speed"
- +72s transcript.accepted turnState="IDLE" round=0 transcriptLength=26
- +72s ws.send type="session_state" state="LOADING"
- +72s turn.state_changed state="LOADING"
- +72s ws.send type="session_state" state="PROCESSING"
- +72s turn.state_changed state="PROCESSING"
- +74s ws.send type="session_state" state="SPEAKING"
- +74s turn.state_changed state="SPEAKING"
- +78s ws.send type="session_state" state="IDLE"
- +78s turn.state_changed state="IDLE"
- +82s transcript.accepted turnState="IDLE" round=1 transcriptLength=15
- +82s ws.send type="session_state" state="LOADING"
- +82s turn.state_changed state="LOADING"
- +82s ws.send type="session_state" state="PROCESSING"
- +82s turn.state_changed state="PROCESSING"
- +85s ws.send type="session_state" state="SPEAKING"
- +85s turn.state_changed state="SPEAKING"
- +89s ws.send type="session_state" state="IDLE"
- +89s turn.state_changed state="IDLE"
- +99s transcript.accepted turnState="IDLE" round=2 transcriptLength=25
- +99s ws.send type="session_state" state="LOADING"
- +99s turn.state_changed state="LOADING"
- +99s ws.send type="session_state" state="PROCESSING"
- +99s turn.state_changed state="PROCESSING"
- +102s ws.send type="session_state" state="SPEAKING"
- +102s turn.state_changed state="SPEAKING"
- +107s ws.send type="session_state" state="IDLE"
- +107s turn.state_changed state="IDLE"
- +114s transcript.accepted turnState="IDLE" round=3 transcriptLength=45
- +114s ws.send type="session_state" state="LOADING"
- +114s turn.state_changed state="LOADING"
- +114s ws.send type="session_state" state="PROCESSING"
- +114s turn.state_changed state="PROCESSING"
- +116s ws.send type="session_state" state="SPEAKING"
- +116s turn.state_changed state="SPEAKING"
- +121s ws.send type="session_state" state="IDLE"
- +121s turn.state_changed state="IDLE"
- +126s transcript.accepted turnState="IDLE" round=4 transcriptLength=56
- +126s ws.send type="session_state" state="LOADING"
- +126s turn.state_changed state="LOADING"
- +126s ws.send type="session_state" state="PROCESSING"
- +126s turn.state_changed state="PROCESSING"
- +128s ws.send type="session_state" state="SPEAKING"
- +128s turn.state_changed state="SPEAKING"
- +133s ws.send type="session_state" state="IDLE"
- +133s turn.state_changed state="IDLE"
- +136s transcript.accepted turnState="IDLE" round=5 transcriptLength=27
- +136s ws.send type="session_state" state="LOADING"
- +136s turn.state_changed state="LOADING"
- +136s ws.send type="session_state" state="PROCESSING"
- +136s turn.state_changed state="PROCESSING"
- +137s ws.send type="session_state" state="SPEAKING"
- +137s turn.state_changed state="SPEAKING"
- +140s ws.send type="session_state" state="IDLE"
- +140s turn.state_changed state="IDLE"
- +141s flow_game.attempt_event game="unknown" type="attempt_event"
- +146s transcript.accepted turnState="IDLE" round=6 transcriptLength=19
- +146s ws.send type="session_state" state="LOADING"
- +146s turn.state_changed state="LOADING"
- +147s ws.send type="session_state" state="PROCESSING"
- +147s turn.state_changed state="PROCESSING"
- +148s ws.send type="session_state" state="SPEAKING"
- +148s turn.state_changed state="SPEAKING"
- +153s ws.send type="session_state" state="IDLE"
- +153s turn.state_changed state="IDLE"
- +169s flow_game.game_state_update game="generated-baseline" type="game_state_update" activityId="act-wordproblems-speed"
- +169s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-wordproblems-speed"
- +174s flow_game.game_state_update game="generated-baseline" type="game_state_update" activityId="act-skipcount-puzzle"
- +174s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-skipcount-puzzle"
- +176s flow_game.attempt_event game="unknown" type="attempt_event"
- +177s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-skipcount-puzzle"
- +180s flow_game.attempt_event game="unknown" type="attempt_event"
- +182s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-skipcount-puzzle"
- +183s flow_game.attempt_event game="unknown" type="attempt_event"
- +190s flow_game.game_state_update game="generated-baseline" type="game_state_update" activityId="act-factretrieval-puzzle"
- +190s flow_game.game_state_update game="generated-math" type="game_state_update" activityId="act-factretrieval-puzzle"
- +196s session.ending turnState="IDLE" roundNumber=7 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=14
- +196s engine.progression_computed level=78 totalXP=7755 wordsMastered=33

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 7,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "b0fad5f4-650c-47e4-a2fd-488c7491fb1e",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 14
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 14,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
