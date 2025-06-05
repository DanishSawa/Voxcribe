# Voxcribe
A powerful and user-friendly web application for Text-to-Speech (TTS) and Speech-to-Text (STT) processing, built with Python and Streamlit, powered by Azure Cognitive Services and OpenAI ChatGPT-4. This tool supports multi-language, multi-voice rendering, audio transcription, and translation — all from one sleek interface.

## Features:

✅ Text to Speech (TTS)

Render single or multiple phrases to audio.
Supports multiple languages and Azure voice talents.
Download generated audio as a ZIP file.
Custom UI for selecting voices by language.

✅ Speech to Text (STT)

Upload structured or unstructured .wav files (ZIP-supported).
Auto-detect language or specify manually.
Transcribe speech to text with high accuracy.
Optional translation into multiple target languages.
Download transcription files as CSV or combined ZIP.

## How to Use:

Open the notebook in Jupyter or JupyterLab.
Make sure your Azure subscription key and region are set correctly.
Run each cell step-by-step to interact with the UI and process audio or text.

## File Organization:

MultiLanguage_Speech_Renderer.ipynb   # Main notebook

audio-files-folder             # Input WAVs or ZIP for STT

text-csv-file                 # Input csv for TTS # Refer to the csv template

## Text CSV File:

Refer the csv template where you can add multiple texts and add multiple languages.

## Use Cases:

Creating voiceovers in multiple languages.
Transcribing and translating audio files.
Building prototypes for IVR, accessibility, or education tools.

## Notes:

Azure Speech API keys are required for TTS and STT.
OpenAI API is optional (for translation or language detection).


