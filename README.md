# Synergy
🛡️ DeepFake Shield: Real-Time Audio/Video Authenticator
DeepFake Shield is a sophisticated browser extension and AI-powered backend designed to combat the rise of hyper-realistic AI-generated media. It provides users with a real-time "Trust Score" to help distinguish between authentic human content and AI-generated deepfakes.
🚀 Project Overview
In an era of digital mistrust, DeepFake Shield acts as a protective layer for the browser, analyzing live media streams (Zoom calls, YouTube videos, audio clips) for robotic artifacts, facial landmark inconsistencies, and frequency anomalies.
🛠️ The Tech Stack

Frontend: Chrome Extension (Manifest V3, Vanilla JS, CSS3)
Backend: Python (FastAPI, Uvicorn)
AI/ML Layer:

Audio: Hugging Face (Wav2Vec2 / Specialized Deepfake Detectors)
Video: OpenCV, Dlib (Facial Landmark Consistency)
Processing: Librosa (MFCC extraction), NumPy, PyTorch
