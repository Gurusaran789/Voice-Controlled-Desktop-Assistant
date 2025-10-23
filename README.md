💬 Voice-Controlled Desktop Assistant (Jarvis-Lite in Java)
A simple yet powerful desktop voice assistant built using Java. This project recognizes your voice commands and performs tasks such as opening applications, searching the web, and responding via speech synthesis.

🚀 Features
🎙️ Voice Command Recognition using CMU Sphinx
🗣️ Text-to-Speech with FreeTTS
🖥️ Launches desktop applications like Chrome, Notepad, etc.
🌐 Performs Google searches from voice input
🛠️ Modular and extensible codebase for adding new commands
🛠️ Tech Stack
Java (JDK 8+ or OpenJDK)
CMU Sphinx (Speech Recognition)
FreeTTS (Text-to-Speech)
IntelliJ IDEA / Eclipse
Windows OS (for native app control)
📁 Project Structure
📦 Voice_Assistant_Using_Java ┣ 📂 lib # JAR files (Sphinx4, FreeTTS, etc.) ┣ 📂 src # Source code files ┃ ┗ 📜 VoiceAssistant.java ┣ 📜 README.md # This file ┣ 📜 requirements.txt # Optional, for listing dependencies

⚙️ Setup Instructions
Clone the Repository bash git clone https://github.com/your-username/voice-assistant-java.git cd voice-assistant-java

Add Required JARs

Download and include the following libraries in your project’s lib/ folder:
sphinx4-core.jar
freetts.jar
Any other dependencies from CMU Sphinx or FreeTTS
Compile & Run

Use IntelliJ or any Java IDE.
Set up the project SDK to Java 8+.
Build and run VoiceAssistant.java.
🗣️ Voice Activation
By default, the trigger word is:

"Gurusaran" Example: “Gurusaran open Chrome” “Gurusaran search for today’s news”

📦 Future Enhancements
Add AI-based chatbot integration (e.g., GPT API)
Integrate with APIs like weather, news, etc.
Add GUI using JavaFX or Swing
🙋‍♂️ Author
Gurusaran Passionate Java Developer | Tech Enthusiast 🔗 LinkedIn

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
