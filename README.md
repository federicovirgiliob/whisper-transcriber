# 🎧 Whisper Transcriber

A simple Python script to automatically transcribe audio files using OpenAI's Whisper model.

## 🚀 Features
- Supports `.wav`, `.mp3`, `.m4a` files
- Uses OpenAI's Whisper for high-quality transcription
- Saves transcriptions as `.txt` files
- Generates a downloadable ZIP file of transcriptions

## 📦 Installation & Setup
1. Install required dependencies:
   ```bash
   pip install -q git+https://github.com/openai/whisper.git
   sudo apt install ffmpeg -y
   ```
2. Clone the repository:
   ```bash
   git clone https://github.com/federicovirgiliob/whisper-transcriber.git
   cd whisper-transcriber
   ```
3. Run the script:
   - **In Google Colab**: Upload `transcriber.ipynb`
   - **Locally**: Run:
     ```bash
     python transcriber.py
     ```

## 🎤 How to Use
1. Upload your audio files (`.wav`, `.mp3`, `.m4a`).
2. The script will automatically transcribe them using Whisper.
3. Transcriptions are saved as `.txt` files.
4. You can download a ZIP file containing all transcriptions.

## 🛠 Requirements
- **Python 3.8+** (Recommended)
- OpenAI Whisper
- ffmpeg

Install dependencies with:
```bash
pip install -r requirements.txt
```

## 🔗 Links
- Whisper GitHub: [Whisper Repo](https://github.com/openai/whisper)
- Google Colab: [https://colab.research.google.com/drive/1FKKupND_rtf2zZFppIu4WRyOE5xCdDyD?usp=sharing]

