# IOT-NodeMCU
NodeMCU with DHT22 sensor, using Azure, Node Red and HiveMq

# IOT with Azure, Mqtt, Arduino, NodeMCU and Node Red tutorial part 1

NodeMCU PinOuts using D1 which = GPIO5
![Screenshot](NodeMCUPinOut.PNG)

![Screenshot](NodeMCUDHT22Fritz.PNG)


# IOT with Azure, Mqtt, Arduino, NodeMCU and Node Red tutorial part 2

<b style='color:red'>CODE for Arduino IDE:</b>
https://github.com/itchopshop/IOT-NodeMCU/blob/master/DHTtesterTutorialPart2/DHTtesterTutorialPart2.ino

https://www.arduino.cc/en/Main/Software ******** Arduino IDE

http://arduino.esp8266.com/stable/package_esp8266com_index.json ****** Additional Boards Manager URLs

https://github.com/adafruit/Adafruit_Sensor **** Main Sensor Library

<b style='color:red'>Change the following code in your Arduino C++ program to the below.</b>

#define DHTPIN 5  // GPIO 15 (D1) ***** what digital pin we're connected to


# IOT with Azure, Mqtt, Arduino, NodeMCU and Node Red tutorial part 3

Azure subscription, VM set up in Azure, configuring end points and Node Red installation

https://azure.microsoft.com/en-us/free/ **** link to Azure subscription

http://nodered.org/docs/getting-started/installation.html **** Node-Red setup

https://www.java.com/en/download/windows-64bit.jsp ***** Java Install

https://nodejs.org/en/ ***** Node.js install

http://www.hivemq.com/try-out/ *** Tryout

Connect to Public Broker

Host: broker.hivemq.com

Port: 1883

Websocket Port: 8000


# IOT with Azure, Mqtt, Arduino, NodeMCU and Node Red tutorial part 4

<b style='color:red'>Add pubsubclient library to you Arduino IDE</b>.

http://127.0.0.1:1880/ **** Node Red designer Url

<b style='color:red'>change topics in Node red to:</b>wifiTemp and wifiHumidity

https://flows.nodered.org/ ****** Flows and useful nodes

https://flows.nodered.org/node/node-red-dashboard  **** Dashboard install for Node-Red

npm i node-red-dashboard

http://127.0.0.1:1880/ui/ ***** Node Red Dashboard URL

Code for this section: https://github.com/itchopshop/IOT-NodeMCU/blob/master/NodeMCUAzurePart3/NodeMCUAzurePart3.ino

# IOT with Azure, Mqtt, Arduino, NodeMCU and Node Red tutorial part 5

Just some handy links for setting up Noed red

https://flows.nodered.org/ ******** Flows and Nodes

https://nodered.org/docs/security ****** Security
