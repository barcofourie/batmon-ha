* Current calibration factor
* For large publish periods, publish mean values
* MicroPython port
** https://docs.micropython.org/en/latest/reference/packages.html 

* smooth current (10s)
* only mqqt publish differences
* SoC Energy compute?
* temperatures
* parallel fetch

* MQTT discovery cleanup (use new names)
* dashboard integration preset? https://community.home-assistant.io/t/esphome-daly-bms-using-uart-guide/394429
* add ant bms: https://diysolarforum.com/threads/for-those-of-you-looking-to-monitor-your-ant-bms-with-pi3-via-bluetooth.6726/

Victron Readouts https://github.com/fl4p/batmon-ha/issues/63

Merge Batteries together

DONE:
* BMSSample POD class

- Rename MQTT messages
- cell voltages
- battery current, voltage, soc, capacity, charge
- bms mosfet state
- don't send discovery for nan-only data