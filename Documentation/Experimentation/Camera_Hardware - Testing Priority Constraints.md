# Testing Priority Constraints
## Experiment Description
### Summary
Insert Summary here

#### Subsystem(s) Involved:
Camera Hardware Subsystem

#### Constraints Tested:
- System shall capture an image of the UAS in flight or the control station.
- Images captured by the system shall be transmitted to the database in either a RAW or PNG format with a minimum resolution of 1080px720p.
- Servo motors shall be capable of reaching and maintaining angles required for image capture with a ± 10° range of accuracy.<!-- - Servo motors shall be capable of reaching required angles in a minimum time of 500 milliseconds after recieving the appropriate signal(s). -->
- Camera system shall not draw more than 50 Watts of power.
 
#### Expected Result(s):
- Image of Drone or Operator to be taken and stored.
- A PNG or Raw Image type present in either the database or the computer running the database.
- An angle set by the running software to be met by the servo within a ± 10° range of accuracy (set 70. get anywhere from 60-80).<!-- - Servos reach the set angle within half a second -->
- In all states, system draws well below 50 Watts of power.

## Experimental Procedure
<!-- Description of what you did ideally in steps -->
Image Capture
- Number of trials: 5
1. Using the program developed by the [Camera Software System](https://github.com/mrnye42/S24_Team1_DroneTracker/blob/Experiments/Documentation/Signoffs/Camera_Software_System.md), create and run 5 pseudo-signals from the receiver system for the camera to "track"
2. Allow Program to capture and transmit images
3. Analyze images for drone/operator presence
4. Run and repeat test 5 times, analyzing each for subject's presence
5. Record success in table below

Image Quality
- Number of trials: 5
1. After running the above test, check each image for its quality
2. Verify each image is a png file with a minimum resolution of 1080px720p
3. Record successful attempts in table below
   
Servo Accuracy
- Number of trials: 10
1. Attach a 360° graduated circle to the moving arm of each servo motor.
2. Attach a yellow indicator piece of plastic to show where servo arm is currently pointing.
3. Create a program (aaronTest.cpp) to move the servos to pre-determined angles for testing.
4. Run and repeat test 10 times for each motor, using different angles and recording each result in the data table below.

Servo Speed
- Number of trials: 10
1. While running Servo Accuracy test, time how long it takes for the servo to reach the final angle requested
2. Record results and rough times in the table

Power Draw
- Number of trials: 10
1. For each servo test, analyze the voltage drop and current draw using a DMM
2. Record the highest values seen by testers in table

## Experimental Data
<!-- data tables or graph of the results (whichever is appropriate) -->

## Conclusions
#### Interpretation of Data
<!-- explain what the results of the experiments mean and what conclusions you draw -->

#### Final Thoughts
<!-- Were constraints met? -->