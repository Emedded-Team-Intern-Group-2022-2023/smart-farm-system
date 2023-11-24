# Hardware Design
The circuit has been grouped into sub circuits for ease of design, testing and implementation:
1. Power supply
2. sensing, logic processing and communication
3. high power circuit control

Each subcircuit has the following functional requirements:
1. Power supply
   1. input voltage of 12V to 24V
   2. output voltage of 5V
   3. output voltage of 3.3V
2. sensing, logic processing and communication
   1. temperature sensing at accuracy of $\plusmn 5 \degree C$
   2. humidity sensing at accuracy of $\plusmn 5 RH$
   3. data communication using MQTT protocol, over LoRa radio
3. high power switches
   1. input voltage



## 1. Power supply
