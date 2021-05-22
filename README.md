# Line-Follower-Robot

A working model of line follower robot by using Arduio uno.

## What is a Line Follower
A line follower robot is a robot that can track lines and follow them, proceeding along a preset path that can be altered by moving the lines. Our robot can distinguish between different colors, making it possible for them to follow one among several lines accurately.


## Working
As we know that different colors tend to absorb different amount of light. Like black absorbs more than lighter colors, light sensors work on basis of this principle only.  The light sensor radiates some light and checks the amount of light reflected back and that’s how we differentiate between colors using light sensors.

Now, we have used 2 light sensors and the robot would be placed in such a way that both the light sensors are on the either side of the line to be followed. For instance, let us suppose the line to be followed to be black and the color surrounding it to be white. Now, we will program it in such a way that if both the sensors are on white the robot should keep on moving straight. If one of the sensors detects black, the bot should turn in the direction of sensor detecting black until it starts detecting white again and then start moving straight again. So this is how a line follower works with the help of light sensors.

![image](https://user-images.githubusercontent.com/58677568/119220452-4663a500-bb08-11eb-87ba-d63f5ac7297c.png)

## Materials used
Arduino uno
2 BO Motors 150
2 IR Proximity Sensors (light sensors)
L298N Motor Driver Module
Connecting Wires
Wheels
Batteries
Cardboard
Glue-gun
Chart Paper and Tape(for path)
