# Telegram-MeteoBot
Read temprature/humidity and send photo upon request via Telegram. It requires Raspbery Pi, Arduino, temperature and humidity sensors, raspberry-camera.

Arduino UNO is used as a data acquisition module to send data from sensors DHT11(temperature and humidity) and KY-013 (temperature) to Raspberry PI via Serial port:
 * Thermistor Pin A0
 * DHT11 pin 4 

Raspberry Pi night vision camera is connected directly to Raspberry via camera-socket.

## Commands:
 *  */data* - read and send data from sensors
 *  */photo* - make and send a photo


UPD
1. Record all the data in csv-file.
2. Save all the photos.
3. The temperature of CPU is also recorded and send via the Telegram bot
