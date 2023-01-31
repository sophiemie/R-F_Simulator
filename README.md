# Robot@Factory Simulator
Our code for the Robot@Factory for the SimTwo2022 Simulator. It was created for the competition for the BIP Embedded Systems, where we participated beetween the 9th and 13th of january at the IPB in Braganca.

## Acknowledgements

 - [Robot@Factory Lite: An Educational Approach for the Competition with Simulated and Real Environment](https://core.ac.uk/reader/323508990)
 - [SimTwo Realistic Simulator: A Tool for the Development and Validation of Robot Software](https://www.academia.edu/80708613/SimTwo_Realistic_Simulator_A_Tool_for_the_Development_and_Validation_of_Robot_Software)

## Authors

- [Sophie Mießner](https://www.github.com/sophiemie)
- [Josephina Ochynski](https://www.github.com/josy12345)
- [Liu Lizhong](https://www.github.com/llzlby)

## Run

- Clone the project

```bash
  git clone https://github.com/sophiemie/RAF_Simulator
```
- Load the code on an ESP32
- Connect the ESP32 with your device with an usb-micro cable
- Start the SimTwo2022 Simulator
- Choose the Scene RobotFactoryLite2022
- Start the Simulation

## Work with the Simulation
In this simulation there are some different scenes that can be simulated. We have to choose the scene RobotFactoryLite2022.  We can change a scene by right-click with the mouse on the current scene. After that we can see the scene. 

<img src="/Simulator/Scene.png" width="40%" height="40%">

On the left side is the robot and on the top the boxes at the startposition. The robot need to carry the boxes at the right side of the scene.

If we want to connect the microcontroller with the simulator, we have to open the configurations and switch to I/O. Then we can choose in the Com Port Field the port where the microcontroller is connected. If the field is green then the microcontroller is connected with the simulator. When the field is red then its disconnected. 

<img src="/Simulator/config.png" width="20%" height="20%">

To start the simulation, the sheets must be open. Then there are two buttons which can start and stop the simulation. There are also buttons for the robot ant part 1 to 4. When the simulation is stopped, these buttons can be used to set the robot or the boxes to the startpoint. The coordinates are standing under the buttons.

<img src="/Simulator/sheet.png" width="30%" height="30%">

## State Mashines
### Main State for the Simulation:
<img src="/States/main.png" width="20%" height="20%">

### States for the four boxes:
<img src="/States/state_machines.png" width="100%" height="100%">

## Documentation

You can find the Documentation in Report_RAF_Group9.pdf.

## Related

You can find the project for our real Robot@Factory here

[RAF](https://github.com/sophiemie/RAF)
