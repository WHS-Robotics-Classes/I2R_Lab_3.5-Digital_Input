# Arduino 3.5-Digital Input
## In this assignment you will learn to use digital sensors as input devices.  

---

### Step One: Build the Circuit

Build your circuit according to this schematic:

![pulldown circuit](https://github.com/WHS-Robotics-Classes/3.5-Digital_Input/blob/main/pulldown.PNG?raw=true)

### Step Two: Write the Code

Before you start, review the Arduino Reference page on [`digitalRead()`](https://www.arduino.cc/reference/en/language/functions/digital-io/digitalread/).  You should also review [`Serial.println()`](https://www.arduino.cc/reference/en/language/functions/communication/serial/println/) as you will need to know how to print something as a binary number.

1. Copy any starter code provided for you (Starter.ino file) into the [Codebender IDE](https://edu.codebender.cc/class/1ajtp).
2. Modify the code so your sketch does the following:
    - Print the value received by the input pin to the Serial monitor using `Serial.ptintln()` as a binary number (0 or 1).
    - Delay 100 ms between each cycle.
    - Keep running forever.

Use the video below as a reference.

### Step Three: Debug and Submit

[![3.5_Video](http://img.youtube.com/vi/Nc7hQMbBjHo/0.jpg)](https://www.youtube.com/watch?v=Nc7hQMbBjHo "3.5-Digital Input Video")

Make sure your prototype behaves the same way as the one in the video. As in the previous assignment, make a new file here on GitHub. Name it 3.5_Digital_Input.ino and Commit it to the repository.
