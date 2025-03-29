# French Audio Transcription App

## Overview

This application allows users to upload one or multiple French audio files, transcribe them using OpenAI's Whisper model, and compile the transcriptions into a single Word document. The app is built with Streamlit, offering an easy-to-use interface to manage audio uploads, transcription, and document download.

## Features

- **Multi-File Upload:** Upload one or several audio files at once.
- **Whisper Transcription:** Leverages OpenAI's Whisper model to transcribe French audio.
- **Word Document Generation:** Compiles all transcriptions into a single Word document with each transcription in its own section.
- **Downloadable Output:** Provides a download button to easily save the Word document.

## Prerequisites

- Python 3.7 or higher
- [Streamlit](https://streamlit.io/)
- [openai-whisper](https://github.com/openai/whisper)
- [python-docx](https://python-docx.readthedocs.io/en/latest/)
- [ffmpeg](https://ffmpeg.org/) – Required by Whisper for processing audio files

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/audio-transcription-app.git
   cd audio-transcription-app

2. **Create and activate a virtual environment (optional but recommended):**

    ```bash
    python -m venv venv
    # On macOS/Linux:
    source venv/bin/activate
    # On Windows:
    venv\Scripts\activate

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt

4. **Install ffmpeg: Using Conda (recommended):**

    ```bash
    conda install -c conda-forge ffmpeg


## Usage

   ```bash
   streamlit run app.py




