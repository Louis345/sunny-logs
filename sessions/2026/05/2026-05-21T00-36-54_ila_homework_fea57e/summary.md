# Sunny Session Debug Summary

sessionId: fea57e10-1657-43f4-a7cb-08f9c130a35e
date: 2026-05-21T00:36:54.004Z
endedAt: 2026-05-21T00:45:26.718Z
child: Ila
subject: homework
mode: real
gitCommit: f2754be
command: npm run npx
duration_ms: 512714
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
- +472s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +472s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=1 word="ago" bonusMultiplier=1 wordIndex=0
- +472s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +472s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +473s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=1
- +473s transcript.accepted turnState="IDLE" round=34 transcriptLength=36
- +473s ws.send type="session_state" state="LOADING"
- +473s turn.state_changed state="LOADING"
- +473s ws.send type="session_state" state="IDLE"
- +473s turn.state_changed state="IDLE"
- +475s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +475s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +475s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +475s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=2 word="above" bonusMultiplier=1 wordIndex=1
- +475s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +475s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +475s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=2
- +476s transcript.accepted turnState="IDLE" round=35 transcriptLength=6
- +476s ws.send type="session_state" state="LOADING"
- +476s turn.state_changed state="LOADING"
- +476s ws.send type="session_state" state="IDLE"
- +476s turn.state_changed state="IDLE"
- +477s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +477s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +477s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +477s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=3 word="away" bonusMultiplier=1 wordIndex=2
- +477s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +477s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +478s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +478s transcript.accepted turnState="IDLE" round=36 transcriptLength=5
- +478s ws.send type="session_state" state="LOADING"
- +478s turn.state_changed state="LOADING"
- +478s ws.send type="session_state" state="IDLE"
- +478s turn.state_changed state="IDLE"
- +481s flow_game.pronunciation_miss game="pronunciation" type="pronunciation_miss" word="about" wordIndex=3 attempt=1
- +481s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +481s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +481s transcript.accepted turnState="IDLE" round=37 transcriptLength=3
- +481s ws.send type="session_state" state="LOADING"
- +481s turn.state_changed state="LOADING"
- +481s ws.send type="session_state" state="IDLE"
- +481s turn.state_changed state="IDLE"
- +481s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=3
- +483s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +483s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +483s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +483s flow_game.pronunciation_hit game="pronunciation" type="pronunciation_hit" streak=1 word="about" bonusMultiplier=1 wordIndex=3
- +483s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +483s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +484s flow_game.game_state_update game="pronunciation" type="game_state_update" wordIndex=4
- +486s transcript.accepted turnState="IDLE" round=38 transcriptLength=11
- +486s ws.send type="session_state" state="LOADING"
- +486s turn.state_changed state="LOADING"
- +486s ws.send type="session_state" state="IDLE"
- +486s turn.state_changed state="IDLE"
- +486s transcript.accepted turnState="IDLE" round=39 transcriptLength=12
- +486s ws.send type="session_state" state="LOADING"
- +486s turn.state_changed state="LOADING"
- +486s ws.send type="session_state" state="IDLE"
- +486s turn.state_changed state="IDLE"
- +492s transcript.accepted turnState="IDLE" round=40 transcriptLength=19
- +492s ws.send type="session_state" state="LOADING"
- +492s turn.state_changed state="LOADING"
- +492s ws.send type="session_state" state="IDLE"
- +492s turn.state_changed state="IDLE"
- +496s flow_game.voice_control game="pronunciation" type="voice_control"
- +500s transcript.accepted turnState="IDLE" round=41 transcriptLength=118
- +500s ws.send type="session_state" state="LOADING"
- +500s turn.state_changed state="LOADING"
- +500s ws.send type="session_state" state="PROCESSING"
- +500s turn.state_changed state="PROCESSING"
- +503s tool.called tool="sessionEnd" argsKeys=["childName","reason"] hasResult=true
- +503s tool.client_result tool="sessionEnd"
- +505s ws.send type="session_state" state="SPEAKING"
- +505s turn.state_changed state="SPEAKING"
- +505s session.ending turnState="SPEAKING" roundNumber=42 isEnding=true childName="Ila" canvasMode="idle" activeGame=null pendingTranscript=false pendingTranscriptLength=0 wbActive=false wbRound=0 spellCheckSessionActive=false activeSpellCheckWord=null tts="on" conversationTurns=63
- +505s ws.send type="session_state" state="IDLE"
- +505s turn.state_changed state="IDLE"
- +505s engine.session_finalized totalAttempts=56 accuracy=0.7857142857142857
- +505s engine.progression_computed level=100 totalXP=9945 wordsMastered=19

## Errors
- none recorded

## Final State
```json
{
  "turnState": "IDLE",
  "roundNumber": 42,
  "isEnding": true,
  "childName": "Ila",
  "sessionId": "fea57e10-1657-43f4-a7cb-08f9c130a35e",
  "canvasMode": "idle",
  "activeGame": null,
  "pendingTranscript": false,
  "pendingTranscriptLength": 0,
  "wbActive": false,
  "wbRound": 0,
  "spellCheckSessionActive": false,
  "activeSpellCheckWord": null,
  "tts": "on",
  "conversationTurns": 63
}
```

## Relevant Artifacts
```json
{
  "persistedSessionData": true,
  "sessionNotesWritten": true,
  "rewardsWritten": true,
  "shouldPersistSessionData": true,
  "conversationTurns": 63,
  "rewardLogEntries": 18
}
```

## Upload
Session saved locally. Upload not configured yet.
