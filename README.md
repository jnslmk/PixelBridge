# PixelBridge
WLED control board with intefacing options via wired Ethernet and DMX.

## Design Goals
- Wired Ethernet
- DMX support (optional by soldering components oder add-on board)
- 5V to 24V supply voltage without jumper between 5V and higher voltages
- Signal conditioning resistors with selectable resistance
- Signal conditioning capacitors
- Exchangeable fuse support (mini ATO)
- Accessible ESP pins via headers or JST XH connectors
- Power saving by enabling Vout via MOSFET
- Level shifted signal output to 5V
- External antenna support for WiFi

## Open Design Decisions
- Make board options available via add-on boards or by not equipping the circuit board with them
- Decide whether to add buttons directly to PCB
- Pluggable or screw terminals for data and power supply
- Use ESP32 or ESP32-S3
- Use resettable or ATO fuses

## Related Boards
- https://github.com/bobko69/8PortLEDDistro
