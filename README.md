# Smart-Room-Automation-System-using-Combinational-Logic-Circuit-and-Sensors
University Project I made during my EEE3104 Digital Electronics Lab OEL. First I did it in Quartus Simulation then Hardware.
Working Principle:

The smart room automation system functions based on the inputs received from three sensors: a light sensor (photoresistor), a temperature sensor (thermistor), and a human presence sensor (PIR sensor). These sensors output binary signals used to control an LED light and a fan via a Logic Array using AND and NOT gates.

The system operates as follows:

1. Light Sensor (L):

• Outputs 0 if it is dark.

• Outputs 1 if it is light.

2. Temperature Sensor (T):

Outputs 0 if the temperature is X degrees Celsius or lower.

• Outputs 1 if the temperature is above x degrees Celsius.

3. Human Presence Sensor (H):

Outputs 0 if no human is present.

• Outputs 1 if a human is present.

Logic Operations Output:

1. LED Light (L):

• The LED light turns ON (L=1) if a human is present (H=1) and it is dark (L=0).

• The LED light remains OFF (L=0) if no human is present (H=0) or if it is light (L=1).

2. Fan (F):

• The fan turns ON (F=1) if a human is present (H=1) and the temperature is above X degrees (T=1).

• The fan remains OFF (F=0) if no human is present (H=0) or if the temperature is degrees or lower (T=0).

#Below Project software and hardware implementation pictures are given:

![Image](https://github.com/user-attachments/assets/3fc27f29-518a-4624-acd9-d9c3d61a3d60)

![Image](https://github.com/user-attachments/assets/74714536-3d92-4ca6-b80b-3bdfcf1279ff)


Equipment List with Estimated Costs in BDT:
Breadboard: 200tk
PIR Motion Sensor: 95tk
7408 AND Gate: 25tk
7404 NOT Gate: 20tk
Digital Temperature Module: 95tk
LDR Sensor Module: 75tk
Wires: 50tk
LED: 5tk
DC Fan: 90tk 
