# vehicle_simulator_IOT_raspberryPI
This program simulates the basic functionality of a vehicle using a RaspberryPi and hardware components such us an ultrasonic sensor, LDR sensor, DC motor, servo motor and RGB leds. 

## Running the program
### Prerequisites
1. RaspberryPi
2. Ultrasonic Sensor
3. LDR sensor
4. DC motor
5. Servo motor
6. RGB leds
7. Protoboard
### HARDWARE configuration
Connect the components as in the following image:

<img width="763" alt="Hardware configuration SCHEME" src="https://github.com/pablohd10/vehicle_simulator_IOT_raspberryPI/assets/98902991/85139910-5617-4ca6-ab39-a54563038ddf">

Establish the digital/PWM pins as specified in the code (or configurate them as desired)

### SOFTWARE configuration
- [ ] Clone the repository.
- [ ] Connect your device to the raspberryPI.
> [!TIP]
> Connect the rapberry to the device via ssh. Remember that they must be in the same network.
- [ ] Run the file vehicle.py in the raspberryPI. To do this you have 2 options:
  - Upload the code to the raspberry and execute it
  - Create a remote interpreter in Pycharm and execute the code through this interpreter

