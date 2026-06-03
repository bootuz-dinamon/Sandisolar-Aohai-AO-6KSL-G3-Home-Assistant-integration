# Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration
Sandisolar Aohai AO-6KSL-G3 Home Assistant integration via RS-485 using esphome.

Source: https://bootuse.com/forum/viewtopic.php?p=25#p25

If you have established communication with the battery via CAN, then you still have free RS485 and it can be used for integration into Home Assistant.

Off-grid solar inverter Sandisolar 6.5kW - https://s.click.aliexpress.com/e/_c3pTJSjF

The inverter's rated output power is 6000W.
The inverter does not have the Neutral formation function in off-grid mode if Grounding is present.


You will need an RS485-TTL adapter and an esp32 (I use an esp32c6 but the correct one).
RS485-TTL adapter power supply - 5V, connection to the inverter - only lines A and B (without GND).
- RS485-TTL - https://s.click.aliexpress.com/e/_c3yN9U9d
- esp32c6 - https://s.click.aliexpress.com/e/_c3HYdofD


![Sensors](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Sensor1.jpg)
![Sensors](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Sensor2.jpg)
![Sensors](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Sensor3.jpg)
![Settings](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Settings1.jpg)
![Settings](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Settings2.jpg)
![Settings](https://github.com/bootuz-dinamon/Sandisolar-Aohai-AO-6KSL-G3-Home-Assistant-integration/blob/main/Settings3.jpg)
