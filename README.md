# JARVIS Voice Assistant

A Python voice assistant for Windows. Speak a command and JARVIS answers out loud and runs it on your PC.

## Features
- Wikipedia lookups ("what is...", "who is...", "wikipedia ...")
- Weather (free, no API key) and BBC news headlines
- Word definitions, jokes, date and time
- Open apps (Notepad, Calculator, VLC, VirtualBox, WhatsApp and more)
- Google and YouTube search
- Music playback from your Music folder
- Volume control, battery status, screenshots, public IP lookup
- Shutdown and restart with a 60-second cancel window ("cancel shutdown")

## Requirements
- Windows 10/11 (uses SAPI5 speech, pywin32 and Windows media keys)
- Python 3.9+
- A working microphone and internet connection

## Setup
```bash
pip install -r requirements.txt
python jarvis.py
```
If PyAudio fails to install, use `pip install pipwin` then `pipwin install pyaudio`.

## Example commands
- "what is cybersecurity"
- "weather in London"
- "open notepad"
- "play music"
- "take a screenshot"
- "bye"

## Notes
`main()` is designed to be called by a wake-word listener. Running `jarvis.py` directly starts a continuous listening loop for testing.

## Author
Alexander Ayikwei
