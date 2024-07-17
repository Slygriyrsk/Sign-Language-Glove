# Sign-Language-Glove

Welcome to the **Sign-Language-Glove** project! This innovative hardware-based solution translates American Sign Language (ASL) gestures into text or speech in real-time. Leveraging the power of Arduino Uno, flex sensors, and ADXL335 accelerometers, the Sign-Language Glove aims to bridge the communication gap between the deaf and hearing communities.

![s](https://github.com/user-attachments/assets/3cee495f-9c25-47a6-8770-c1ebc3229be3)

# Features

- **Real-Time Translation**: Converts ASL gestures into text and speech instantly.
- **Wireless Connectivity**: Uses Bluetooth for seamless connection to mobile devices and computers.
- **User-Friendly Interface**: Mobile app and desktop software for easy interaction and customization.
- **Extensive Vocabulary**: Supports a wide range of ASL gestures with the ability to add custom signs.
- **Data Logging**: Records gesture data for analysis and improvement.

# Technology Stack

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

# Installation

### Hardware Setup

- Attach the flex sensors to each finger of the glove.
- Connect the ADXL335 accelerometer to the Arduino Uno.
- Pair the Arduino Uno with a Bluetooth module.
- Upload the firmware to the Arduino Uno using the [Arduino IDE](https://www.arduino.cc/en/software).

### Software Setup

- Clone this repository
   ```bash
   git clone https://github.com/Slygriyrsk/sign-language-glove.git

- Navigate to the project directory
   ```bash 
   cd sign-language-glove

- Install the required dependencies
   ```bash
   pip install -r requirements.txt

- Run the gesture recognition script
```bash
   python gesture_recognition.py
```

# Bluetooth App Designing
The mobile application provides an interface for users to interact with the device, including features for converting sign language to audio or video signs.


### Connect Bluetooth
Establish a connection between your phone and the glove by selecting the appropriate Bluetooth address.

![m](https://github.com/user-attachments/assets/2eb8092c-3a0e-44f4-ba9e-afdd9b2b8e52)

### Bluetooth App Block Diagram
This is done using MIT app inventor: https://appinventor.mit.edu/
![b](https://github.com/user-attachments/assets/b1faa25d-b293-4a66-b271-03e43e66737d)



# Readings
Here are some basic readings from our records

![Screenshot 2024-07-17 174728](https://github.com/user-attachments/assets/e4655d2e-830f-4cb1-a8b8-d4e3ac8d83b2)



# Usage
- Wear the glove and ensure all sensors are securely attached.
- Turn on the Arduino Uno and pair it with your mobile device or computer via Bluetooth.
- Open the mobile or desktop app.
- Perform ASL gestures; the corresponding text and speech output will be displayed and played in real-time.

# Contribution
Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

- `Report Bugs` Use the Issues section to report any bugs or feature requests.
- `Fix Issues` Fork the repository, make your changes, and submit a pull request.
- `Improve Documentation` Help us improve the project's documentation by adding tutorials, examples, and clarifications.
## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saharsh-kumar-9768a8264/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/repatriation_23?s=09)


## Authors

- [@Slygriyrsk](https://github.com/Slygriyrsk)
- [@maheshkatyayan](https://github.com/maheshkatyayan)

## Acknowledgements

This project would not have been possible without the dedicated efforts and contributions of our amazing team members:

- **Saharsh Kumar** Team Leader and developed the Bluetooth communication application, ensuring seamless connectivity between the glove and mobile devices.
- **Hitesh Kumar** Focused on the hardware integration and wrote the core code for the Arduino Uno, flex sensors, and ADXL335 accelerometers.
- **Mahesh K Katyayan** Worked on the signal processing and machine learning aspects, laying the groundwork for future innovations in gesture recognition.
Thank you for your hard work and commitment to making this project a success!

