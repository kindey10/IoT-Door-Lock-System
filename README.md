# IoT-Based Smart Door Lock System  

### Overview  
This project implements a smart and secure **IoT-enabled door lock system** using **ESP32, RFID, and WebSockets**, offering **real-time access control, monitoring, and automated authentication**. Designed for **enhanced security and seamless user experience**, the system ensures robust authentication through **RFID tags**, while enabling remote access and alerts via **WebSockets**.  

### Features  
- **Secure RFID-Based Access Control** – Each authorized user is assigned an RFID tag, ensuring only registered users can unlock the door.  
- **Real-time Monitoring with WebSockets** – Enables instant updates on access logs and lock status, reducing security risks.  
- **IoT-Enabled Remote Authentication** – Allows administrators to manage access rights and receive notifications remotely.  
- **ESPAsyncWebServer for Efficient Communication** – Hosts a lightweight web interface on ESP32 for easy configuration and real-time control.  
- **Failsafe Mechanism** – Ensures fallback authentication in case of connectivity issues.  

### Technologies Used  
- **ESP32** – Microcontroller for IoT operations and connectivity.  
- **RFID** – Secure tag-based user authentication system.  
- **WebSockets** – Enables real-time communication between the server and client.  
- **ESPAsyncWebServer** – Efficient web server implementation for ESP32-based applications.  
- **Python** – Optional backend functionality for data logging and user management.  

### Installation & Usage  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/Smart-Door-Lock.git  
   cd Smart-Door-Lock  
   ```  
2. Flash the ESP32 firmware using **Arduino IDE** or **PlatformIO**.  
3. Upload RFID authentication data to the ESP32.  
4. Access the web dashboard for real-time lock status monitoring.  

### Future Enhancements  
- Integrate biometric authentication for multi-factor security.  
- Implement **AI-driven access control** using facial recognition.  
- Expand logging features for better security auditing.  
