# Home-automation-system

Abstract:

The objective of this project is to develop a home automation system using nodeMCU and relay switches, which can control LEDs using voice.
With progressive technological advancement, the work required to achieve a simple task has significantly decreased, one of these essential advancements is “Home Automation,” which is controlling devices using commands from a smart device.

Introduction: 

“Home automation” refers to the automatic and electronic control of household features, activities, and appliances. The utilities and features of our home can be easily controlled through the Internet. 
Many modern houses are now gradually shifting from conventional switches to a centralized system, involving remote-controlled switches. Conventional wall switches located in different parts of the house make it difficult for the user to go near them to operate. Even more difficult for the elderly or physically handicapped people to do so. The remote-controlled home automation system provides a most modern solution with smartphones.

Aim of the project

To develop a home automation system that can turn on and off LED using voice control as well as with buttons and switches.

Components required
1.	NodeMCU 8266
2.	4-channel relay switch 
3.	3 LED and LED holder
4.	Switches
5.	Jumper wires

Software and applications required
1.	Arduino IDE
2.	Sinric Pro
3.	Google Home

About
1.	NodeMCU 8266: is an open-source platform based on ESP8266 which connects objects and lets data transfer using the Wi-Fi protocol.
 <img width="752" height="382" alt="image" src="https://github.com/user-attachments/assets/c104dae2-8795-43aa-981e-d971b44fc80c" />

2.	4-channel Relay switch: they are used to control the opening and closing of circuit contacts of an electronic circuit. It can interface board allows us to control various appliances and other equipment with large current. In this case, we are using 4 channel relay switch, i.e. it can connect a maximum of 4 devices.
 <img width="683" height="459" alt="image" src="https://github.com/user-attachments/assets/ea193895-c566-4fe3-b9f2-6409704cb76c" />

3.	Switch: is an electrical component used to disconnect or connect the conducting path in an electrical circuit, interrupting the electric current or diverting it from one conductor to another.


4.	LED: they are an output device which generates light with the help of light emitting diodes. The input to LED is AC supply.
 <img width="476" height="476" alt="image" src="https://github.com/user-attachments/assets/ad6b6f6c-cd19-4c97-84c2-2681036d7da5" />

5.	Jumper Wires: Jumper wires are used for making connections between items on your breadboard and your Arduino’s header pins. Use them to wire up all circuits.
 <img width="524" height="392" alt="image" src="https://github.com/user-attachments/assets/ccf6fa85-dd32-4da5-9eb4-749b473073f9" />

Circuit diagram 
<img width="975" height="533" alt="image" src="https://github.com/user-attachments/assets/ffa6a08c-e48f-4c0d-a50f-a322cff7aa22" />


Description and connections in the project:

To control the LEDs with voice, Google Home app is used in the smartphone which uses the platform “Sinric Pro” to connect with the NodeMCU board.
•GPIO pin D2, D5m D6 of NodeMCU is connected to in2, in3, in4 of relay module, to control their respective module.
•GPIO pins D3, D7, and RX are connected to the manual switches which are then further connected to the ground.
•On the other half of the relay switch, where the AC supply is provided, the three bulbs are connected.
•Relay switch is used in Normally Open conditions which are connected to one terminal to bulbs and the other terminal of the bulb is connected to a neutral wire.
•The common of the relay is connected to the live wire, after this both live and neutral wire are connected to a plug which is used for AC supply 


