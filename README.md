<h4>Esp8266 with DHT22 / AM2302 Digital Temperature and Humidity Sensor displaying data to 0.96 inch oled and Cayenne MyDevices
</h4>
<p>#What you will need:</p>
<p>1. Esp8266/Nodemcu microcontroller</p>
<p>2. 0.91'' Oled screen</p>
<p>3. DHT22 sensor (DHT11 and DHT21 should work also, you just need to define your model on the code)</p>
<p>#Instructions<br>
  Login to https://cayenne.mydevices.com/ and add new device Generic ESP8266<br>
  Copy MQTT Username, Pass and Client-Id<br>
  Enter all the above in the sketch plus your wifi credentials<br>
  Make sure you have all the necessary libraries installed.<br>
  
  Connect DHT22 data to D5-GPIO14 VCC to 3.3v and GND to GND<br>
  OLED's SCK goes to D1-GPIO5 and SDA to D2-GPIO4<br>
  <br>
  Upload the code<br>
  Enjoy!<br>
  
  Based on code examples from:<br>
  https://randomnerdtutorials.com/esp32-esp8266-dht-temperature-and-humidity-oled-display/<br>
  and<br>
https://community.mydevices.com/t/esp8266-12e-arduino-dht22-bmp180-cayenne/6403</p>
