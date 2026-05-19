# Sunny Session Debug Summary

sessionId: 33cc698f-a252-4e93-8073-bae4bb7bed04
date: 2026-05-19T04:25:02.227Z
endedAt: 2026-05-19T04:26:52.597Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 110370
result: completed

## Env Flags
- TTS_ENABLED: false
- SUNNY_MODE: real
- SUNNY_CHILD: demo_adaptive
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +83s transcript.replay turnState="IDLE" round=10 transcriptLength=16
- +83s transcript.accepted turnState="IDLE" round=10 transcriptLength=16
- +83s ws.send type="session_state" state="LOADING"
- +83s turn.state_changed state="LOADING"
- +83s ws.send type="session_state" state="PROCESSING"
- +83s turn.state_changed state="PROCESSING"
- +84s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +85s transcript.queued turnState="PROCESSING" round=11 transcriptLength=16
- +85s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +85s tool.client_result tool="sessionLog"
- +86s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +86s transcript.duplicate_suppressed turnState="PROCESSING" round=11 transcriptLength=16
- +87s ws.send type="session_state" state="SPEAKING"
- +87s turn.state_changed state="SPEAKING"
- +87s ws.send type="session_state" state="IDLE"
- +87s turn.state_changed state="IDLE"
- +87s transcript.replay turnState="IDLE" round=11 transcriptLength=16
- +87s transcript.accepted turnState="IDLE" round=11 transcriptLength=16
- +87s ws.send type="session_state" state="LOADING"
- +87s turn.state_changed state="LOADING"
- +87s ws.send type="session_state" state="PROCESSING"
- +87s turn.state_changed state="PROCESSING"
- +88s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +89s transcript.queued turnState="PROCESSING" round=12 transcriptLength=16
- +90s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +90s tool.client_result tool="sessionLog"
- +91s transcript.duplicate_suppressed turnState="PROCESSING" round=12 transcriptLength=16
- +91s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +92s ws.send type="session_state" state="SPEAKING"
- +92s turn.state_changed state="SPEAKING"
- +92s ws.send type="session_state" state="IDLE"
- +92s turn.state_changed state="IDLE"
- +92s transcript.replay turnState="IDLE" round=12 transcriptLength=16
- +92s transcript.accepted turnState="IDLE" round=12 transcriptLength=16
- +92s ws.send type="session_state" state="LOADING"
- +92s turn.state_changed state="LOADING"
- +92s ws.send type="session_state" state="PROCESSING"
- +92s turn.state_changed state="PROCESSING"
- +94s transcript.queued turnState="PROCESSING" round=13 transcriptLength=16
- +95s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +96s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +96s transcript.duplicate_suppressed turnState="PROCESSING" round=13 transcriptLength=16
- +97s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +97s tool.client_result tool="sessionLog"
- +98s transcript.queued turnState="PROCESSING" round=13 transcriptLength=16
- +98s ws.send type="session_state" state="SPEAKING"
- +98s turn.state_changed state="SPEAKING"
- +98s ws.send type="session_state" state="IDLE"
- +98s turn.state_changed state="IDLE"
- +98s transcript.replay turnState="IDLE" round=13 transcriptLength=16
- +98s transcript.accepted turnState="IDLE" round=13 transcriptLength=16
- +98s ws.send type="session_state" state="LOADING"
- +98s turn.state_changed state="LOADING"
- +98s ws.send type="session_state" state="PROCESSING"
- +98s turn.state_changed state="PROCESSING"
- +99s transcript.duplicate_suppressed turnState="PROCESSING" round=14 transcriptLength=16
- +100s transcript.duplicate_suppressed turnState="PROCESSING" round=14 transcriptLength=16
- +101s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +102s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +102s tool.client_result tool="sessionLog"
- +102s transcript.queued turnState="PROCESSING" round=14 transcriptLength=16
- +103s transcript.duplicate_suppressed turnState="PROCESSING" round=14 transcriptLength=16
- +103s ws.send type="session_state" state="SPEAKING"
- +103s turn.state_changed state="SPEAKING"
- +103s ws.send type="session_state" state="IDLE"
- +103s turn.state_changed state="IDLE"
- +103s transcript.replay turnState="IDLE" round=14 transcriptLength=16
- +103s transcript.accepted turnState="IDLE" round=14 transcriptLength=16
- +103s ws.send type="session_state" state="LOADING"
- +103s turn.state_changed state="LOADING"
- +103s ws.send type="session_state" state="PROCESSING"
- +103s turn.state_changed state="PROCESSING"
- +104s transcript.duplicate_suppressed turnState="PROCESSING" round=15 transcriptLength=16
- +105s session.ending turnState="PROCESSING" roundNumber=15 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=46
- +105s ws.send type="session_state" state="IDLE"
- +105s turn.state_changed state="IDLE"
- +105s engine.session_finalized totalAttempts=21 accuracy=1
- +105s engine.progression_computed level=7 totalXP=645 wordsMastered=6
- +108s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +108s tool.client_result tool="companionAct"

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 15,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "33cc698f-a252-4e93-8073-bae4bb7bed04",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 48
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 48,
  "rewardLogEntries": 9
}
```

## Upload
Session saved locally. Upload not configured yet.
