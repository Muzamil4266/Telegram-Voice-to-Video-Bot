Telegram Voice to Video Bot

Convert voice recordings into videos automatically using Telegram.

Features

- Send a WAV voice recording to Telegram Saved Messages.
- Automatically downloads the audio.
- Creates a vertical MP4 video using images from a local folder.
- Generates subtitles using Whisper AI.
- Enhances audio quality.
- Adds transitions and visual effects.
- Sends the finished video back to Telegram.

How It Works

1. Send a WAV file to Telegram Saved Messages.
2. The bot detects the new audio file.
3. Audio is enhanced and transcribed.
4. Images are selected from the local photo library.
5. A video is generated automatically.
6. The MP4 video is sent back to Telegram.

Requirements

- Python 3.10+
- FFmpeg
- ImageMagick
- Telegram API credentials
- Whisper AI model

Installation

pip install -r requirements.txt

Configure your Telegram API ID and API Hash in the script.

Run

python Instagram-reel-editor-automation.py

Output

Generated videos are saved locally and automatically uploaded to your Telegram Saved Messages.

License

MIT License
