# Mini-Vacuum-Cleaner-Robot
Today, all of us are so preoccupied with our jobs that we don't have time to adequately clean our homes. 
The problem can be easily solved by purchasing a domestic vacuum cleaner robot, such the iRobot Roomba, which will clean your home with the touch of a button. But the expense of these commercial goods is a problem they all share. 
We therefore made the decision to construct a basic floor cleaning robot today, which is not only easy to construct but also quite inexpensive when compared to commercially produced items on the market.
The robot will be able to roam freely until the room is well cleaned thanks to the ultrasonic sensor and the proximity sensor, which also prevents it from tumbling down stairs.
Three ultrasonic sensors are used to identify impediments. Therefore, we must connect all of the ultrasonic sensors' grounds to a single common ground. 

Additionally, we link the sensor's three Vcc pins to the shared VCC pin. The Arduino's trigger and echo pins are then connected to its PWM pins. The output pin of the IR sensor module is connected to the Arduino's digital pin D2, and we also link the IR module's VCC to 5V and ground to the ground pin. 
Since we are utilising 5 volt motors, we connect the two enable pins of the motor driver to 5 volts as well as the driver voltage pin.
