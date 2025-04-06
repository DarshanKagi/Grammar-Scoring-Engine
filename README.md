# Grammar Scoring Engine for Voice Samples

An interactive desktop application that records or loads voice samples, transcribes them using OpenAI’s Whisper model, checks grammar/style with LanguageTool, computes readability metrics, and generates a comprehensive report.

---

## Table of Contents

- [Project Description](#project-description)  
- [Features](#features)  
- [Prerequisites](#prerequisites)  
- [How to Install and Run](#how-to-install-and-run)  
- [How to Use the Project](#how-to-use-the-project)  
- [Screenshots / Media](#screenshots--media)  
- [Future Enhancements](#future-enhancements)  
- [Contributing](#contributing)  
- [License](#license)  
- [Credits](#credits)  
- [Author](#author)  
- [Connect with Me](#connect-with-me)  

---

## Project Description

The Grammar Scoring Engine for Voice Samples is a Python/Tkinter desktop application that enables users to:

1. **Record** or **upload** an audio sample (WAV/MP3/M4A).  
2. **Transcribe** speech to text using OpenAI’s Whisper.  
3. **Analyze** the transcript for grammar, typos, punctuation, and style issues via LanguageTool.  
4. **Compute** readability metrics (Flesch, Gunning Fog, etc.) with `textstat`.  
5. **Generate** a detailed, weighted grammar score and comprehensive report.  
6. **Highlight** errors inline and allow interactive correction.  

Ideal for language learners, content creators, and researchers who need quick, quantitative feedback on spoken language fluency and writing clarity.

---

## Features

- **Real‑time Recording & File Upload**  
- **Whisper‑powered Transcription** (base model)  
- **Weighted Grammar Scoring** (grammar, typos, punctuation, style)  
- **Readability & Style Metrics** (Flesch Reading Ease, Flesch‑Kincaid Grade, Gunning Fog)  
- **Inline Error Highlighting & Click‑to‑Correct**  
- **Side‑by‑Side Comparison Mode**  
- **Comprehensive Text Report Export**  
- **Customizable Error Weights**  

---

## Prerequisites

- **Python 3.8+**  
- **FFmpeg** (for audio decoding, if not already on your system)  
- **pip**  

Python packages (install via `pip`):

```bash
pip install tkinter whisper language-tool-python sounddevice soundfile numpy textstat
