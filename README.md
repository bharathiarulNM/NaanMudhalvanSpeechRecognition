# NaanMudhalvanSpeechRecognition
🎙️ Speech Recognition Project
This project focuses on recognizing and processing human speech using machine learning techniques. It includes multiple speech-based applications such as a Speech-to-Text converter, Emotion Detection from voice, and a Speech-Controlled Music Player. These tools demonstrate real-time speech analysis capabilities using deep learning models trained on the Google Speech Commands dataset.

📁 Projects Included
Speech-to-Text Converter
Converts 1-second audio clips into corresponding transcribed words using a CNN-based model.

Emotion Detection from Speech
Detects emotional tone (e.g., happy, sad, angry) from spoken audio clips using spectrogram analysis and a trained model.

Speech-Controlled Music Player
Controls music playback with simple voice commands — "up" to play and "down" to pause.

🗃️ Dataset Used
Source: Google Speech Commands Dataset

Content: Contains 1-second .wav files of spoken words like "yes", "no", "up", "down", "go", "stop", etc.

Format: Each file is labeled with its spoken word. MFCC features are extracted for training models.

🛠️ Technologies Used
Language: Python

Libraries:

NumPy, Pandas

Librosa (for audio processing)

TensorFlow/Keras or PyTorch (for model training)

Matplotlib & Seaborn (for visualization)

UI: Developed using Flask (for applicable projects)
⚙️ How to Run
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/bharathiarulNM/speech-recognition-project.git
cd speech-recognition-project
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Application:

bash
Copy
Edit
python app.py
(If applicable – or run the Colab notebooks step by step)

📊 Project Structure
bash
Copy
Edit
speech-recognition-project/
│
├── dataset/                    # Audio dataset (Google Speech Commands)
├── speech_to_text/            # Code for speech-to-text converter
├── emotion_detection/         # Code for emotion detection from voice
├── music_player_control/      # Code for voice-controlled music player
├── saved_models/              # Trained model files (.h5 or .pt)
├── utils/                     # Helper scripts for feature extraction, evaluation, etc.
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation
✅ Features
Real-time speech recognition using pre-trained models

Accurate detection of commands from noisy backgrounds

Simple user interfaces for testing and deployment

🚧 Limitations
Trained on short, clean audio clips — performance may reduce in noisy or long speech

Limited vocabulary (dependent on dataset classes)

🚀 Future Enhancements
Extend vocabulary and multi-language support

Integrate continuous speech recognition (longer audio handling)

Improve emotion detection with multimodal data (voice + facial expressions)

👨‍💻 Contributors
Bharathi A – Project Design & Development
BOOMIKA B


📚 References
Google Speech Commands Dataset

TensorFlow Speech Recognition Tutorial
