SpeechInSight – Audio & Video Speech Transcription with Speaker Segmentation

SpeechInSight is an AI-powered application that performs speech transcription and speaker segmentation from uploaded audio or video files.
The system extracts audio from media, segments the speech by speaker, and generates transcriptions through a trained model.

The project includes:

FastAPI backend for processing and inference

React frontend for user interaction

AI speech model for transcription

Automatic video → audio conversion

Features

Upload audio or video files

Automatic video-to-audio conversion

Speaker diarization (detect different speakers)

Speech transcription

Interactive web interface

Modular AI pipeline for easy experimentation

Tech Stack
Backend

Python

FastAPI

Uvicorn

PyTorch

Transformers

Librosa

FFmpeg

Frontend

React

Vite

JavaScript / CSS

AI Model

Speech recognition model trained with the Hugging Face ecosystem


Project Structure 

SpeechInSight
│
├── api.py                 # FastAPI server
├── app.py                 # Backend entry point
├── media_utils.py         # Media conversion utilities
├── segmentation.py        # Speaker segmentation logic
├── model.py               # Speech transcription model
├── requirements.txt       # Python dependencies
│
├── final_model/           # Model configuration files
│
└── speech-insight-frontend
    ├── src/               # React components
    ├── public/            # Static assets
    ├── index.html
    ├── package.json
    └── vite.config.js
