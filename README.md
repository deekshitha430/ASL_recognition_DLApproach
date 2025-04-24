🧠 ASL Recognition – Deep Learning Approach


This project is a deep learning-based application that recognizes American Sign Language (ASL) hand gestures using computer vision. The model processes input from a webcam or image file and predicts the corresponding ASL alphabet gesture in real-time.

🎯 Features
🖐️ Real-time ASL gesture recognition using webcam input

🧠 CNN-based deep learning model for alphabet classification

📸 Preprocessed hand gesture image dataset

📊 Live prediction overlay using OpenCV

📁 Modular code for easy training and inference

🧰 Tech Stack
Language: Python

Libraries: TensorFlow / Keras, OpenCV, NumPy, Matplotlib

Model: Convolutional Neural Network (CNN)

Dataset: ASL Alphabet Dataset

🚀 Getting Started
🔧 Clone the repo
bash
Copy
Edit
git clone https://github.com/deekshitha430/ASL_recognition_DLApproach.git
cd ASL_recognition_DLApproach
📦 Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
🏁 Run the model
bash
Copy
Edit
python asl_predictor.py
Make sure your webcam is connected before launching real-time recognition.

📁 Project Structure
graphql
Copy
Edit
├── data/                   # Dataset (ASL alphabet images)
├── model/                  # Trained model files
├── asl_predictor.py        # Real-time ASL prediction script
├── train_model.py          # Model training script
├── requirements.txt        # Python dependencies
└── README.md
