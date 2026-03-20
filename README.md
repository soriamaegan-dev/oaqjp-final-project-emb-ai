# 🤖 Emotion Detection Web App

An AI-powered web application that detects emotions in text using the 
Watson NLP library. Built with Python and deployed with Flask.

## 📖 About
This application analyzes text input and identifies the underlying emotions
including anger, disgust, fear, joy, and sadness. It uses IBM's Watson NLP
Emotion Predict function to analyze text and returns the dominant emotion
along with confidence scores for each emotion.

## 🚀 Features
- Detects 5 emotions: anger, disgust, fear, joy, and sadness
- Returns confidence scores for each emotion
- Identifies the dominant emotion in any text
- Simple and intuitive web interface
- Error handling for blank or invalid input
- REST API endpoint for emotion analysis

## 🛠️ Tech Stack
- **AI/NLP**: IBM Watson NLP Library
- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Testing**: Python unittest
- **Code Quality**: Pylint (10.00/10)

## 📂 Project Files
| File | Description |
|------|-------------|
| `server.py` | Flask web server and API endpoints |
| `EmotionDetection/emotion_detection.py` | Watson NLP emotion detector function |
| `EmotionDetection/__init__.py` | Python package initializer |
| `test_emotion_detection.py` | Unit tests for all 5 emotions |
| `templates/index.html` | Web application frontend |
| `static/mywebscript.js` | Frontend JavaScript |

## 🔧 Run Locally
```bash
git clone https://github.com/soriamaegan-dev/oaqjp-final-project-emb-ai
cd oaqjp-final-project-emb-ai
pip install flask requests
python3 server.py
```
Then open your browser at `http://localhost:5000`

## 🧪 Run Unit Tests
```bash
python3 -m unittest test_emotion_detection.py -v
```
All 5 tests pass ✅

## 📊 Example Output
```
For the given statement, the system response is
'anger': 0.006, 'disgust': 0.002, 'fear': 0.009,
'joy': 0.972 and 'sadness': 0.055.
The dominant emotion is joy.
```

## ✅ Tasks Completed
- [x] Task 1: Cloned project repository
- [x] Task 2: Created emotion detection app using Watson NLP
- [x] Task 3: Formatted output with dominant emotion
- [x] Task 4: Packaged as EmotionDetection Python package
- [x] Task 5: Unit tests for all 5 emotions (5/5 passing)
- [x] Task 6: Flask web deployment
- [x] Task 7: Error handling for blank input
- [x] Task 8: Static code analysis (Pylint 10.00/10 ⭐)

## 🎓 Built As Part Of
IBM AI Developer Professional Certificate — Coursera  
Final Project: Emotion Detection Web Application
