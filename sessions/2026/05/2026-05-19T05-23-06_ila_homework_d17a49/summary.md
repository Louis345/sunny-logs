# Sunny Session Debug Summary

sessionId: d17a49bd-273b-45f7-9261-76e2964b868f
date: 2026-05-19T05:23:06.608Z
endedAt: 2026-05-19T05:30:57.221Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 470613
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
- +40s turn.state_changed state="PROCESSING"
- +40s transcript.queued turnState="PROCESSING" round=3 transcriptLength=5
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +40s flow_game.game_state_update game="word-radar" type="game_state_update"
- +41s flow_game.game_state_update game="word-radar" type="game_state_update"
- +43s flow_game.game_complete game="word-radar" type="game_complete"
- +43s flow_game.voice_control game="word-radar" type="voice_control"
- +43s game_narration.speak text="Demo_Adaptive, spell check is ready. First target: again." activityId="spell-check" nodeId="n-spell-check-hw-adapt-weak_performance" reason="game_mount_greeting"
- +43s transcript.replay turnState="PROCESSING" round=3 transcriptLength=5
- +43s transcript.queued turnState="PROCESSING" round=3 transcriptLength=5
- +46s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +46s tool.client_result tool="companionAct"
- +49s ws.send type="session_state" state="SPEAKING"
- +49s turn.state_changed state="SPEAKING"
- +50s ws.send type="session_state" state="IDLE"
- +50s turn.state_changed state="IDLE"
- +50s transcript.replay turnState="IDLE" round=3 transcriptLength=5
- +50s transcript.accepted turnState="IDLE" round=3 transcriptLength=5
- +50s ws.send type="session_state" state="LOADING"
- +50s turn.state_changed state="LOADING"
- +50s ws.send type="session_state" state="PROCESSING"
- +50s turn.state_changed state="PROCESSING"
- +50s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +51s transcript.queued turnState="PROCESSING" round=4 transcriptLength=16
- +52s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +52s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +53s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +53s tool.client_result tool="sessionLog"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +54s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +55s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +55s tool.client_result tool="companionAct"
- +56s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +57s ws.send type="session_state" state="SPEAKING"
- +57s turn.state_changed state="SPEAKING"
- +57s ws.send type="session_state" state="IDLE"
- +57s turn.state_changed state="IDLE"
- +57s transcript.replay turnState="IDLE" round=4 transcriptLength=16
- +57s transcript.accepted turnState="IDLE" round=4 transcriptLength=16
- +57s ws.send type="session_state" state="LOADING"
- +57s turn.state_changed state="LOADING"
- +57s ws.send type="session_state" state="PROCESSING"
- +57s turn.state_changed state="PROCESSING"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +57s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +59s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +60s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word"] hasResult=true
- +60s tool.client_result tool="sessionLog"
- +61s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +61s ws.send type="session_state" state="SPEAKING"
- +61s turn.state_changed state="SPEAKING"
- +61s ws.send type="session_state" state="IDLE"
- +61s turn.state_changed state="IDLE"
- +61s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +61s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +63s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +63s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +63s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +66s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +66s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +67s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +67s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +71s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +71s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +71s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +73s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +74s flow_game.game_complete game="unknown" type="game_complete"
- +82s flow_game.voice_control game="word-radar" type="voice_control"
- +87s flow_game.game_state_update game="word-radar" type="game_state_update"
- +89s flow_game.narration_request game="word-radar" type="narration_request" word="again" reason="word_radar_response_prompt"
- +89s game_narration.speak text="again." activityId="word-radar" reason="word_radar_response_prompt"
- +466s session.ending turnState="IDLE" roundNumber=5 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="off" conversationTurns=44
- +466s engine.session_finalized totalAttempts=22 accuracy=1
- +466s engine.progression_computed level=4 totalXP=350 wordsMastered=5

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 5,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "d17a49bd-273b-45f7-9261-76e2964b868f",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "off",
  "conversationTurns": 44
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 44,
  "rewardLogEntries": 16
}
```

## Upload
Session saved locally. Upload not configured yet.
