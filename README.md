# Sandisolar Aohai AO-6KSL-G3 Home Assistant integration
Sandisolar Aohai AO-6KSL-G3 Home Assistant integration via RS-485 using esphome.

![Sandisolar Aohai AO-6KSL-G3](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/SD-PRO-EU-6_8.webp)

Source: https://bootuse.com/forum/viewtopic.php?p=25#p25

If you have established communication with the battery via CAN, then you still have free RS485 and it can be used for integration into Home Assistant.

Off-grid solar inverter Sandisolar 6.5kW - https://s.click.aliexpress.com/e/_c3pTJSjF

The inverter's rated output power is 6000W.


You will need an RS485-TTL adapter and an esp32 (I use an esp32c6 but the correct one).
RS485-TTL adapter power supply - 5V, connection to the inverter - only lines A and B (without GND).
- RS485-TTL - https://s.click.aliexpress.com/e/_c3yN9U9d
- esp32c6 - https://s.click.aliexpress.com/e/_c3HYdofD

Pinout RJ45 Sandisolar Aohai AO-6KSL-G3:
BAT_NTC and GND - you can connect a 10kΩ NTC to these pins to measure battery temperature.
If you don't need this, comment out the "Temp External NTC" sensor.

![Pinout](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/rj45.jpg)

Sensors:

![Sensors](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Sensor1.jpg)
![Sensors](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Sensor2.jpg)
![Sensors](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Sensor3.jpg)

Settings:

![Settings](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Setting1.jpg)
![Settings](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Setting2.jpg)
![Settings](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Setting3.jpg)
