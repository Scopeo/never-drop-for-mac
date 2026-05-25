### NeverDrop for macOS
NeverDrop is a lightweight macOS menu bar app that records and transcribes your conversations in real time. It captures both microphone and system audio, uploads audio in chunks, and streams a live transcript — so you never lose a word.

### Features
- Menu bar app — runs quietly in your status bar, out of the way
- Microphone + system audio capture — records your voice and the audio playing through your Mac (meeting participants, media, etc.)
- Live transcription — see a real-time transcript via server-sent events as you record
- Speaker diarization — distinguishes between different speakers with color-coded labels
- Chunked upload — audio is streamed to the server in small chunks so nothing is lost if the app quits unexpectedly
- Background finalization — when you stop recording, upload and transcription finish in the background
- Sign in with Apple — secure authentication with no passwords to remember
- Automatic output device switching — seamlessly adapts when you change headphones or speakers mid-recording

### Requirements
- macOS 14.2 (Sonoma) or later
- Microphone permission
- Screen Recording permission (required for system audio capture)
