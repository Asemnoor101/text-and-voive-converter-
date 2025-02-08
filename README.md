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

### **1️⃣ Clone the Repository**

git clone https://github.com/your-username/your-repo-name.git


##2️⃣ Install Dependencies
pip install openai whisper pyaudio keyboard


##3️⃣ Set Up OpenAI API Key
setx OPENAI_API_KEY "your-api-key-here"    # For Windows


🚀 Usage
1️⃣ Record Your Voice
python audio_recording.py
Press SPACE to start and stop recording.
Saves as audio.wav.


##2️⃣ Convert to Text & Get AI Response
python process_audio.py
Converts audio.wav to text.
Sends text to ChatGPT.
Saves AI response as chatgpt_response.mp3.


##3️⃣ Play the AI Response

click the file ( chatgpt_response.mp3 ) and play 
