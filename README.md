# STT-Whisper

# 🎙️ Whisper Speech-to-Text Transcription Tool

This project uses OpenAI's [Whisper](https://github.com/openai/whisper) model to convert audio files into text using state-of-the-art speech recognition.

##  Features

- 🎧 Transcribes speech from audio files (MP3, WAV, etc.)
- 🌍 Automatically detects the spoken language
- ⚡ Uses the fast and lightweight `turbo` model
- 📄 Outputs clean, readable text

##  Getting Started

### 1. Clone the Repository
git clone https://github.com/Hrishika1102/STT-Whisper.git

### 2. Install Requirements
Make sure you have Python 3.8 or higher and ffmpeg installed.
pip install -r requirements.txt

### 3. How It Works
  Loads the Whisper "turbo" model.
  Prepares the audio (pads/trims to 30s).
  Converts audio to Mel spectrogram.
  Detects language.
  Transcribes the audio and prints the text.

## License
MIT License. See LICENSE for details.

