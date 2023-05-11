# Weather Monitoring System using the Nodemcu ESP8266 board and the New Blynk app

Block Diagram:

![block diagram](https://github.com/Rakshita2003/Weather-Monitoring-System/assets/101338848/74033ad4-f276-4920-904f-12e3d9477399)

Circuit Diagram:

![circuit diagram](https://github.com/Rakshita2003/Weather-Monitoring-System/assets/101338848/8aeb7c41-ec17-47c7-9998-fe032ba4d7dc)

*Step 1:* Firstly, identify these components i.e. Temperature Sensor, Pressure Sensor, Humidity Sensor, Rain Sensor and Light Sensor.

*Step 2:* Attach these components one by one to the breadboard.

*Step 3:* Connect these components to the Nodemcu board. For that, use the circuit diagram.

*Step 4:* Now go to the Blynk website and create a new account using your email address. Then, sign in to your account and create a new template for this project. Then name it as you like. I named it the “Weather Monitoring System”.

click the datastreams tab and create the five datastreams for this project. For that, use the information below.
Virtual Pin > Name –> Temperature / Pin –> V0 / DataType –> double / MIN –>0 / MAX –> 100
Virtual Pin > Name –> Humidity / Pin –> V1 / DataType –> double / MIN –>0 / MAX –> 100
Virtual Pin > Name –> Rainfall / Pin –> V2 / DataType –> integer / MIN –>0 / MAX –> 100
Virtual Pin > Name –> Pressure / Pin –> V3 / DataType –> double / MIN –>300 / MAX –> 1100
Virtual Pin > Name –> Light / Pin –> V4 / DataType –> integer / MIN –>0 / MAX –> 1


Now, click the web dashboard tab. Then, drag and drop the four Gauge widgets and one LED widget to the dashboard. Next, click on the settings icons one by one in the widgets and select the datastreams that we created earlier. Finally, arrange these widgets as you like.

Next, click the search icon and create a new device. For that, select the template you created earlier.

OK, the Blynk Web Dashboard is now ready

*Step 5:* Now, let’s connect the Nodemcu board to the computer throub the cable and upload the program in NodeMCU

(Program/Code of this project is already uploaded in the folder)

*Step 6:* Also, download all the files from the folder name "Libraries".

*Step 7:* Now, copy and paste the Blynk auth token. It’s in the web dashboard. Also, include your WIFI connection details.

*Step 8:* Next, select board and port. After that, upload the code to the Nodemcu board.

*Step 9:* Now remove the USB cable and connect the external 5v power supply.

(Note: Pressure Sensor requires 2V-5V power supply. You can also use an adapter which carriers less than 5V)

# Output:

# LCD Display
![lcd](https://github.com/Rakshita2003/Weather-Monitoring-System/assets/101338848/4cc18947-eda5-4a81-a648-1a60e9da21f9)

# Blynk Dashboard
![blynk](https://github.com/Rakshita2003/Weather-Monitoring-System/assets/101338848/e0fb0312-595e-48b2-884b-4257ee9e8d7e)

(Note: A video of this project is added)
