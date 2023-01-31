# K-way-Nicla-Smart-Jacket
K-way Smart Jacket with Nicla Sense ME

Includes the MIT App Inventor .aia file.  Can upload into MIT App Inventor to see the blocks.

Also included is the Arduino sketch to run the code.  Could probably use the Arduino IDE but I used PlatformIO in VS Code.

In order to not run into memory issues, you need to change the WORK_BUFFER_SIZE from 2048 to 64 in the BoschSensorTec.h file in the Arduino_BHY2 library.
