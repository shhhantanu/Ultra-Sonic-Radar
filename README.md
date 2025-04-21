# Ultra-Sonic-Radar
🛠️ Ultra Sonic Radar using Arduino and Processing

This project is a radar simulation system built using an Arduino Uno, an ultrasonic sensor (HC-SR04), and the Processing IDE to visualize detected objects in a radar-style display. It demonstrates how to combine hardware and software to detect and visualize object distance and position in a semi-circular radar view.

📡 Features

    Real-time radar scanning using a servo-mounted HC-SR04 sensor

    Visual radar interface built with Processing

    Distance data acquisition via Arduino

    Scanning angle range: 0° to 180°

    Object detection and live plotting on radar screen

    Simple and effective representation of nearby obstacles

🧰 Tools & Technologies

    Arduino UNO

    HC-SR04 Ultrasonic Sensor

    Servo Motor (SG90)

    Processing IDE (Java-based)

    Arduino IDE

🔌 How It Works

    Arduino rotates the ultrasonic sensor using the servo motor from 0° to 180°.

    At each angle, it sends out an ultrasonic pulse and measures the time taken for the echo to return.

    The measured distance and angle are sent to the Processing application via serial communication.

    Processing receives this data and visually plots the obstacle on a radar-like GUI.
    
🚀 Getting Started

    Upload the Arduino code to your UNO board.

    Connect the components as per the circuit diagram (included in repo).

    Open the Processing sketch and run it.

    Make sure the correct COM port is selected in both Arduino and Processing sketches.

🖇️ Circuit Components

    Arduino UNO

    HC-SR04 Ultrasonic Sensor

    SG90 Servo Motor

    Jumper Wires

    Breadboard

    USB Cable

💡 Applications

    Obstacle detection

    Autonomous robots

    Security and motion tracking

    Educational visualization tools
