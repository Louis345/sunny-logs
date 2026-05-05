# Sunny Session Debug Summary

sessionId: 8bdd7bed-a8a1-40e9-8e91-f37b9726d122
date: 2026-05-01T23:07:32.807Z
endedAt: 2026-05-01T23:42:37.633Z
child: Reina
subject: homework
mode: as-child
gitCommit: 97dd20e
command: npm run npx
duration_ms: 2104826
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: as-child
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +2014s turn.state_changed state="IDLE"
- +2017s transcript.accepted turnState="IDLE" round=28 transcriptLength=105
- +2017s ws.send type="session_state" state="LOADING"
- +2018s turn.state_changed state="LOADING"
- +2018s ws.send type="session_state" state="PROCESSING"
- +2018s turn.state_changed state="PROCESSING"
- +2020s tool.called tool="takeGameScreenshot" argsKeys=["reason"] hasResult=true
- +2020s tool.client_result tool="takeGameScreenshot"
- +2021s transcript.queued turnState="PROCESSING" round=29 transcriptLength=122
- +2023s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +2023s tool.client_result tool="sessionStatus"
- +2026s ws.send type="session_state" state="SPEAKING"
- +2026s turn.state_changed state="SPEAKING"
- +2028s ws.send type="session_state" state="IDLE"
- +2028s turn.state_changed state="IDLE"
- +2028s transcript.replay turnState="IDLE" round=29 transcriptLength=122
- +2028s transcript.accepted turnState="IDLE" round=29 transcriptLength=122
- +2028s ws.send type="session_state" state="LOADING"
- +2028s turn.state_changed state="LOADING"
- +2028s ws.send type="session_state" state="PROCESSING"
- +2028s turn.state_changed state="PROCESSING"
- +2029s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +2029s tool.client_result tool="sessionStatus"
- +2030s transcript.queued turnState="PROCESSING" round=30 transcriptLength=17
- +2032s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +2032s tool.client_result tool="companionAct"
- +2033s ws.send type="session_state" state="SPEAKING"
- +2033s turn.state_changed state="SPEAKING"
- +2035s ws.send type="session_state" state="IDLE"
- +2035s turn.state_changed state="IDLE"
- +2035s transcript.replay turnState="IDLE" round=30 transcriptLength=17
- +2035s transcript.accepted turnState="IDLE" round=30 transcriptLength=17
- +2035s ws.send type="session_state" state="LOADING"
- +2035s turn.state_changed state="LOADING"
- +2035s ws.send type="session_state" state="PROCESSING"
- +2035s turn.state_changed state="PROCESSING"
- +2037s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +2037s tool.client_result tool="companionAct"
- +2040s ws.send type="session_state" state="SPEAKING"
- +2040s turn.state_changed state="SPEAKING"
- +2041s transcript.dropped reason="assistant_owns_turn" turnState="SPEAKING" round=31 transcriptLength=74
- +2041s ws.send type="session_state" state="IDLE"
- +2041s turn.state_changed state="IDLE"
- +2048s transcript.accepted turnState="IDLE" round=31 transcriptLength=96
- +2048s ws.send type="session_state" state="LOADING"
- +2048s turn.state_changed state="LOADING"
- +2048s ws.send type="session_state" state="PROCESSING"
- +2048s turn.state_changed state="PROCESSING"
- +2049s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +2049s tool.client_result tool="sessionStatus"
- +2051s ws.send type="session_state" state="SPEAKING"
- +2051s turn.state_changed state="SPEAKING"
- +2053s ws.send type="session_state" state="IDLE"
- +2053s turn.state_changed state="IDLE"
- +2061s transcript.accepted turnState="IDLE" round=32 transcriptLength=118
- +2061s ws.send type="session_state" state="LOADING"
- +2061s turn.state_changed state="LOADING"
- +2061s ws.send type="session_state" state="PROCESSING"
- +2061s turn.state_changed state="PROCESSING"
- +2062s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +2062s tool.client_result tool="sessionStatus"
- +2064s ws.send type="session_state" state="SPEAKING"
- +2064s turn.state_changed state="SPEAKING"
- +2065s transcript.dropped reason="assistant_owns_turn" turnState="SPEAKING" round=33 transcriptLength=183
- +2066s ws.send type="session_state" state="IDLE"
- +2066s turn.state_changed state="IDLE"
- +2072s transcript.accepted turnState="IDLE" round=33 transcriptLength=12
- +2072s ws.send type="session_state" state="LOADING"
- +2072s turn.state_changed state="LOADING"
- +2072s ws.send type="session_state" state="PROCESSING"
- +2072s turn.state_changed state="PROCESSING"
- +2074s tool.called tool="sessionStatus" argsKeys=[] hasResult=true
- +2074s tool.client_result tool="sessionStatus"
- +2077s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +2077s tool.client_result tool="companionAct"
- +2078s ws.send type="session_state" state="SPEAKING"
- +2078s turn.state_changed state="SPEAKING"
- +2079s ws.send type="session_state" state="IDLE"
- +2079s turn.state_changed state="IDLE"
- +2105s session.ending turnState="IDLE" roundNumber=34 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=68

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 34,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "8bdd7bed-a8a1-40e9-8e91-f37b9726d122",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 68
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 68,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
