# **Vehicle Parking Sensor** 🚗💡  
### *An IoT-based system for automatic vehicle parking detection*

---

## 📌 **Overview**  
Welcome to the **Vehicle Parking Sensor** project! 🚗 This system utilizes ultrasonic sensors to detect vehicle presence in a parking spot and control indicators like LEDs or buzzers. The system can be easily implemented in parking lots to improve parking management and automation.

---

## 🔥 **Features**  
- 🅿️ **Parking Spot Detection**: Automatically detects whether a vehicle is present in a parking space.  
- 🔊 **Buzzer Integration**: Alerts when a vehicle enters or exits a parking spot.  
- 💡 **LED Indicators**: Uses LEDs to signal whether a spot is occupied or available.  
- 🛠️ **Modular Code**: Separated logic into different files for easy understanding and modifications (e.g., `ultrasonic.c`, `lcd.c`, `gpio.c`).  
- 🌐 **Easy Setup**: Ready-to-run code with easy configuration and setup instructions.

---

## 🛠 **Technologies Used**  
- **Hardware:**  
  - Ultrasonic Sensors (HC-SR04 or similar)  
  - LEDs and Buzzers  
  - Microcontroller (e.g., STM32, ESP32, Arduino, etc.)  
  - LCD Display (optional for status display)  
- **Software:**  
  - Embedded C programming  
- **Components:**  
  - GPIO pins for LED control  
  - Buzzer for audio feedback  
  - LCD for displaying parking status (optional)  
  - Ultrasonic for distance sensing  

---

## 🚀 **Getting Started**  
To get the project up and running on your local machine, follow the steps below:

---

### **1. Prerequisites**  
- Required Libraries:  
  - GPIO library for controlling hardware pins (usually available in the microcontroller SDK)  
  - LCD library (if using an LCD display)  
- Hardware Setup:  
  - Connect the ultrasonic sensor to the microcontroller's GPIO pins  
  - Connect LEDs to indicate parking status  
  - Connect a buzzer for audio alerts  
- Microcontroller setup (e.g., STM32, ESP32, or Arduino IDE for compiling and flashing the code)

---

### **2. Installation**  
Clone the repository and set up the development environment:

``bash
git clone https://github.com/Suraj7897/Vehicle_Parking_Sensor.git
cd Vehicle_Parking_Sensor

3. Running the Project
To run the project, simply compile and upload the code for your specific microcontroller. For example, using STM32, you'd typically use STM32CubeIDE to flash the firmware.

Alternatively, if using Arduino, ensure you have the Arduino IDE installed and the correct board selected.

bash
Copy
Edit
# Example for STM32
make
make flash

# Example for Arduino
# Upload directly through Arduino IDE
4. Hardware Connections
Ultrasonic Sensor:
Trig Pin to GPIO Pin X
Echo Pin to GPIO Pin Y
LEDs:
Connect to GPIO pins for visual status (green for available, red for occupied).
Buzzer:
Connect to GPIO for audio feedback on parking status.

6. Code Structure
This project is divided into modular code files for easier management:

buzzer.c / buzzer.h - Controls the buzzer for vehicle entry/exit alerts.
gpio.c / gpio.h - Manages the GPIO pins for LEDs, buzzer, and ultrasonic sensor.
ultrasonic.c / ultrasonic.h - Contains logic for triggering and receiving signals from the ultrasonic sensor.
lcd.c / lcd.h - Optional module to display the parking status on an LCD.
car_parking_sensor.c - Main logic for parking detection.

6. Example Usage
Once set up, the system will detect the vehicle's presence and turn on/off the LED indicators and the buzzer accordingly. It can also display the parking status on the LCD if connected.

📸 Screenshots / Demo
Here are some demo images of the setup and working system:


System connected to the ultrasonic sensor and the microcontroller.

![circuit-diagram-22](https://github.com/user-attachments/assets/40ed9e39-17d6-45dd-a86a-2b16342f07f7)



LEDs and buzzer activated when a vehicle is detected.

![WhatsApp-Image-2024-01-22-at-212229_1117487f-(2)](https://github.com/user-attachments/assets/89afb955-6ba6-4f5d-bb82-04cc2d7dd83f)



🧑‍💻 Contributing
Feel free to fork the repository, submit issues, or create pull requests to enhance the project. Contributions are welcome! 😊

🔗 Links
GitHub Repository: Vehicle Parking Sensor


🎉 Thank you for checking out the Vehicle Parking Sensor project! Let's automate parking management with ease! 🚗💡
