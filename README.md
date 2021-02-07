# Arduino 3.5-Digital Input
## In this assignment you will learn to use digital sensors as input devices.  

---

### Step One: Build the Circuit

Build your circuit according to this schematic:

2. Copy any starter code provided for you (Starter.ino file) into the [Codebender IDE](https://edu.codebender.cc/class/1ajtp).

Since this assignment is more about testing out your IDE and your ability to run code to the Arduino, this will be a simple assignment.  Specific instructions are listed Below:
1. Be sure to read this entire document before starting your work.  View the image below so you understand what you will be making.
2. Open the [Codebender IDE](https://edu.codebender.cc/class/1ajtp) which is a part of our school license.  There is also a free version of this but it has some limitations which will make it difficult to use for later assignments.  You also need to install the Chrome app from the web store [here](https://chrome.google.com/webstore/detail/codebender-app/magknjdfniglanojbpadmpjlglepnlko?hl=en).
3. Go to the Starter.ino file (above) in this repository.  Copy all of that code into the [Codebender IDE](https://edu.codebender.cc/class/1ajtp) fully replacing the code that is there.
4. Modify line 4 so that it will print "Hello World" when the program runs.  (Put that phrase in quotes inside the parenthesis after `Serial.println`.)
5. Test the code.  
    - Connect your Arduino to your computer with the blue USB cable.  
    - Select "Arduino Uno" in the first pulldown.  
    - Be sure that the second pulldown shows the current USB.  It should say something like `/dev/tty/ACM0`  If you cannot access the pulldown, you need to install the Codebender App on Chrome by clicking the link to the right.
    ![pulldowns](https://github.com/WHS-Robotics-Classes/images/blob/main/Screenshot%202021-01-20%20at%2011.25.10%20AM.png?raw=true)
    
    - Click the "Run on Arduino" button (Green Arrow)
    - Click the "Serial Monitor" button.
    - Be sure the baud rate pulldown is at 9600 and click "Connect".
    - Verify that the correct message is printed by comparing your screen to the image below.
    - If it all worked skip to step 7.  If not, go to next step.
6. Debug the code and repeat step 5 until it works.  Jump down to the link in step 12 to look over the documentation for this function.
7. Click the link above that says "Arduino_0.0-Hello_World".
![arduino-hello-world](https://github.com/WHS-Robotics-Classes/images/blob/main/Repo-main.PNG?raw=true)

8. Select "Add File" and then "Create New File".
![add-file](https://github.com/WHS-Robotics-Classes/images/blob/main/add-file.PNG?raw=true)

![new-file](https://github.com/WHS-Robotics-Classes/images/blob/main/new-file.PNG?raw=true)

9. Name the file Hello_World.ino.
10. Copy the code into the code window.
11. "Commit New File".

![commit](https://github.com/WHS-Robotics-Classes/images/blob/main/commit.PNG?raw=true)

12. Read over the [`Serial.println()` documentation on the Arduino website](https://www.arduino.cc/reference/en/language/functions/communication/serial/println/) to make sure you understand what you just did.

### Your result in the Serial Monitor window should look like this:
![Serial Monitor](https://github.com/WHS-Robotics-Classes/images/blob/main/Screenshot%202021-01-20%20at%201.16.47%20PM.png?raw=true)

--- 

### For an extra challenge see if you can do any of the following:
- Print other messages in the serial monitor.
- Print two messages side by side.
- Print the same message over and over again forever.
- Create a counter so that the serial monitor prints "Counting: " followed by a number that increases by one with every new line.  See below.

![counting up](https://github.com/WHS-Robotics-Classes/images/blob/main/Screenshot%202021-01-20%20at%201.31.08%20PM.png?raw=true)
