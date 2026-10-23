# Final Project

## AI-Based Web Application Development and Deployment

### Project Overview
This project is an AI-based web application developed using Python (Flask) and embedded Watson AI libraries for emotion detection. The application takes text feedback provided by customers and analyzes it to detect underlying emotions such as joy, sadness, anger, disgust, and fear.

### Features
- **Emotion Detection:** Extracts fine-grained emotions from text input using embedded Watson AI libraries.
- **Web Interface:** Interactive HTML/JavaScript front-end for users to submit text and view analysis results.
- **REST API:** Flask backend exposing endpoints to handle analysis requests.
- **Error Handling:** Robust validation for empty or invalid input text.
- **Unit Testing:** Integrated unit tests ensuring feature reliability.

### Repository Structure
- `EmotionDetection/`: Core Python package containing Watson AI emotion detection logic.
- `server.py`: Flask application server running web endpoints.
- `static/`: Frontend scripts and static assets.
- `templates/`: HTML interface layout.
- `test_emotion_detection.py`: Unit tests for emotion detection capabilities.

### License
This repository is licensed under the Apache 2.0 License.
