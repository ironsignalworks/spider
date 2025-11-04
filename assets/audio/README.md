Place your audio files here. The game will automatically load these filenames if present.

Folders
- assets/audio/sfx
- assets/audio/music

Supported formats (auto-detected): .mp3, .ogg, .wav

SFX files (put in assets/audio/sfx/)
- webDeploy
- enemyKill
- damage
- scorePoint
- scoreCollect
- nuke
- waveStart
- waveComplete
- nukeCharged
- gameOver
- button

Example: assets/audio/sfx/webDeploy.mp3

Background music (put in assets/audio/music/)
- bg

Example: assets/audio/music/bg.mp3

Notes
- You can provide .ogg or .wav instead of .mp3; the game picks a supported extension automatically.
- Volumes are preset in code; adjust in index.html if needed (SFX_VOL and music volume in startMusic).
