# Speed-Control-BLDC
### Design of PI controllers using Ziegler-Nichols method, Genetic Algorithm and ANN, and comparison of their performances

Electric Vehicles(EV) have started capturing significance since people noticed the
after effects of depletion of natural resources, atmospheric pollution and fuel price
hike. The main parts of EV include motor, batteries, controller, sensors, etc.
Different types of electric motors are used for EV application and among them
BLDC motors are popular since they are simple in structure, and high reliability.
The performance of the motor depends upon the performance of the controller and
to identify the most suitable controller for EV application, a comparison study has
to be conducted between several controllers used for controlling the BLDC motor. In
this project, the comparative study is conducted between PI and ANN controllers.
<br><br>
In the first phase of study, PI controller for the BLDC motor is implemented. The
conventional PI type controller is still used in industries because of their relatively
simple implementation and good performance. It improves system stability and
can handle fast load changes. PI controller performance depends upon the tuning
technique used. In this work PI controller is tuned with two techniques (Ziegler Nichols, 
Genetic Algorithm(GA)) and performance is evaluated.
<br><br>
In the second phase of study, ANN controller for BLDC motor is implemented.
Neural Networks have the ability to learn and produce the output that is not limited
to the input provided to them. The PI controller is replaced with ANN controller
for controlling the angular position of the motor. The Neural Network is built using
nntraintool and the performance is evaluated.
<br><br>
The results from the simulation of these controllers are compared in terms of
overshoot, rise time, settling time, ripples, etc. The PI-GA and ANN controllers
have a very small rise time, overshoot, ripples and better transience compared to PI 
Ziegler Nichols. But the PI-GA controller has the least amount of ripples compared
to ANN controller. GA tuning method has increased the stability of the system
by reducing oscillations. For EV application torque should be steady and such a
response is produced by the PI-GA controller. From this study it can be concluded
that the best suited controller for EV application is PI-GA controller.
