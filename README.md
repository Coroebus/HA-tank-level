# -HA-tank-level
Tank level measurement solution for Home Assistant

We use an ESP-32 and a JSN-SR04T module to measure the height of water in a rainwater tank. Depending on the distance and the geometry of the tank we deduce the volume contained in the tank
We use ESPHome to control the ESP32 and expose the information it offers in Home Assistant

Another interesting piece of information to have when you have a rainwater tank and a pump is the temperature near the pump because in the event of frost, it can be damaged.

Once you have an ESP32 for the level in the tank, it is very simple to add a DS18B20 temperature probe.
