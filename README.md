# Telegram-MeteoBot
Read temprature/humidity and send photo upon request via Telegram. It requires Raspbery Pi, Arduino, temperature and humidity sensors, raspberry-camera.

Arduino UNO is used as a data acquisition module to send data from sensors DHT11(temperature and humidity) and KY-013 (temperature) to Raspberry PI via Serial port:
 * KY-013 Pin A0
 * DHT11 pin 4 

Raspberry Pi night vision camera is connected directly to Raspberry via camera-socket.

Upd1: The Raspberry temperature is also monitored

Upd2: MeteoBot communicates only with an allowed user list

## Commands:
 *  */data* - read and send data from sensors
 *  */photo* - make and send a photo
