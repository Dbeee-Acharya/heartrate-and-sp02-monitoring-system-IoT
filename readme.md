<h1> Code and documentation for smart health monitoring system using esp32 </h1>
<br>

<h2>IoT college project </h2>


<h2> Working Device Image </h2>
<img src="./Images/device working.png"/>

<br>

<h2> Schemantic Diagram </h2>

<img src="./Images/Sys arch.png"/>
<br>

<img src = "./Images/Schemantic.png"/>

The maincode folder contains a cpp code named maincode
The vsCode folder contains a cpp code named maincode
Both of the code bases will work with the temperature and sp02/heartrate sensor

the DHT11 sensor does not work due to insufficient voltage in the system
DHT11 sensor is not sending any data to the esp32 module
Values for the DHT11 sensor have been hardcoded 

Due to insufficient voltage, when the temperature sensor and the spo2/heartrate sensors are connected
both the sensors will not work properly

So disconnect the temperature sensor to make the heartrate sensor work
disconnect the heartrate sensor to make the temperature sensor work

All the sensor related issues are because of insufficient voltage and can be fixed by using external power
or by rerouting the power suppy to use both the 3.3v and 5v output power from the esp32 module

<br>

<img src = "./Images/3 dht11.jpg"/>
