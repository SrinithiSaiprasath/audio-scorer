# 🎙️ Grammar Scoring Engine

Welcome to the **Grammar Scoring Engine**, a Streamlit-based web application that allows users to:

- Upload an audio file (`.mp3`, `.wav`, `.m4a`)
- Automatically transcribe the audio using Whisper
- Analyze the transcribed text using grammar correction tools
- Display a grammar score out of 100
- Provide feedback and grammar suggestions

---

## 🚀 How It Works

1. **Upload Audio**  
   The user uploads an audio file in a supported format.

2. **Transcription with Whisper**  
   The app uses the `whisper` model to convert speech to text.

3. **Grammar Analysis**  
   Transcribed text is analyzed using `language_tool_python`, and:
   - A grammar score is generated.
   - Grammar mistakes are highlighted with suggestions.

---

## 🖼️ App Interface Preview

| Section | Description |
|--------|-------------|
| Title  | 🎙️ Grammar Scoring Engine |
| Upload | Upload audio file (MP3, WAV, M4A) |
| Transcription | Displays the converted text |
| Score | Shows a score out of 100 |
| Grammar Errors | Lists grammar issues with suggestions |

---

## 📂 File Structure

```bash
project/
│
├── app.py                 # Main Streamlit app
├── Functions.py           # Contains transcribe_audio() and grammar_analysis()
├── README.md              # This file
├── requirements.txt       # Python dependencies
```

## 📦 Requirements

To run the Grammar Scoring Engine, you need to install the following Python dependencies.

### ✅ Install Using pip

```bash
pip install -r requirements.txt
streamlit
whisper
language-tool-python
```
### For Ubuntu/Debian:
```bash
sudo apt update
sudo apt install ffmpeg
```
### For macOS (with Homebrew):
```bash
Edit
brew install ffmpeg
```

##  🎥 Demo Photo
📌 Watch how the Grammar Scoring Engine works in real-time:
![Screenshot 2025-04-06 184655](https://github.com/user-attachments/assets/8d07388e-1a91-47bd-997f-a19944486ad4)

## 📬 Feedback
Do give your feedback here : scsrinithi@gmail.com




