# Twitch Audio Grabber

Transcribe audio from Twitch stream.  

Uses `twitchrealtimehandler` for capture of Twitch stream audio data, and Google Speech API for transcription.

## Setup Requirements

### Install `ffmpeg`:
```
sudo apt update && sudo apt install ffmpeg
```

### Install `ffmpeg-python`:
```
pip install ffmpeg-python
```

## Usage
```
python main.py --twitch-url https://www.twitch.tv/qtcinderella --segment-length 5 
```