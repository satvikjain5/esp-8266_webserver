# esp-8266_webserver
using the esp8266 as a webserver to get real time data from HCSR-04 sensor
The esp8266 hosts a webpage with real time plots from the sensor and refreshes every 3 seconds.
Here an asynchronous web server is being used instead of a synchronous webserver. The webpage is designed using basic HTML which is stored on the esp8266 board using SPIFFS.
The data from the sensor can be modified to match requirements. For example, humidity, temperature, pressure,etc.
The asynchronous webserver listens for connections and wraps the new clients.
