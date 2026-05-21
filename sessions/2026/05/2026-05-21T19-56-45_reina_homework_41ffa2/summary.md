# Sunny Session Debug Summary

sessionId: 41ffa2f8-72ce-4e9a-bd1c-ebd5efc86c0d
date: 2026-05-21T19:56:45.417Z
endedAt: 2026-05-21T19:57:34.774Z
child: Reina
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 49357
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
- +1s transcript.replay turnState="IDLE" round=0 transcriptLength=946
- +1s transcript.accepted turnState="IDLE" round=0 transcriptLength=946
- +1s ws.send type="session_state" state="LOADING"
- +1s turn.state_changed state="LOADING"
- +1s ws.send type="session_state" state="PROCESSING"
- +1s turn.state_changed state="PROCESSING"
- +4s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +4s tool.client_result tool="companionAct"
- +5s ws.send type="session_state" state="SPEAKING"
- +5s turn.state_changed state="SPEAKING"
- +6s session.started sessionType="homework" companionName="Matilda"
- +9s ws.send type="session_state" state="IDLE"
- +9s turn.state_changed state="IDLE"
- +14s game_narration.speak text="Ray-nah, spell check is ready. First target: sign." activityId="spell-check" nodeId="node-1-silent-baseline" reason="game_mount_greeting"
- +15s game_narration.playback_done text="Ray-nah, spell check is ready. First target: sign." activityId="spell-check" nodeId="node-1-silent-baseline" reason="game_mount_greeting"
- +30s transcript.accepted turnState="IDLE" round=1 transcriptLength=5
- +30s ws.send type="session_state" state="LOADING"
- +30s turn.state_changed state="LOADING"
- +30s ws.send type="session_state" state="PROCESSING"
- +30s turn.state_changed state="PROCESSING"
- +33s tool.called tool="sessionLog" argsKeys=["correct","word","observation"] hasResult=false
- +33s tool.client_result tool="sessionLog"
- +35s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word","observation"] hasResult=true
- +35s tool.client_result tool="sessionLog"
- +37s ws.send type="session_state" state="SPEAKING"
- +37s turn.state_changed state="SPEAKING"
- +40s ws.send type="session_state" state="IDLE"
- +40s turn.state_changed state="IDLE"
- +46s session.ending turnState="IDLE" roundNumber=2 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=6
- +46s engine.session_finalized totalAttempts=2 accuracy=1
- +46s engine.progression_computed level=88 totalXP=8770 wordsMastered=40

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 2,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "41ffa2f8-72ce-4e9a-bd1c-ebd5efc86c0d",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 6
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 6,
  "rewardLogEntries": 2
}
```

## Upload
Session saved locally. Upload not configured yet.
