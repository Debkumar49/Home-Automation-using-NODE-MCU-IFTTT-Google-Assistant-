# Home-Automation-using-NODE-MCU-and-IFTTT

This project is implemented using NodeMCU, 2Way Relay Switch, LM7805 Transistor, a breadboard, a veroboard, couple of jumper wires, multimeter, and as for the software implementations we have used google assistant, Arduino ide for the coding, IFTTT applet launcher and Adafruit IO for the Wi-Fi connectivity.

Our goal with this project is very simple yet useful that we have implemented home automation. Basically we have controlled the home electronic appliances such as turning light on/off with voice recognition system.

From the google assistant we give voice recognition such as “turn on light/turn off light”. Then is responses “turning on/off light”. After that it connects with the IFTTT applet launcher which sends instructions through adafruit io to Node MCU wi-fi module (ESP8266)
Which then connects to the relay and the relay works as a switch by turning the light on/off in terms of the instruction you give.
