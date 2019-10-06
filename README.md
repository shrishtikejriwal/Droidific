# Droidific
Droidific is A tele-op prototype of a cleaning robot, configured using the Intel Galileo Gen 2 board, a RC car chassis and android as a platform. It allows users to clean an area with ease by saving time and energy. 

1. The Intel-Galileo board is first configured using the Yocto linux image, and programmed using Arduino.
2. The N135 WiFi card is connected to the board and it used to establish a tethered connection between the smart device and the bot
   Note: WiFi used and not Bluetooth, for future cloud integration
3. The RC car chassis is interfaced with the L298 motor driver and Intel Galileo.
4. A node.js socket server (net-module) is set up and an android app is used to connect to the socket server to send and receive signals in order to control the direction traversed by the robot. 

The prototype can be found under pbl_prototype. 
