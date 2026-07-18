# Sunny Session Debug Summary

sessionId: e23cfb8b-f1a6-44fb-b944-45fad9c2c8f7
date: 2026-07-18T17:59:59.701Z
endedAt: 2026-07-18T18:00:49.027Z
child: Ila
subject: spelling
mode: default
gitCommit: c06d4f0
command: npm run npx
duration_ms: 49326
result: errored

## Env Flags
- TTS_ENABLED: 
- SUNNY_MODE: 
- SUNNY_CHILD: 
- SUNNY_SUBJECT: 
- SUNNY_PREVIEW_MODE: 
- ADVENTURE_MAP: 
- SUNNY_STATELESS: 

## Timeline
- +0s session.constructed diagKiosk=false silentTts=true sttOnly=true chartChildId="ila"
- +0s session.start_requested childName="Ila" companionName="Elli"
- +0s ws.send type="session_started" childName="Ila" companion="Elli" companionName="Elli" emoji="" voiceId="MF3mGyEYCl7XYWbV9V6O" openingLine="" goodbye="" debugBrowserTts=false debugMode=false diagKiosk=false
- +0s canvas.draw mode="idle"
- +49s session.ending turnState="IDLE" roundNumber=0 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=0
- +49s engine.session_finalized totalAttempts=0 accuracy=0
- +49s engine.progression_computed level=86 totalXP=8590 wordsMastered=18

## Errors
- [2026-07-18T18:00:49.027Z] Post-session chain error

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 0,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "e23cfb8b-f1a6-44fb-b944-45fad9c2c8f7",
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
  "persistedSessionData": true,
  "postSessionError": "Anthropic API key is missing. Pass it using the 'apiKey' parameter or the ANTHROPIC_API_KEY environment variable.",
  "shouldPersistSessionData": true,
  "conversationTurns": 0,
  "rewardLogEntries": 0
}
```

## Upload
Session saved locally. Upload not configured yet.
