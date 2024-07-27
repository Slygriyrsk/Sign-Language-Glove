# 🧤 Sign-Language-Glove

![GitHub Repo size](https://img.shields.io/github/repo-size/Slygriyrsk/Sign-Language-Glove?style=flat-square)
![GitHub contributors](https://img.shields.io/github/contributors/Slygriyrsk/Sign-Language-Glove?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/Slygriyrsk/Sign-Language-Glove?style=flat-square)
![GitHub license](https://img.shields.io/github/license/Slygriyrsk/Sign-Language-Glove?style=flat-square)

Welcome to the **Sign-Language-Glove** project! This innovative hardware-based solution translates American Sign Language (ASL) gestures into text or speech in real-time. Leveraging the power of Arduino Uno, flex sensors, and ADXL335 accelerometers, the Sign-Language Glove aims to bridge the communication gap between the deaf and hearing communities.

![gestureglove](https://github.com/user-attachments/assets/aad52852-352c-4432-8057-ab8d292839c6)

---

## 🚀 Features

- **Real-Time Translation**: Converts ASL gestures into text and speech instantly.
- **Wireless Connectivity**: Uses Bluetooth for seamless connection to mobile devices and computers.
- **User-Friendly Interface**: Mobile app and desktop software for easy interaction and customization.
- **Extensive Vocabulary**: Supports a wide range of ASL gestures with the ability to add custom signs.
- **Data Logging**: Records gesture data for analysis and improvement.

---

## 🛠️ Technology Stack

### Hardware
- **Arduino Uno**: Central microcontroller for data processing.
- **Flex Sensors**: Detect finger movements.
- **ADXL335 Accelerometer**: Tracks hand orientation and motion.
- **Bluetooth Module**: For wireless communication with mobile devices and computers.

### Software
- **Programming Languages**: C/C++ for Arduino, Python for data processing.
- **Machine Learning**: [TensorFlow](https://www.tensorflow.org/) or [PyTorch](https://pytorch.org/) for gesture recognition.
- **Mobile App**: [React Native](https://reactnative.dev/) for cross-platform compatibility.
- **Desktop App**: [Electron.js](https://www.electronjs.org/) for a unified experience across OS.

---

## 📦 Installation

### Hardware Setup
1. Attach the flex sensors to each finger of the glove.
2. Connect the ADXL335 accelerometer to the Arduino Uno.
3. Pair the Arduino Uno with a Bluetooth module.
4. Upload the firmware to the Arduino Uno using the [Arduino IDE](https://www.arduino.cc/en/software).

### Software Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Slygriyrsk/Sign-Language-Glove.git
   ```

1.  Navigate to the project directory:

    ```bash
    cd Sign-Language-Glove
    ```

2.  Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3.  Run the gesture recognition script:

    ```bash
    python gesture_recognition.py
    ```

* * * * *

📱 Bluetooth App Designing
--------------------------

The mobile application provides an interface for users to interact with the device, including features for converting sign language to audio or video signs.

### 🔗 Connect Bluetooth

Establish a connection between your phone and the glove by selecting the appropriate Bluetooth address.

![mobile](https://github.com/user-attachments/assets/17b43e69-c33d-4b4a-85f9-a640d57caa30)

### 📊 Bluetooth App Block Diagram

This is done using MIT App Inventor: MIT App Inventor

![bluetooth](https://github.com/user-attachments/assets/bae4c1b2-450a-4d8c-aa46-9c9389600a9a)

* * * * *

📈 Readings
-----------

Here are some basic readings from our records:

![readings](https://github.com/user-attachments/assets/6b8b11a3-10ac-415b-a9f2-94dd8b31a569)

* * * * *

🎉 Usage
--------

1.  Wear the glove and ensure all sensors are securely attached.
2.  Turn on the Arduino Uno and pair it with your mobile device or computer via Bluetooth.
3.  Open the mobile or desktop app.
4.  Perform ASL gestures; the corresponding text and speech output will be displayed and played in real-time.

* * * * *

🤝 Contribution
---------------

Contributions are always welcome! Please see `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

-   **Report Bugs**: Use the Issues section to report any bugs or feature requests.
-   **Fix Issues**: Fork the repository, make your changes, and submit a pull request.
-   **Improve Documentation**: Help us improve the project's documentation by adding tutorials, examples, and clarifications.

🔗 Links
--------

* * * * *

👨‍💻 Authors
-------------

-   @Slygriyrsk
-   @maheshkatyayan

* * * * *

🙌 Acknowledgements
-------------------

This project would not have been possible without the dedicated efforts and contributions of our amazing team members:

-   **Saharsh Kumar**: Team Leader, developed the Bluetooth communication application, ensuring seamless connectivity between the glove and mobile devices. ![Team Leader](https://img.shields.io/badge/Role-Team%20Leader-blue?style=flat-square)
-   **Hitesh Kumar**: Focused on hardware integration and wrote the core code for the Arduino Uno, flex sensors, and ADXL335 accelerometers. ![Hardware Engineer](https://img.shields.io/badge/Role-Hardware%20Engineer-orange?style=flat-square)
-   **Mahesh K Katyayan**: Worked on the signal processing and machine learning aspects, laying the groundwork for future innovations in gesture recognition. ![Machine Learning Engineer](https://img.shields.io/badge/Role-Machine%20Learning%20Engineer-green?style=flat-square)

Thank you for your hard work and commitment to making this project a success! 🎉 ![Thank You](https://img.shields.io/badge/Thank%20You!-orange?style=flat-square)

![Project Completed](https://img.shields.io/badge/Project-Completed-brightgreen?style=flat-square) 
![Contributors](https://img.shields.io/badge/Contributors-3-yellow?style=flat-square) 
![Last Commit](https://img.shields.io/github/last-commit/Slygriyrsk/Sign-Language-Glove?style=flat-square) 

