# Plant-monitor-system
This IoT based system shares the environment parameters with the user. The user only requires the access of Wifi. The environment paramenters such as temperature, humidty and pressure are reported back to the user. Inorder to connect the sensor with raspberry pi, wiring pi library has been used.

In order to setup the system 
1.	Sign in to Azure portal
2.	Create a resource and search for IoT hub and create it
3.	Registering of simulator into the IoT hub choose any unique device id with location same as the IoT hub
4.	On creation of device a primary connection string is received enter it into the coding area of the simulator
5.	In order to run the code type npm start
6.	The console area will show that its sending the data

7.	The data collection has been started now we send it to IoT hub
8.	In order to communicate live data from simulator for visualization we have the following two steps
                 i. Stream analytics
                ii. Power Bi
9. Setup the line chart to that data recieved 
