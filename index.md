# Phone-Controlled Robot Arm
<!--Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:

This is an HTML comment in Markdown 
Anything between these symbols will not render on the published site-->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Krishna D. | American High | Software Engineering/Design | Rising Sophomore

<!---**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone-->

# First Milestone

<!--**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/XQz-tYDIEzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!--For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project-->
## Summary
My intensive project is the phone-controlled robot arm. Using a wired controller with thumbsticks, the user can control the robot to move forward, backward, right, and left to grab objects with its expanding claws. 
### Components Used
- Arduino Nano: Stores the code that controls the arm and utilizes pins to connect and manage different components
- Servo 1(MG90): Rotates left and right to move the entire robot around at the base
- Servos 2, 3, 4(SG90): Rotate left and right to control the joints and claws of the arm
- Joysticks: Uses left, right, top, and bottom movements of the thumbstick to controll the arm's movements
- Turntable: Small metal balls between two plates allow it to rotate 360 degrees at the base
- 9V battery & clip: Powers the Arduino
- Wooden cutouts: Make up the physical parts needed for the arm; the claws, the joints, the base <br>
When you plug the battery clip into the 9V, the robot powers up and the Arduino lights up. The user hold the wired controller and moves the thumbsticks in specific gestures to control the arm. For the left joystick, up moves the arm forward, right moves the based counter-clockwise, down moves the arm backward, and left moves the base clockwise. With Servo 1 screwed into the wooden base and turntable, it allows the rest of the components above it to move left and right with the servo movement. Servo 2 allows for forward and backward movements, since its fixed to the wooden arm. For the right joystick, up closes the claw, down expands the claw, left starts recording an action, and right peforms the recorded action. Servo 4, at the top of the arm, moves one of the claws. Geared against the other claw, both claws move in opposite directions simultaneously. Each time a joystick has input, the Arduino uses its uploaded code to match it to a function and transmit an electronic signal to the servos, which move. 
## Challenges Faced
The components of the project depend mostly on screws and stacked in an upward position, meaning although the initial installation is easy, fixing any past errors means disassembling multiple components below it. Another challenge I faced was initially using the servos; I realized you need to adjust servos 90 degrees before installation.
## Next Steps 
Coding the Android app for the arm and creating custom functions for Servo 3 in the Arduino code.

# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaBMmpWIf28" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Summary
My starter project was a digital clock with an alarm. With the clock, you can customize the hours and minutes of the display and set alarms for specific times. The clock beeps when the user presses a button or the alarm time has come.
### Components Used
- Microcontroller: Coded to manage the circuit and its different components
- Crystal: Keeps track of the time set to change the display with minutes and hours
- Buttons: Enable the user to control the time displayed and set alarms based on different combinations of presses
- Buzzer: Plays a beeping sound to notify the use of a change in settings or an alarm
- Triode: Amplifies the audio and radio signals
- Ceramic/Electrolytic Capacitors: Store and release electrical energy to control different parts of the circuit
- Transistors - Amplify and direct electronic signals
- Display - Shows the four digits for the time
- AA batteries & holder: Power the circuit <br>
For the user to adjust the time and set and alarm, they have to use the two buttons at K1 and K2. When you press the button in a certain combination, the microcontroller runs its code based on the button input to change the digits in the display. Using the different types of At the same time, the microcontroller sends an audio signal to the buzzer, which the triode amplifies and the buzzer plays. When the user long presses K2 and saves their time settings, the crystal starts to track time. Every sixty seconds, the minute digit with change, and every 60 minutes, the hour digit will change in the display. Transistors assist in generally controlling user input and the crystal to send to the microcontroller. The capacitors help supply electrical energy towards different components like the buzzer or display based on the microcontroller and button input.
## Challenges Faced
Most components in the project require soldering, and being a beginner to soldering, my first attempts didn't go well. I overheated the soldering iron, soldered with too much material, and scratched the fiberglass of my first board trying to desolder. I also had a hard time distinguishing between what to solder and what to not. I learned that many of my challenges came from not cleaning the iron's tip and not being able to put conductive material on the tip.
## Next Steps
I have to start on my main project, the Phone-Controlled Robotic Arm. I have to build the arm, adjust the components and code, and develop/connect and app to the physical build.

<!---# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https:///YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.-->
