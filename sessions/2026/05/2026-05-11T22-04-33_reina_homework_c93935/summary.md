# Sunny Session Debug Summary

sessionId: c93935cd-baf9-4bca-a23a-d9ed458b114b
date: 2026-05-11T22:04:33.238Z
endedAt: 2026-05-11T22:06:13.122Z
child: Reina
subject: homework
mode: as-child
gitCommit: 7bbbafb
command: npm run npx
duration_ms: 99884
result: completed

## Env Flags
- TTS_ENABLED: true
- SUNNY_MODE: as-child
- SUNNY_CHILD: reina
- SUNNY_SUBJECT: homework
- ADVENTURE_MAP: true
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=false sttOnly=false
- +0s session.start_requested childName="Reina" companionName="Matilda"
- +6s canvas.draw mode="worksheet_pdf"
- +6s ws.send type="session_started" childName="Reina" companion="Matilda" companionName="Matilda" emoji="📚" voiceId="jBpfuIE2acCO8z3wKNLl" openingLine="Reina! Good to see you — what's new?" goodbye="That was a championship round, Reina! やった! See you next time, champ! 📚" debugBrowserTts=false debugMode=false diagKiosk=false
- +6s canvas.draw mode="idle"
- +6s ws.send type="session_state" state="LOADING"
- +6s turn.state_changed state="LOADING"
- +6s ws.send type="session_state" state="PROCESSING"
- +6s turn.state_changed state="PROCESSING"
- +6s ws.send type="session_state" state="SPEAKING"
- +6s turn.state_changed state="SPEAKING"
- +7s ws.send type="session_state" state="IDLE"
- +7s turn.state_changed state="IDLE"
- +7s session.started sessionType="homework" companionName="Matilda"
- +32s flow_game.voice_control game="karaoke" type="voice_control"
- +35s flow_game.karaoke_progress game="karaoke-reading" event="progress" wordIndex=0 totalWords=68 accuracyPct=0 hesitations=0 flaggedCount=0 skippedCount=0 spelledCount=0
- +35s flow_game.voice_control game="karaoke" type="voice_control"
- +100s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "c93935cd-baf9-4bca-a23a-d9ed458b114b",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 0
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": false,
  "sessionNotesWritten": false,
  "rewardsWritten": false,
  "shouldPersistSessionData": false,
  "conversationTurns": 0,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
