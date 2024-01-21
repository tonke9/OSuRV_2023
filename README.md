# CAN-BUS Protocol

##### Library used:
 mcp2515_can.h from CAN_BUS_Shield by Seeed Studio and SPI.h from SD by Arduino <br/><br/><br/>

### Connection between Arduino and OBD Mary, using ELM327<br/><br/> 

##### Application used for testing:
 Obd Mary<br/><br/>
##### Profile in application:
 OBD2 Standard<br/><br/>
##### Parameters supported:
 CoolantTemp, rpm, vspeed, IATSensor, MAFSensor, AmbientAirTemp, CAT1Temp, CAT2Temp, CAT3Temp, CAT4Temp, VIN number<br/><br/><br/>

### Connection between two Arduino Boards<br/><br/>


##### Basic examples for communication: 
sender.ino and receiver.ino<br/>
##### Expanded communication with boards:
 receive with interrupt, Blink, monitor, sleep, etc.<br/><br/><br/>


##### References used :<br/>
>OBDII_PIDs example in Arudino ide from CAN_BUS_Shield library:<br/>
>https://en.wikipedia.org/wiki/OBD-II_PIDs<br/>
>Generating PIDs: https://www.csselectronics.com/pages/obd2-pid-table-on-board-diagnostics-j1979<br/>
>Code example for sender and reciver: https://github.com/Seeed-Studio/Seeed_Arduino_CAN<br/>
>Description of CAN-BUS Shield:<br/> 
>https://seeeddoc.github.io/CAN-BUS_Shield/<br/> 
>https://wiki.seeedstudio.com/CAN-BUS_Shield_V2.0/<br/>

