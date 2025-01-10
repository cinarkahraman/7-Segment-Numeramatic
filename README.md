# 7-Segment Display Using Servo Motors

Project Video Link : https://youtu.be/xPlOSnwSvJo

📟📟📟 This project demonstrates a unique way to create a 7-segment display using servo motors. Each segment of the display is controlled by a servo motor, which moves between two positions to represent an "on" or "off" state. This project is implemented using Arduino. 📟📟📟

## Features
📌📌📌
- Displays numbers from 0 to 9 using servo motors.
- Automatically counts down from 99 to 00.
- Uses two Arduino boards: one for controlling the units digit and another for the tens digit. 📌📌📌

## Components Required
📋📋📋
- 7 x Servo motors
- 2 x Arduino boards
- Power supply for the servos
- Jumper wires
- Breadboard (optional) 📋📋📋

## How It Works
🎛️🎛️🎛️
1. **Servo Control:** Each servo motor corresponds to a segment of the 7-segment display. The servos move to specific positions to turn a segment "on" or "off." 🎛️🎛️🎛️
2. **Digit Mapping:** The `digits` array maps each number (0-9) to the corresponding segments that should be active.
3. **Countdown Logic:** The `loop` function counts down from 99 to 00. The units digit is displayed using the current Arduino, and the tens digit is sent to a second Arduino.
4. **Communication:** The `displayTensDigit` function is designed to communicate the tens digit to the second Arduino for synchronized display.

## Installation and Usage
🛠️🛠️🛠️
1. **Connect Components:**
   - Attach the servo motors to the Arduino pins as specified in the code.
   - Ensure a stable power supply for the servos.
2. **Upload Code:**
   - Upload the code to both Arduino boards. Customize the `displayTensDigit` function for communication between the boards.
3. **Run the System:**
   - Power on the system and observe the countdown. 🛠️🛠️🛠️

## Future Improvements
🚀🚀🚀
- Implement the `displayTensDigit` function to enable proper synchronization between the two Arduinos.
- Add a feature to reset the countdown.
- Optimize servo movements for smoother transitions. 🚀🚀🚀

## Notes
📖📖📖
- Ensure the servo motors have sufficient power to operate simultaneously.
- Use appropriate delay values to avoid servo jittering or misalignment. 📖📖📖


