### 2025 Capstone Design 2, Dongguk University
# 🦮 WayVi
> WayVI is a smartwatch application that provides real-time navigation for the visually impaired, utilizing the wearability and health sensors of smartwatches.

<br>

## 🚀 Features
- Voice-based real-time navigation using Tmap API
- AI-powered health monitoring (heart rate, fatigue, fall detection)
- Automatic SOS alerts in emergencies
- Daily health summary with personalized voice feedback
- Fully voice-controlled interface (no screen interaction)
- Smartwatch with GPS, motion, and heart rate sensors
- Wi-Fi/Bluetooth for data sync and emergency communication
<br>

## 💻 Tech Stack

| Category   | Technologies |
|------------|--------------|
| Frontend | Swift (Apple Watch), HealthKit, CoreMotion, Tmap API, TTS/STT, Haptic Engine |
| Backend  | FastAPI (Python), AWS EC2, MySQL RDS, REST API, Nginx, Gunicorn |
| AI       | TensorFlow, Scikit-learn, LSTM Autoencoder, CNN, Random Forest, KMeans |
<br>

## 👩‍💻 Developers

| ![@VegetableKim](https://github.com/VegetableKim.png?size=140) | ![@sunhanmoo](https://github.com/sunhanmoo.png?size=140) | ![@forever0801](https://github.com/forever0801.png?size=140) | ![@munjji](https://github.com/munjji.png?size=140) |
|:---:|:---:|:---:|:---:|
| [Chaerin Kim](https://github.com/VegetableKim) | [Hoeun Seong](https://github.com/sunhanmoo) | [Sujin Lee](https://github.com/forever0801) | [Jihee Lee](https://github.com/munjji) |
| Server | Client | AI | Server |
<br>

## ▶️ How to Run

### ✅ Prerequisites
- Xcode 16.0 or higher (for building the Apple Watch app)
- Java 17 or higher (for Spring Boot server)
- MySQL 8.0 or higher
- Python 3.8 or higher (for AI server)
### 📦 Build
### 1. Git Clone
```bash
git clone https://github.com/2025-WAYVI/SERVER_WAYVI.git
git clone https://github.com/2025-WAYVI/CLIENT_WAYVI.git
```
### 2. Run the Spring Boot server
<b>Run in development mode</b>
```bash
cd spring-server
./gradlew bootRun
```
<b>Build and run in production</b>
```bash
cd spring-server
./gradlew build
java -jar build/libs/Azaping-0.0.1-SNAPSHOT.jar
```
<b>Run on Windows</b>
```bash
cd spring-server
gradlew.bat bootRun
```
### 3. Run the AI server
```bash
cd ai-server
pip install -r requirements.txt  # only if not installed
python app.py
```
### 4. Run the Apple Watch app
```bash
cd CLIENT_WAYVI
open CLIENT_WAYVI.xcworkspace
```
<br>

## 📌 Overview
<img src="https://github.com/user-attachments/assets/c58061d7-5aaf-4141-9ad6-3154a318541f" width="80%" />  
<img src="https://github.com/user-attachments/assets/3e1733cc-ac16-4289-9d29-cdbb3fe1ccaf" width="80%" />  
<img src="https://github.com/user-attachments/assets/8ffdb4b3-b2b8-4848-b977-c4510ffa317e" width="80%" />  
<img src="https://github.com/user-attachments/assets/9021634b-6fc6-4863-aca0-e61f8c515661" width="80%" />  
<img src="https://github.com/user-attachments/assets/96724e38-ccc5-4c95-97e2-0cb5d86b0958" width="80%" />  
<img src="https://github.com/user-attachments/assets/7033c32b-4007-4a44-9776-d468b8ed66c7" width="80%" />

