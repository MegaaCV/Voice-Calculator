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

# **🎯 Example Usage**

Voice: “square root of 16” → Result: 4.0

Voice: “sine of 30” → Result: 0.5

Voice: “cosine of 60” → Result: 0.5

Text: “5 plus 7 multiplied by 2” → Result: 19.0

# **🚀 Future Enhancements**

🔹 Unit Conversions → “convert 5 kilometers to miles”, “convert 32 °C to °F”
🔹 Complex Expressions with Parentheses → “open bracket 5 plus 3 close bracket multiplied by 2” → 16
🔹 Cross-Platform Deployment → Mobile app (Kivy/Flutter) or Web app (Flask/Django + React)

# **📌 Applications**

Assistive tech for visually impaired users

Hands-free math learning assistant

Integration into smart devices (Alexa, Google Assistant)

Educational tools & interactive learning apps

👉 This project demonstrates how voice recognition, natural language processing, symbolic math, and GUI design can be combined to create an intelligent and accessible calculator.
