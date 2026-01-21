# AirMaestro: Gesture-Controlled Music Synthesis

🎵 **Conduct music with your hands** - Real-time AI-powered gesture recognition that converts hand movements into dynamic music synthesis.

## What is AirMaestro?
AirMaestro is an interactive system that uses computer vision (MediaPipe) to detect hand gestures in real-time and feeds them into Suno AI music generation API. Raise your hand to compose. Lower it to create. Move to conduct.

## Features
- **Real-time hand tracking**: MediaPipe Hand Landmarker detects 21 keypoints per hand at 30+ FPS
- **Gesture-to-MIDI mapping**: Hand position, orientation, and velocity → MIDI parameters
- **AI music generation**: Suno API creates unique melodies based on gesture patterns
- **Live visualization**: Three.js web interface shows hand pose and generated waveforms
- **Zero latency UI**: Streamlit/FastAPI backend for responsive performance

## Tech Stack
- **CV/Pose**: MediaPipe Hands
- **Music Generation**: Suno API (free tier)
- **Backend**: Python 3.11, FastAPI
- **Frontend**: React/Three.js (gesture viz), Streamlit (demo UI)
- **Deployment**: Vercel (frontend) + Heroku/Railway (backend)

## Quick Start
```bash
git clone https://github.com/magictreesproductions/airmaestro-gesture-synth
cd airmaestro-gesture-synth
pip install -r requirements.txt
python app.py
```

## Why This Project Wins Hackathons
✨ **Novelty**: Blends CV + music AI in an interactive, emotional way  
🎯 **Feasibility**: 48-hour buildable with free APIs  
🏆 **Impact**: Demo video shows immediate "wow factor" for judges  
📱 **Accessibility**: No music theory knowledge required - pure gesture = music  

## Use Cases
- Interactive art installations
- Accessibility-focused music creation (gesture-based for motor disabilities)
- Educational: Learn music composition through embodied gesture
- Entertainment: VR/AR music performances

## Contributors
Created by [@mag00s](https://github.com/magictreesproductions) for Hackathon Victory 2026.

## License
MIT - Build on it, remix it, win with it.
