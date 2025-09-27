# Face Recognition and Detection System

## 📌 Project Description
The **Face Recognition and Detection System** is an AI-powered application that detects and recognizes human faces while analyzing key attributes such as **identity, age, gender, and emotion**. The system utilizes deep learning models for facial recognition and feature extraction to provide real-time insights.

## 🚀 Features
- **Face Detection:** Detects human faces in images or video streams.
- **Face Recognition:** Identifies and verifies individuals using a trained database.
- **Age Prediction:** Estimates the age of a person.
- **Gender Classification:** Determines whether the detected face is male or female.
- **Emotion Recognition:** Analyzes facial expressions and classifies emotions (happy, sad, neutral, angry, etc.).
- **Real-time Processing:** Works on live video feeds using OpenCV and a webcam.

## 🛠️ Tech Stack

**Programming Language:**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  

**Libraries & Frameworks:**  
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)  
![Dlib](https://img.shields.io/badge/Dlib-5C2D91?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAABd0lEQVRYhe2XMWrCQBSEv2GBOUJAiHoxUYiL0DRMS3A0EQHqCSU5iZ0hLOZEoUKs1j6/8uRMCjz9X7Hw/3qBnHIgGmJqM77Hiq2Eaj1gCLYfYFAx0KxWHjx1VGwgKaQXy5xS3WBK1Uqv7X1k5wggAiAKJ+uHk3zzAbw+X2aW9mRBhZCqrcHhwRDIuwgSVXW9Tx4x5W9IAJe+Pf9OZZz/5bM0JHcCUxGjh/95FglFYpR1SkfL1fT+UgVwqFppjU8M3l+f+mJknhJvU+fJXxM2/Y1rL+nZVgfp62f0xeKZPFPkXhzlH92AEk1mX+1mCzIq+H6M0k5i8iM/BMwE+7/L/TN+T2Mr4AJC1k7YUhKALvU4LQeH4r5aTVjF3sS6BaZoj7VQ1uM6EAAAAASUVORK5CYII=)  
![FaceNet](https://img.shields.io/badge/FaceNet-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)  
![DeepFace](https://img.shields.io/badge/DeepFace-007ACC?style=for-the-badge&logo=python&logoColor=white)  
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)  
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)  
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)  

## 📂 Project Structure
```
Face_Recognition_Detection_System/
│── models/            # Pretrained deep learning models
│── datasets/          # Face images for training/testing
│── src/               # Source code files
│   ├── detect_faces.py  # Face detection script
│   ├── recognize_faces.py  # Face recognition implementation
│   ├── predict_age.py  # Age estimation module
│   ├── predict_gender.py  # Gender classification module
│   ├── detect_emotion.py  # Emotion recognition module
│   ├── main.py  # Main application file
│── requirements.txt   # List of dependencies
│── README.md          # Project documentation
```

## 🔧 Installation & Setup
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/Face-Recognition-Detection.git
   cd Face-Recognition-Detection
   ```

2. **Create a Virtual Environment (Optional):**
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the Application:**
   ```sh
   python main.py
   ```

## 📷 How It Works
1. The camera captures a live video feed or an image is provided.
2. The face detection model identifies faces in the frame.
3. The recognition model compares detected faces with the database for identification.
4. Age and gender models analyze facial features to predict age and gender.
5. The emotion recognition model determines the person's emotional state.
6. Results are displayed in real time on the console or UI.

## 📝 Future Enhancements
- Enhance accuracy using more advanced deep learning models.
- Deploy as a web application using Flask/Django.
- Integrate with a cloud database for large-scale face recognition.
- Improve speed and efficiency with optimized algorithms.



https://github.com/user-attachments/assets/6dd2f829-a6d5-49ab-b3ee-825cc178182a




