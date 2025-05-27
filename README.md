# VibeSense

**Real-Time Emotion-Based Music Recommender Web App**

VibeSense uses webcam-based facial emotion detection powered by AI/ML to recommend music that matches your current mood. It combines computer vision, machine learning, and web technologies to create a seamless and personalized music experience.

## Features

- Real-time emotion detection using webcam
- AI/ML-based emotion classification model
- Music recommendations based on detected emotions
- User authentication and history tracking (Firebase)
- Responsive and modern frontend (React + Tailwind CSS)
- Backend API for model inference and music management

## Tech Stack

- **Frontend:** React, Tailwind CSS, react-webcam
- **Backend:** Node.js, Express.js, Flask/FastAPI (for ML model)
- **Machine Learning:** TensorFlow/Keras, OpenCV, FER-2013 dataset
- **Authentication & Storage:** Firebase Auth and Firestore
- **Deployment:** Vercel (frontend), Render (backend)


## Project Structure

vibesense/
├── backend/ # Flask/FastAPI app + ML model serving
├── frontend/ # React app
├── model/ # Trained ML model files
├── notebook/ # Jupyter notebooks for training
├── README.md # Project overview and instructions
