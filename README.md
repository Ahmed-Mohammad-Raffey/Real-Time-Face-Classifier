# Real-Time-Face-Classifier
This project is a real-time computer vision application that detects human faces via webcam and predicts their age group, gender, and emotional expression using custom-trained Convolutional Neural Networks (CNNs).

Developed as part of my 5th semester (BCA), this project showcases the integration of deep learning, image classification, and real-time video processing for intelligent human-centered AI.
Features.

✅ Detects faces in real-time using OpenCV.

👦 Predicts Age Group (e.g., Child, Teen, Adult, Senior).

👨‍💼 Predicts Gender (Male/Female).

😀 Classifies Emotions (Happy, Sad, Angry, Fear, Surprise, Neutral, Disgust).

📦 Each task uses a separate, custom-trained CNN model.

🧩 Modular design for easy updates or replacements of models.

🖥️ Built using Python with a simple command-line interface.

Tech Stack
Component	Tools/Frameworks
Language	Python
Deep Learning	TensorFlow / Keras
Image Processing	OpenCV
Model Training	CNN (Convolutional Neural Networks)
Visualization	Matplotlib
Data Handling	Pandas, NumPy

Datasets Used:

Emotion: FER2013-like dataset with 7 emotion categories

Age & Gender: Cleaned and resized dataset based on UTKFace and custom preprocessed images

All datasets were manually cleaned and split in
Learning Highlights
How to build and train CNN models for classification tasks

Techniques for real-time face detection and annotation

Integration of multiple AI models into a single pipeline

Handling noise, lighting, and performance constraints in real-time ML applications

Future Improvements
🎨 Streamlit or Flask Web UI integration

📈 Use of pre-trained models (e.g., MobileNetV2 for better speed)

🔊 Add audio-based emotion detection

📱 Deploy as a mobile/web app

Acknowledgments
OpenCV team for face detection tools

TensorFlow/Keras community

Inspiration from projects like FaceNet, DeepFace, and UTKFace research

BELOW IS THE SAMPLE WORKING OF THE MODEL ON MY FRIENDS
![Screenshot 2025-05-22 165337](https://github.com/user-attachments/assets/1bba35aa-a284-4e64-92a7-0d88e29be690)
