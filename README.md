# AutonomousBot

Autonomous Navigation Bot- Curio 

The code mentioned above belongs to the Processing part of the Autonomous Navigation Bot- Curio .

The path data obtained from ROS to the destination is stored in a text file which is accessed line by line and sent to the motors when a indication is received from them assuming they have travelled the expected distance .

Simultaneously sensors are connected to another controller to cover dynamic obstacles and the sensor data is sent to the processor which is Raspberry Pi wherein it's processed for obstacles detection range so as to stop the motors when required. 

Most importantly , in order to reach the destination the user interface is provided based on GTK wherein the user inputs the desired destination.

All these 3 tasks , are performed using threading concept .
