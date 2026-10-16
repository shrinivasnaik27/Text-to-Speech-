# 🔊 Text-to-Speech Converter

## 📌 About the Project

The **Text-to-Speech Converter** is a Python-based web application that converts written text into spoken audio. It uses **Streamlit** to provide a simple and interactive user interface and **Google Text-to-Speech (gTTS)** to generate speech.

Users can enter text, select a language, adjust the speaking speed, listen to the generated audio, and download it as an MP3 file.

## ✨ Features

- 📝 Convert written text into speech.
- 🌍 Supports multiple languages.
- 🐢 Option to generate slower speech.
- 🔊 Play generated audio directly in the application.
- 💾 Download speech as an MP3 file.
- ⚡ Simple and user-friendly interface.
- ⚠️ Input validation and error handling.

## 🛠️ Technologies Used

- **Python** – Main programming language.
- **Streamlit** – Web application interface.
- **gTTS** – Text-to-speech conversion.
- **BytesIO** – Handles audio data in memory.

## 🌐 Supported Languages

The application currently supports:

- English
- Spanish
- French
- German
- Italian
- Japanese
- Korean
- Russian
- Arabic

## 📂 Project Structure

```text
Text-to-Speech-Converter/
│
├── app.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your repository's URL.

### 2. Open the Project Folder

```bash
cd Text-to-Speech-Converter
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

If you have not created `requirements.txt`, run:

```bash
pip install streamlit gTTS
```

### 4. Run the Application

```bash
streamlit run app.py
```

The application will open in your browser, usually at `http://localhost:8501`.

## 🚀 How to Use

1. Open the Text-to-Speech Converter application.
2. Enter the text you want to convert.
3. Select your preferred language.
4. Enable the slow-speech option if required.
5. Click **Convert to Speech**.
6. Listen to the generated audio.
7. Click **Download MP3** to save the audio file.

## 🎯 Applications

- Language learning and pronunciation practice.
- Listening to written notes and study materials.
- Accessibility support for people who prefer audio.
- Creating spoken versions of text content.
- Basic speech-generation experiments.

## ⚠️ Requirements

- Python installed on your system.
- An internet connection for gTTS to generate speech.
- Required Python libraries installed.

## 🔮 Future Improvements

- Add more supported languages.
- Provide additional voice and speed settings.
- Support larger text inputs and audio formats.
- Add text-file upload functionality.
- Deploy the application online for public access.

## 👨‍💻 Author

Created as a Python project to explore text-to-speech technology and interactive web application development.

## 📄 License

This project can be shared and modified for learning and educational purposes. Add a formal open-source license if you want to specify permissions for reuse and distribution.
