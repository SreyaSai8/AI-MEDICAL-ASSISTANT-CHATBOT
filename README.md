# AI-MEDICAL-ASSISTANT-CHATBOT
This is a Flask-based AI-powered medical assistant chatbot that provides preliminary health advice based on user input. The chatbot collects user vitals, including temperature and heart rate, and symptoms to generate AI-driven medical suggestions. It also integrates with IoT devices to fetch real-time data.


**Features**
✅ AI-Powered Symptom Analysis – Provides health advice based on symptoms, temperature, and heart rate.
✅ IoT Integration – Fetches real-time vitals from connected IoT devices.
✅ Voice Assistant (TTS) – Uses pyttsx3 to convert text-based responses into speech.
✅ Flask API – A simple API to handle user input and provide JSON responses.
✅ Scalable Symptom Detection – Supports 50+ symptoms, including fever, cough, chest pain, dizziness, and more.

**How It Works**
1️⃣ User enters temperature, heart rate, and symptoms.
2️⃣ The chatbot processes the input and analyzes symptoms using predefined medical knowledge.
3️⃣ It provides personalized health advice.
4️⃣ If an IoT device is connected, it retrieves real-time health data.
5️⃣ The chatbot speaks the response using Text-to-Speech (TTS) for an enhanced user experience.

**Technologies Used**
🔹 Flask – Backend API
🔹 Python – Core logic
🔹 pyttsx3 – Text-to-Speech engine
🔹 Serial Communication (pySerial) – Fetching IoT device data
🔹 HTML, JavaScript – Frontend (index.html)
