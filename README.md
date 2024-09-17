Deepfake Detection Platform

This project is a Deepfake Detection Platform built using React for the frontend and Flask for the backend. It allows users to upload 
videos and receive predictions about the authenticity of the content. The platform leverages machine learning techniques to analyze uploaded 
videos and determine if they have been digitally altered (i.e., "deepfaked").


Features

- Video Upload: Users can upload video files through the web interface.
- Deepfake Detection: Once uploaded, videos are processed by a machine learning model hosted on the Flask backend to predict whether 
                    the video contains deepfake content.
- Real-time Feedback: Users receive real-time updates on the status of their video and the final detection results.
- Scalable Architecture: The React frontend communicates with the Flask API, making the architecture modular and scalable.


Tech Stack
- Frontend: React, JavaScript, HTML, CSS
- Backend: Flask, Python
- Machine Learning: Deep learning model for video analysis(CNN & LSTM) (e.g., TensorFlow, PyTorch)
- Deployment: Can be deployed using Docker, or hosted on cloud platforms like AWS or Heroku.


How to Run
- Clone this repository.
- Install dependencies for both the React frontend and Flask backend.
- Start Flask:
    - move to the virtual environment:
        - run :  source fl_venv/bin/activate
- Start backend
    - cd backend
    - node index.js
- Start the React frontend:
    - cd frontend
    - npm install
    - npm start
- Upload a video through the web app, and the model will analyze it for deepfakes.


Future Improvements : 
- Support for more file formats and larger video uploads.
- Enhanced accuracy by improving the underlying detection model.
- Deployment on scalable cloud infrastructure for production use.
