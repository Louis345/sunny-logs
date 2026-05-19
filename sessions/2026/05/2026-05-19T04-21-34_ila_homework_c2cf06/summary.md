# Sunny Session Debug Summary

sessionId: c2cf06f8-021f-44d2-8238-e64d220a3a57
date: 2026-05-19T04:21:34.335Z
endedAt: 2026-05-19T04:23:21.146Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 106811
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
- +68s turn.state_changed state="LOADING"
- +68s ws.send type="session_state" state="PROCESSING"
- +68s turn.state_changed state="PROCESSING"
- +69s transcript.duplicate_suppressed turnState="PROCESSING" round=6 transcriptLength=16
- +70s transcript.duplicate_suppressed turnState="PROCESSING" round=6 transcriptLength=16
- +70s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +71s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +71s tool.client_result tool="companionAct"
- +71s transcript.queued turnState="PROCESSING" round=6 transcriptLength=16
- +73s transcript.duplicate_suppressed turnState="PROCESSING" round=6 transcriptLength=16
- +74s transcript.duplicate_suppressed turnState="PROCESSING" round=6 transcriptLength=16
- +74s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +74s tool.client_result tool="companionAct"
- +75s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +76s ws.send type="session_state" state="SPEAKING"
- +76s turn.state_changed state="SPEAKING"
- +76s ws.send type="session_state" state="IDLE"
- +76s turn.state_changed state="IDLE"
- +76s transcript.replay turnState="IDLE" round=6 transcriptLength=16
- +76s transcript.accepted turnState="IDLE" round=6 transcriptLength=16
- +76s ws.send type="session_state" state="LOADING"
- +76s turn.state_changed state="LOADING"
- +76s ws.send type="session_state" state="PROCESSING"
- +76s turn.state_changed state="PROCESSING"
- +76s transcript.queued turnState="PROCESSING" round=7 transcriptLength=16
- +77s transcript.duplicate_suppressed turnState="PROCESSING" round=7 transcriptLength=16
- +79s transcript.duplicate_suppressed turnState="PROCESSING" round=7 transcriptLength=16
- +80s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +80s tool.client_result tool="companionAct"
- +80s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +80s transcript.queued turnState="PROCESSING" round=7 transcriptLength=16
- +81s ws.send type="session_state" state="SPEAKING"
- +81s turn.state_changed state="SPEAKING"
- +81s ws.send type="session_state" state="IDLE"
- +81s turn.state_changed state="IDLE"
- +81s transcript.replay turnState="IDLE" round=7 transcriptLength=16
- +81s transcript.accepted turnState="IDLE" round=7 transcriptLength=16
- +81s ws.send type="session_state" state="LOADING"
- +81s turn.state_changed state="LOADING"
- +81s ws.send type="session_state" state="PROCESSING"
- +81s turn.state_changed state="PROCESSING"
- +81s transcript.duplicate_suppressed turnState="PROCESSING" round=8 transcriptLength=16
- +83s transcript.duplicate_suppressed turnState="PROCESSING" round=8 transcriptLength=16
- +84s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +84s tool.client_result tool="companionAct"
- +84s transcript.queued turnState="PROCESSING" round=8 transcriptLength=16
- +85s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +86s transcript.duplicate_suppressed turnState="PROCESSING" round=8 transcriptLength=16
- +86s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +86s tool.client_result tool="takeGameScreenshot"
- +87s transcript.duplicate_suppressed turnState="PROCESSING" round=8 transcriptLength=16
- +88s transcript.queued turnState="PROCESSING" round=8 transcriptLength=16
- +90s transcript.duplicate_suppressed turnState="PROCESSING" round=8 transcriptLength=16
- +90s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +91s transcript.duplicate_suppressed turnState="PROCESSING" round=8 transcriptLength=16
- +91s ws.send type="session_state" state="SPEAKING"
- +91s turn.state_changed state="SPEAKING"
- +91s ws.send type="session_state" state="IDLE"
- +91s turn.state_changed state="IDLE"
- +91s transcript.replay turnState="IDLE" round=8 transcriptLength=16
- +91s transcript.accepted turnState="IDLE" round=8 transcriptLength=16
- +91s ws.send type="session_state" state="LOADING"
- +91s turn.state_changed state="LOADING"
- +91s ws.send type="session_state" state="PROCESSING"
- +91s turn.state_changed state="PROCESSING"
- +92s transcript.queued turnState="PROCESSING" round=9 transcriptLength=16
- +94s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +95s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +95s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +96s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +96s tool.client_result tool="companionAct"
- +97s transcript.queued turnState="PROCESSING" round=9 transcriptLength=16
- +98s transcript.duplicate_suppressed turnState="PROCESSING" round=9 transcriptLength=16
- +98s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +98s tool.client_result tool="companionAct"
- +98s session.ending turnState="PROCESSING" roundNumber=9 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=true pendingTranscriptLength=16 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=32
- +98s ws.send type="session_state" state="IDLE"
- +98s turn.state_changed state="IDLE"
- +98s engine.session_finalized totalAttempts=11 accuracy=1
- +98s engine.progression_computed level=2 totalXP=115 wordsMastered=0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 9,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "c2cf06f8-021f-44d2-8238-e64d220a3a57",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 34
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 34,
  "rewardLogEntries": 1
}
```

## Upload
Session saved locally. Upload not configured yet.
