Esp8266 with DHT22 / AM2302 Digital Temperature and Humidity Sensor displaying data to 0.96 inch oled and Cayenne MyDevices

#Instructions
Login to https://cayenne.mydevices.com/ and add new device ESP8266
Copy MQTT Username, Pass and Client-Id
Enter all the above in the sketch plus your wifi credentials
Make sure you have all the necessary libraries installed.

Connect DHT22 data to D5-GPIO14 VCC to 3.3v and GND to GND
OLED's SCK goes to D1-GPIO5 and SDA to D2-GPIO4

Upload the code
Enjoy!

Based on code examples from:<br>
https://randomnerdtutorials.com/esp32-esp8266-dht-temperature-and-humidity-oled-display/<br>
and<br>
https://community.mydevices.com/t/esp8266-12e-arduino-dht22-bmp180-cayenne/6403
