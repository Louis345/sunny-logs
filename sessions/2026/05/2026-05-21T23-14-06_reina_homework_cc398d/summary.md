# Sunny Session Debug Summary

sessionId: cc398d03-b76d-436c-8a60-fb390e425c89
date: 2026-05-21T23:14:06.153Z
endedAt: 2026-05-21T23:16:41.966Z
child: Reina
subject: homework
mode: real
gitCommit: cc49f2b
command: npm run npx
duration_ms: 155813
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: real
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false chartChildId="reina"
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +0s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +1s transcript.replay turnState="IDLE" round=0 transcriptLength=949
- +1s transcript.accepted turnState="IDLE" round=0 transcriptLength=949
- +1s ws.send type="session_state" state="LOADING"
- +1s turn.state_changed state="LOADING"
- +1s ws.send type="session_state" state="PROCESSING"
- +1s turn.state_changed state="PROCESSING"
- +3s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +3s tool.client_result tool="companionAct"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +6s session.started sessionType="homework" companionName="Matilda"
- +9s ws.send type="session_state" state="IDLE"
- +9s turn.state_changed state="IDLE"
- +21s flow_game.game_state_update game="adventure-map" type="game_state_update"
- +22s flow_game.game_state_update game="adventure-map" type="game_state_update"
- +154s session.ending turnState="IDLE" roundNumber=1 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=2
- +154s engine.session_finalized totalAttempts=0 accuracy=0
- +154s engine.progression_computed level=92 totalXP=9110 wordsMastered=41

## Activity Evidence
- activityReadings: 0
- activityAttemptReadings: 0
- activityCorrectReadings: 0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 1,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "cc398d03-b76d-436c-8a60-fb390e425c89",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 2
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 2,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
