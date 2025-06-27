# TrackMyLane
A real-time lane detection system that combines traditional computer vision with smart visual cues and voice-controlled commands. Designed to assist with safe driving and lane discipline using OpenCV, Python, and optional speech recognition.

🚀 Features
✈️ Real-Time Lane Detection from dashcam or test videos

🔍 Edge Detection + Hough Transform to identify lane lines

💃 Instruction Overlay: Dynamic text displayed based on lane detection status

Two Operating Modes:
  Auto Mode: Automatically detects lanes and displays real-time feedback
🔮 Voice-Controlled Mode: Allows user to give voice commands like "Drift out of lane" or "Stop drifting"

🗣 Text-to-Speech Feedback for detected instructions

🔊 Optional Voice Assistant for command-based control

📊 Lane Centering Detection: Alerts if vehicle is deviating from lane center

📅 Overlay Visuals: Highlighted lane area with green/red color coding based on position

📄 Includes complete documentation, requirement setup, and demo video link

📚 Tech Stack
Tool            Usage

Python -     Core logic

OpenCV -     Video processing & lane detection

NumPy  -     Image array & math operations

SpeechRecognition    -    Recognize voice commands

Pyttsx3 -    Text-to-speech output

Threading -  Background voice processing
