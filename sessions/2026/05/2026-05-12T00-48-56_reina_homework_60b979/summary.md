# Sunny Session Debug Summary

sessionId: 60b97981-5c47-4b29-9f59-8eeb04a48182
date: 2026-05-12T00:48:56.730Z
endedAt: 2026-05-12T00:56:01.601Z
child: Reina
subject: homework
mode: real
gitCommit: 7bbbafb
command: npm run npx
duration_ms: 424871
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
- +244s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=1 word="government" bonusMultiplier=1 wordIndex=1
- +244s transcript.queued turnState="PROCESSING" round=11 transcriptLength=11
- +246s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=2 word="half" bonusMultiplier=1 wordIndex=2
- +248s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=3 word="machine" bonusMultiplier=1 wordIndex=3
- +249s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +249s tool.client_result tool="companionAct"
- +250s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=4 word="pair" bonusMultiplier=1 wordIndex=4
- +250s flow_game.pronunciation_complete game="pronunciation" totalWords=5 correctCount=5 accuracyPct=71 wordsAttempted=7 wordsHit=5 xpEarned=70 bestStreak=4
- +250s ws.send type="session_state" state="SPEAKING"
- +250s turn.state_changed state="SPEAKING"
- +257s ws.send type="session_state" state="IDLE"
- +257s turn.state_changed state="IDLE"
- +257s transcript.replay turnState="IDLE" round=11 transcriptLength=11
- +257s transcript.accepted turnState="IDLE" round=11 transcriptLength=11
- +257s ws.send type="session_state" state="LOADING"
- +257s turn.state_changed state="LOADING"
- +257s ws.send type="session_state" state="PROCESSING"
- +257s turn.state_changed state="PROCESSING"
- +259s transcript.queued turnState="PROCESSING" round=12 transcriptLength=18
- +259s flow_game.game_state_update game="ASTEROIDS" type="game_state_update"
- +259s tool.called tool="sessionLog" argsKeys=["correct","childSaid","word","observation"] hasResult=true
- +259s tool.client_result tool="sessionLog"
- +262s tool.called tool="expressCompanion" argsKeys=["emote","intensity"] hasResult=true
- +262s tool.client_result tool="expressCompanion"
- +264s ws.send type="session_state" state="SPEAKING"
- +264s turn.state_changed state="SPEAKING"
- +268s ws.send type="session_state" state="IDLE"
- +268s turn.state_changed state="IDLE"
- +268s transcript.replay turnState="IDLE" round=12 transcriptLength=18
- +268s transcript.accepted turnState="IDLE" round=12 transcriptLength=18
- +268s ws.send type="session_state" state="LOADING"
- +268s turn.state_changed state="LOADING"
- +268s ws.send type="session_state" state="PROCESSING"
- +268s turn.state_changed state="PROCESSING"
- +269s transcript.queued turnState="PROCESSING" round=13 transcriptLength=15
- +270s tool.called tool="companionAct" argsKeys=["type","payload"] hasResult=true
- +270s tool.client_result tool="companionAct"
- +272s transcript.queued turnState="PROCESSING" round=13 transcriptLength=16
- +273s ws.send type="session_state" state="SPEAKING"
- +273s turn.state_changed state="SPEAKING"
- +280s ws.send type="session_state" state="IDLE"
- +280s turn.state_changed state="IDLE"
- +280s transcript.replay turnState="IDLE" round=13 transcriptLength=16
- +280s transcript.accepted turnState="IDLE" round=13 transcriptLength=16
- +280s ws.send type="session_state" state="LOADING"
- +280s turn.state_changed state="LOADING"
- +280s ws.send type="session_state" state="PROCESSING"
- +280s turn.state_changed state="PROCESSING"
- +282s tool.called tool="expressCompanion" argsKeys=["emote","intensity"] hasResult=true
- +282s tool.client_result tool="expressCompanion"
- +286s ws.send type="session_state" state="SPEAKING"
- +286s turn.state_changed state="SPEAKING"
- +293s ws.send type="session_state" state="IDLE"
- +293s turn.state_changed state="IDLE"
- +293s transcript.accepted turnState="IDLE" round=14 transcriptLength=3
- +293s ws.send type="session_state" state="LOADING"
- +293s turn.state_changed state="LOADING"
- +293s ws.send type="session_state" state="PROCESSING"
- +293s turn.state_changed state="PROCESSING"
- +295s ws.send type="session_state" state="SPEAKING"
- +295s turn.state_changed state="SPEAKING"
- +300s ws.send type="session_state" state="IDLE"
- +300s turn.state_changed state="IDLE"
- +353s transcript.accepted turnState="IDLE" round=15 transcriptLength=17
- +353s ws.send type="session_state" state="LOADING"
- +353s turn.state_changed state="LOADING"
- +353s ws.send type="session_state" state="PROCESSING"
- +353s turn.state_changed state="PROCESSING"
- +355s ws.send type="session_state" state="SPEAKING"
- +355s turn.state_changed state="SPEAKING"
- +363s ws.send type="session_state" state="IDLE"
- +363s turn.state_changed state="IDLE"
- +365s transcript.accepted turnState="IDLE" round=16 transcriptLength=37
- +365s ws.send type="session_state" state="LOADING"
- +365s turn.state_changed state="LOADING"
- +365s session.ending turnState="LOADING" roundNumber=16 isEnding=true childName="Reina" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=202
- +365s ws.send type="session_state" state="IDLE"
- +365s turn.state_changed state="IDLE"
- +365s engine.session_finalized totalAttempts=0 accuracy=0
- +365s engine.progression_computed level=75 totalXP=7450 wordsMastered=30

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 16,
  "isEnding": true,
  "childName": "Reina",
  "sessionId": "60b97981-5c47-4b29-9f59-8eeb04a48182",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 202
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 202,
  "rewardLogEntries": 16
}
```

## Upload
Session saved locally. Upload not configured yet.
