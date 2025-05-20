# Epever-upower-homeassistant
Home assistant modbus configuration for epever upower UP3000-M3322 inverter/charger. The modbus addresses may work with other epever devices, but have only been tested with the UP3000-M3322 device

## How to add to home assistant
- connect the inverter to a modbus compatible rs485 to ethernet adapter(or other adapter that can be connected to home assistant), like USR-TCP232-306 (example configuration below). The manual contains the pinout for the RJ45 serial port on the device
- install modbus extension
- add modbus.yaml to home assistant configuration folder (same folder as configuration.yaml)
- Add modbus: `!include modbus.yaml` to configuration.yaml

## Pictures:
[](https://raw.githubusercontent.com/ArttuKuikka/Epever-upower-homeassistant/main/ha1.png)
[](https://raw.githubusercontent.com/ArttuKuikka/Epever-upower-homeassistant/main/ha2.png)
[](https://raw.githubusercontent.com/ArttuKuikka/Epever-upower-homeassistant/main/serial.png)
