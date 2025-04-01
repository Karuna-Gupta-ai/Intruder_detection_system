Intruder Detection System 🚨
📌 Project Overview
This project is an Intruder Detection System simulated in Proteus, using an Arduino Uno and a PIR (Passive Infrared) sensor. The system detects motion and triggers an alert when an unauthorized movement is detected.

🔧 Features
✅ Motion detection using PIR sensor
✅ Simulated in Proteus 8.6 (requires proteus 8.6 and later versions)
✅ Sound alerts on intrusion
✅ Arduino-based implementation

🛠️ Components Used
Arduino Uno 🟦

PIR Sensor  👀

Buzzer (for alerts) 🔊

LED (for indication) 💡

LCD (for msg display)

Proteus 8.6 (for simulation)

⚙️ Circuit Diagram (Proteus)
![Screenshot (43)](https://github.com/user-attachments/assets/0787342c-d471-4506-be1b-fbe5fb2c3aa0)


💾 Installation & Setup
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/Karuna-Gupta-ai/Intruder_detection_system.git
cd Intruder_detection_system
2️⃣ Open the Arduino Code
Open Intruder_detection_system.ino in the Arduino IDE.

Select Board: Arduino Uno and Port.


3️⃣ Run the Simulation in Proteus
Open Proteus and load the provided Proteus project file (.pdsprj).

Run the simulation and observe the behavior when motion is detected.

📜 Code Explanation
The PIR sensor detects movement and sends a signal to the Arduino Uno.

If motion is detected, the buzzer sounds and the LED turns on.

The system logs intrusion events on LCD.

📷 Demo Screenshot
![Screenshot (44)](https://github.com/user-attachments/assets/dcb720e7-63ad-4ced-a38f-dfde904a1530)


💡 Future Improvements
🔹 Integrate an ESP32-cam for intruder recognition
🔹 Implement GSM Module for SMS alerts
🔹 Integrate an GPS module for real time tracking of intruder for border security applications. 

🤝 Contributing
Feel free to fork this repo and contribute to enhance the system!


