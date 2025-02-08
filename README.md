📌 README.md (Simple Version)
markdown

# 🎤 Voice Assistant: Speech-to-Text & AI Response 🎧

This project records **voice input**, converts it to **text**, sends it to **ChatGPT**, and plays the AI-generated **audio response**.

## **🔹 Features**
✅ Record voice input 🎙️  
✅ Convert speech to text using Whisper  
✅ Send text to ChatGPT API  
✅ Get AI response and convert it to speech 🗣️  
✅ Play the AI-generated response 🔊  

---

## **🛠️ Installation**

### **1️⃣ download some important library**
download the whisper library from 

pip install git+https://github.com/openai/whisper.git 

install the ffmpeg using https://github.com/GyanD/codexffmpeg/releases/tag/2025-02-06-git-6da82b4485



### **2️⃣ Install Dependencies**
pip install openai whisper pyaudio keyboard


## **3️⃣ Set Up OpenAI API Key**
setx OPENAI_API_KEY "your-api-key-here"    # For Windows


##**🚀 Usage**
## **1️⃣ Record Your Voice**
python audio_recording.py


Press SPACE to start and stop recording.


Saves as audio.wav.





https://github.com/user-attachments/assets/2030f868-5db3-4b69-8069-8b2ca15e3fac





## **2️⃣ Convert to Text & Get AI Response**
python process_audio.py


Converts audio.wav to text.


Sends text to ChatGPT.


Saves AI response as chatgpt_response.mp3.
![لقطة شاشة 2025-02-09 004611](https://github.com/user-attachments/assets/a9430acf-a5cf-4ea1-98e4-3fc576bdff82)


## **3️⃣ Play the AI Response**

click the file ( chatgpt_response.mp3 ) and play 


https://github.com/user-attachments/assets/36bbc6ca-5453-477a-b9a2-318ef11f1d27



