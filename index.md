# Obstacle Avoiding Robot
In this project I design a robot that is able to maneuver around obstacles using an ultrasonic sensor. I was also able to add my own modifications by adding a servo that lets the robot decide which path to take.  

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Samuel H | A-tech | Electrical Engineering | Incoming Senior

![HeadstoenImage](https://i.postimg.cc/7PJntrpw/IMG-8400.jpg)

# Final Milestone
My final milestone I mange to get the robot to turn instead of stopping whenevr theres an obstacle infront of it. I was able to do this by turnin off the motors on the left side and keeping the right ones turn on whenever theres an obstacle within 20 centimters. This allowed the robot to turn to the left. Next I attached the ultrasonic sensor to a SG90 micro servo. When the robot is within 20 centimeters from an obstacle the robot will stops, then servo will turn 45 degrees to the left and right. In each direction, the ultrasonic sensor returns the distance between the robot an the nearest obstacle. The robot turns in the direction with the farther obstacle and continues moving forward until the next obstacle is reached.

[![Samuel H finalmilestone ](https://res.cloudinary.com/marcomontalbano/image/upload/v1658500648/video_to_markdown/images/youtube--akQv5ePTqw0-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/akQv5ePTqw0 "Samuel H finalmilestone ") {:target="_blank" rel="noopener"}
# Second Milestone

My second milestone was getting the robot to stop whenever theres an obstacle within 20 centimeters. I was able to do this by connecting the HC-SR04 ultrasonic sensor. The HC-SR04 ultrasonic sensor emits sound waves at a frequency above human hearing through the trig pin. The sound waves bounce off of the nearest obstacle and are received again by the echo pin of the ultrasonic sensor.Base on the amount of time that it takes for the waves to bounce back the ultrasonic sensor is able to determine the distance from the closest obstacle.  

[![Samuel H Milestone 2](https://res.cloudinary.com/marcomontalbano/image/upload/v1657897872/video_to_markdown/images/youtube--lhwfVbKQ5wQ-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=lhwfVbKQ5wQ "Samuel H Milestone 2"){:target="_blank" rel="noopener"} 
# First Milestone
  

MY first milestone was getting the motors to work work in order to spin the wheel of the robot. I was able to do this using an arduino, an H-bridge, and a battery pack. I coded the arduino to send data to the H-bridge which is what ,akes the motor spin and the battery pack was incharge of powering everything.
A problem that I encounter while doing this was that somo mottors were spinning clockwise while others were spinning countercloclkwise which made the robot spin instead of move foward. However I was able to solve this after fixing some problems with my code.

[![Samuel H Milestone 1](https://res.cloudinary.com/marcomontalbano/image/upload/v1657551255/video_to_markdown/images/youtube--3aWtaafTSi0-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/3aWtaafTSi0 "Samuel H Milestone 1"){:target="_blank" rel="noopener"}


