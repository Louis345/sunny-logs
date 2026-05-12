# Sunny Session Debug Summary

sessionId: 68da5964-0d83-49fd-86c4-9f45b8cbc456
date: 2026-05-12T00:45:48.759Z
endedAt: 2026-05-12T00:47:45.287Z
child: Reina
subject: review
mode: real
gitCommit: 7bbbafb
command: npm run npx
duration_ms: 116528
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: 
- SUNNY_SUBJECT: review
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +36s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +36s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +40s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +41s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +45s canvas.draw mode="worksheet_pdf"
- +45s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Reina! Good to see you — what's new?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +45s canvas.draw mode="idle"
- +46s ws.send type="session_state" state="LOADING"
- +46s turn.state_changed state="LOADING"
- +46s ws.send type="session_state" state="PROCESSING"
- +46s turn.state_changed state="PROCESSING"
- +46s ws.send type="session_state" state="SPEAKING"
- +46s turn.state_changed state="SPEAKING"
- +46s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +47s ws.send type="session_state" state="IDLE"
- +47s turn.state_changed state="IDLE"
- +47s session.started sessionType="freeform" companionName="Matilda"
- +50s transcript.accepted turnState="IDLE" round=0 transcriptLength=17
- +50s ws.send type="session_state" state="LOADING"
- +50s turn.state_changed state="LOADING"
- +50s ws.send type="session_state" state="PROCESSING"
- +50s turn.state_changed state="PROCESSING"
- +51s flow_game.game_state_update game="Spell Check" type="game_state_update"
- +52s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +52s tool.client_result tool="companionAct"
- +55s ws.send type="session_state" state="SPEAKING"
- +55s turn.state_changed state="SPEAKING"
- +59s ws.send type="session_state" state="IDLE"
- +59s turn.state_changed state="IDLE"
- +62s transcript.accepted turnState="IDLE" round=1 transcriptLength=25
- +62s ws.send type="session_state" state="LOADING"
- +62s turn.state_changed state="LOADING"
- +62s ws.send type="session_state" state="PROCESSING"
- +62s turn.state_changed state="PROCESSING"
- +64s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +64s tool.client_result tool="companionAct"
- +66s ws.send type="session_state" state="SPEAKING"
- +66s turn.state_changed state="SPEAKING"
- +72s ws.send type="session_state" state="IDLE"
- +72s turn.state_changed state="IDLE"
- +76s session.ending turnState="IDLE" roundNumber=2 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=20
- +76s engine.session_finalized totalAttempts=0 accuracy=0
- +76s engine.progression_computed level=73 totalXP=7290 wordsMastered=29

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "68da5964-0d83-49fd-86c4-9f45b8cbc456",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 20
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 20,
  "rewardLogEntries": 1
}
```

## Upload
Session saved locally. Upload not configured yet.
