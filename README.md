# The TRACKtor - Line Following Robot

In this project we were trying to make a robot that could follow a black line using 7 down facing photoresistors. We calibrated the photoresistors by getting the average values of each photoresistor while it is on a black surface and mapping that value to 0. We then did the same thing with the photoresistors on a white surface. This way, we could tell where in relation to the photoresistors the 1 inch wide black line was. We then used this information of how far off center the black line was and fed it into our PId controller as the error. We used 4 potentiometers to set the multiplication constants of the S (speed), P (proportion), I (integral), and D (derivative). The result of the calculation was fed into the motor controller as voltages so that the motors could change their speed and keep the robot central to the black line. <br>
<br>
Here is the photoresistor wiring diagram: <br>
![Photoresistor wiring diagram](images/Photoresistor%20Wiring%20Diagram.png) <br>
<br>
Here is the potentiometer wiring diagram: <br>
![Potentiometer wiring diagram](images/PID%20Control%20Potentiometer%20Wiring%20Diagram.png) <br>
<br>
Here is the chassis CAD model: <br>
![Chassis design](images/Chassis%20Design.png) <br>
<br>
Here is the printed chassis: <br>
![Printed chassis](images/Printed%20Chassis.png) <br>
<br>
Here is the assembled robot: <br>
![Assembled robot](images/Final%20Robot.png) <br>
<br>
Here is the robot following a line: <br>
![Robot following line](images/Line%20Following.jpg)