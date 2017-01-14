Automated Snack Delivery Robot

Set Up
 1. This project is designed for a robot to deliver snacks to users along a straight hallway/passageway. Each user's door has a circle of a unique color on it. 
2. The robot has a driving motor, a turning motor and two line sensors. A white strip is placed on the ground to demarcate the line on which the robot can move.

Basic Functioning 
1. The snack robot is initially kept at one end of a dorm passageway. A user logs into the robot using ssh (remote-access). 
2. On receiveng the request, the master program operates the driving motor in the forward direction untill the camera on the bot observes a circle of the appropriate size and color on a particular door. 
3. While delivering the snack, the line sensing code takes input from the two line sensors.If the robot veers sideways, appropriate corrections are made via the turning motor.
 4. When the robot comes to a stop infront of the right door, the user is informed that their snack has arrived. After the user collects the snack, the driving motors starts in the reverse direction, taking the robot back to the starting postion.