# **🎤 Smart Voice + Text Calculator**
# **📌 Overview**

This project is a hybrid calculator that supports both voice and text input for solving mathematical expressions.
It evaluates basic arithmetic and advanced operations, displays results in a modern GUI, and also provides voice output.

The notebook includes:

Basic Model → Demonstrates fundamental speech-to-math functionality.

Customized Model → Adds natural language preprocessing, advanced math support, GUI integration, and voice response.

# **⚙️ Features**

🎙️ Voice Input: Speak your math query (e.g., “sine of 30”).

⌨️ Text Input: Enter expressions directly in the GUI.

🔊 Voice Output: Results are read aloud using TTS.

🧠 Smart Preprocessing: Corrects speech recognition errors (e.g., “sign of 30” → “sine of 30”).

📐 Advanced Math Support: Trigonometry, powers, square roots, logarithms, etc.

🖥️ Modern GUI with real-time results and calculation history.

⚡ Threaded Voice Mode: Keeps the interface responsive while listening.

# **🛠️ Tech Stack**

Python 3.12+

SpeechRecognition
 → Speech-to-text

pyttsx3
 → Text-to-speech

SymPy
 → Mathematical evaluation

CustomTkinter
 → GUI framework

Threading → Background voice recognition

# **📂 Project Structure**

voice-calculator/
│── main.py              # Final GUI + voice calculator
│── basic_model.py       # Basic voice model
│── custom_model.py      # Customized advanced model
│── requirements.txt     # Dependencies
│── README.md            # Documentation
│── demo/                # Screenshots / GIFs

# **💻 Installation & Usage**
1. Clone the repo
git clone https://github.com/MegaaCV/Voice-Calculator.git

cd Voice-Calculator
3. Install dependencies

pip install -r requirements.txt

#**🎯 Example Usage**

Voice: “square root of 16” → Result: 4.0

Voice: “sine of 30” → Result: 0.5

Voice: “cosine of 60” → Result: 0.5

Text: “5 plus 7 multiplied by 2” → Result: 19.0
# **📸 Demo**

# **🚀 Future Enhancements**

🔹 Unit Conversions
🔹 Deployment as Mobile or Web App:
                Transform into a cross-platform mobile app (Flutter/Kivy) or
                Deploy as a web-based calculator app for wider accessibility.

# **📌 Applications**

Assistive tech for visually impaired users

Hands-free math learning assistant

Integration into smart devices (Alexa, Google Assistant)

Educational tools & interactive learning apps

👉 This project demonstrates how voice recognition, natural language processing, symbolic math, and GUI design can be combined to create an intelligent and accessible calculator.
