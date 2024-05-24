# Sign-Language-Glove
This project features a hardware-based sign-language glove translating gestures into text or speech. Flex sensors on the fingers detect bending and send signals to a microcontroller, which interprets the gestures.The Sign-Language Glove is an innovative device designed to translate American Sign Language (ASL) into text and speech in real-time. This project aims to bridge the communication gap between the deaf and hearing communities, leveraging the power of Arduino Uno, flex sensors, and ADXL335 accelerometers.

# Features
1. Real-Time Translation: Converts ASL gestures into text and speech instantly.
2. Wireless Connectivity: Uses Bluetooth for seamless connection to mobile devices and computers.
3. User-Friendly Interface: Mobile app and desktop software for easy interaction and customization.
4. Extensive Vocabulary: Supports a wide range of ASL gestures with the ability to add custom signs.
5. Data Logging: Records gesture data for analysis and improvement.
   
# Technology Stack
1. Hardware:
    1. Arduino Uno: Central microcontroller for data processing.
    2. Flex Sensors: Detect finger movements.
    3. ADXL335 Accelerometer: Tracks hand orientation and motion.
    4. Bluetooth Module: For wireless communication with mobile devices and computers.
2. Software:
    1. Programming Languages: C/C++ for Arduino, Python for data processing.
    2. Machine Learning: TensorFlow or PyTorch for gesture recognition.
    3. Mobile App: React Native for cross-platform compatibility.
    4. Desktop App: Electron.js for a unified experience across OS.
       
# Installation
1. Hardware Setup
    a. Attach the flex sensors to each finger of the glove.
    b. Connect the ADXL335 accelerometer to the Arduino Uno.
    c. Pair the Arduino Uno with a Bluetooth module.
    d. Upload the firmware to the Arduino Uno using the Arduino IDE.

# Software Setup
1. Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/sign-language-glove.git
2. Navigate to the project directory:
bash
Copy code
cd sign-language-glove
3. Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
4. Run the gesture recognition script:
bash
Copy code
python gesture_recognition.py

# Usage
1. Wear the glove and ensure all sensors are securely attached.
2. Turn on the Arduino Uno and pair it with your mobile device or computer via Bluetooth.
3. Open the mobile or desktop app.
4. Perform ASL gestures; the corresponding text and speech output will be displayed and played in real-time.
   
# Contribution
We welcome contributions from the community! Here’s how you can help:

1. Report Bugs: Use the Issues section to report any bugs or feature requests.
2. Fix Issues: Fork the repository, make your changes, and submit a pull request.
3. Improve Documentation: Help us improve the project's documentation by adding tutorials, examples, and clarifications.


Certainly! Here's the revised Acknowledgments section highlighting the three team members and their specific contributions:

# Acknowledgments
This project would not have been possible without the dedicated efforts and contributions of our amazing team members:

Saharsh Kumar: Developed the Bluetooth communication application, ensuring seamless connectivity between the glove and mobile devices.
Hitesh Kumar: Focused on the hardware integration and wrote the core code for the Arduino Uno, flex sensors, and ADXL335 accelerometers.
Mahesh K Katyayan: Worked on the signal processing and machine learning aspects, laying the groundwork for future innovations in gesture recognition.
Thank you for your hard work and commitment to making this project a success!

