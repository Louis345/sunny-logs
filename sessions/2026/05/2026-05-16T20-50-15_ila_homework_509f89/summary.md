# Sunny Session Debug Summary

sessionId: 509f8961-344c-4137-ac04-f933d9e865fb
date: 2026-05-16T20:50:15.908Z
endedAt: 2026-05-16T21:05:17.054Z
child: Ila
subject: homework
mode: real
gitCommit: ec55b2b
command: npm run npx
duration_ms: 901146
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
- +796s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +799s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +800s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +801s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +802s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +803s transcript.suppressed reason="spell-check_active_game" turnState="IDLE" round=10 transcriptLength=4
- +806s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +806s transcript.suppressed reason="spell-check_active_game" turnState="IDLE" round=10 transcriptLength=6
- +811s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +816s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +819s transcript.suppressed reason="spell-check_active_game" turnState="IDLE" round=10 transcriptLength=3
- +820s transcript.suppressed reason="spell-check_active_game" turnState="IDLE" round=10 transcriptLength=4
- +821s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +825s transcript.suppressed reason="spell-check_active_game" turnState="IDLE" round=10 transcriptLength=4
- +826s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +829s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +829s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +831s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +831s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +833s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +836s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +839s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +841s transcript.suppressed reason="spell-check_active_game" turnState="IDLE" round=10 transcriptLength=5
- +841s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +841s transcript.duplicate_suppressed turnState="IDLE" round=10 transcriptLength=5
- +844s transcript.suppressed reason="spell-check_active_game" turnState="IDLE" round=10 transcriptLength=5
- +846s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +851s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +852s transcript.suppressed reason="spell-check_active_game" turnState="IDLE" round=10 transcriptLength=5
- +856s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +857s transcript.suppressed reason="spell-check_active_game" turnState="IDLE" round=10 transcriptLength=1
- +857s transcript.suppressed reason="spell-check_active_game" turnState="IDLE" round=10 transcriptLength=2
- +861s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +861s flow_game.game_complete game="unknown" type="game_complete"
- +866s game_narration.speak text="Ayla, mystery is ready." activityId="mystery" nodeId="n-mystery-hw-spelling_test-bb11de93" reason="game_mount_greeting"
- +866s transcript.accepted turnState="IDLE" round=10 transcriptLength=70
- +866s ws.send type="session_state" state="LOADING"
- +866s turn.state_changed state="LOADING"
- +866s ws.send type="session_state" state="PROCESSING"
- +866s turn.state_changed state="PROCESSING"
- +868s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +868s tool.client_result tool="companionAct"
- +873s tool.called tool="sessionLog" argsKeys=["correct","observation"] hasResult=false
- +873s tool.client_result tool="sessionLog"
- +876s tool.called tool="sessionLog" argsKeys=["correct","childSaid","observation"] hasResult=true
- +876s tool.client_result tool="sessionLog"
- +877s transcript.queued turnState="PROCESSING" round=11 transcriptLength=60
- +877s ws.send type="session_state" state="SPEAKING"
- +877s turn.state_changed state="SPEAKING"
- +877s ws.send type="session_state" state="IDLE"
- +877s turn.state_changed state="IDLE"
- +877s transcript.replay turnState="IDLE" round=11 transcriptLength=60
- +877s transcript.accepted turnState="IDLE" round=11 transcriptLength=60
- +877s ws.send type="session_state" state="LOADING"
- +877s turn.state_changed state="LOADING"
- +877s ws.send type="session_state" state="PROCESSING"
- +877s turn.state_changed state="PROCESSING"
- +881s tool.called tool="recordProductIssue" argsKeys=["issueType","severity","childUtterance","evidenceText","confidence","source"] hasResult=true
- +881s tool.client_result tool="recordProductIssue"
- +884s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +884s tool.client_result tool="takeGameScreenshot"
- +886s ws.send type="session_state" state="SPEAKING"
- +886s turn.state_changed state="SPEAKING"
- +887s transcript.dropped reason="assistant_owns_turn" turnState="SPEAKING" round=12 transcriptLength=23
- +888s ws.send type="session_state" state="IDLE"
- +888s turn.state_changed state="IDLE"
- +894s transcript.accepted turnState="IDLE" round=12 transcriptLength=10
- +894s ws.send type="session_state" state="LOADING"
- +894s turn.state_changed state="LOADING"
- +894s ws.send type="session_state" state="PROCESSING"
- +894s turn.state_changed state="PROCESSING"
- +898s tool.called tool="recordProductIssue" argsKeys=["issueType","severity","childUtterance","evidenceText","confidence","source"] hasResult=true
- +898s tool.client_result tool="recordProductIssue"
- +899s ws.send type="session_state" state="SPEAKING"
- +899s turn.state_changed state="SPEAKING"
- +900s session.ending turnState="SPEAKING" roundNumber=13 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=62
- +900s ws.send type="session_state" state="IDLE"
- +900s turn.state_changed state="IDLE"
- +900s engine.session_finalized totalAttempts=52 accuracy=0.5192307692307693
- +900s engine.progression_computed level=81 totalXP=8015 wordsMastered=15

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 13,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "509f8961-344c-4137-ac04-f933d9e865fb",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 62
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 62,
  "rewardLogEntries": 13
}
```

## Upload
Session saved locally. Upload not configured yet.
