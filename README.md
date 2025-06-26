# 🎙️ Voice to Text (V2T) Project

## 📌 Overview

The **V2T project** is designed to convert voice recordings into text transcriptions and translate them between **English** and **German**. It includes scripts for:
- Recording audio
- Transcribing using OpenAI's Whisper model
- Detecting the language
- Translating the text

---

## ⚙️ Installation

### ✅ Requirements

Ensure you have **Python 3.8+** installed.

Install the required dependencies:

```bash
pip install whisper langdetect googletrans==4.0.0-rc1 sounddevice scipy keyboard numpy
```
---

## 🚀 Usage

### 🎤 Record & Transcribe Audio

To start a new session and record voice input:

```bash
cd Final_code
python Push_to_translate.py
```

- Enter a **session name** when prompted.
- Press the **spacebar** to begin recording.
- Press **'s'** to stop.
- The script saves the **transcription** and **translation** in the `Live_Translations/<session_name>/` directory.

---

### 📦 Batch Transcription & Translation

To run batch tests on multiple files:

```bash
cd Batch_Testing_Ai
python Batch_Transcribe&Translate_efficiency_test.py
```

The script will:
- Read sample audio files from the input folder
- Transcribe and translate them
- Save results in the output folder

---

## 📌 Example

```bash
python Final_code/Push_to_translate.py
```

You will be prompted to:
1. Enter a session name  
2. Record audio (press **spacebar**)  
3. Stop recording (press **'s'**)  

Transcriptions and translations are saved in:

```
Live_Translations/<your_session_name>/
```

---

## 📄 License

**MIT License**

```
MIT License

Copyright (c) 2025 TPesch & JPerumal

Permission is hereby granted, free of charge, to any person obtaining a copy of this software 
and associated documentation files (the "Software"), to deal in the Software without restriction, 
including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, 
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, 
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or 
substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING 
BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. 
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, 
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE 
OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
