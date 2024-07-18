- Phase 1 (Parking algorithm):
We have built a prototype for implementing a parallel parking algorithm on a mobile
robot car, using an Arduino Mega, ultrasonic sensors and an LCD. A hardware push
button starts process of self-parking the car. On pressing the button, the robot moves
forward, while scanning for vacant spots on the side using ultrasonic sensor array. On
finding a suitable spot of appropriate dimensions, the robot stops at an appropriate
distance. The robot then sends signals to the actuators (4 DC motors) to make a 45 degree
turn and back up into the spot. Then make another 45 degree in the opposite direction to
become straight.

- Phase 2 (Car recentering algorithm):
In our prototype using the car built, an Arduino Mega, ultrasonic sensors and an LCD,
after the car has successfully parked, we applied a closed loop feedback control with a
Proportional gain to recenter the car in its parking slot between its neighboring parking
cars autonomously whenever one of them has moved from its position to keep the safest
distance between both cars. This was possible with 2 ultrasonic sensors in the front and in
the rear to read the distances from the neighboring cars, get the readings average and set
this value as the target where the car tries to reach by adjusting the actuators (4 DC
motors) speed to reach the required destination.

- Code used is attached at the end of the report.
