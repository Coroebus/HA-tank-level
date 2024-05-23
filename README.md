# -HA-tank-level
Tank level measurement solution for Home Assistant

![image](https://github.com/Coroebus/-HA-tank-level/assets/11136092/ab5d5e14-226a-49a2-b550-33a9459d45ca)

We use an ESP-32 and a JSN-SR04T module to measure the height of water in a rainwater tank. Depending on the distance and the geometry of the tank we deduce the volume contained in the tank
![image](https://github.com/Coroebus/-HA-tank-level/assets/11136092/5f44e6a1-b8c1-42ab-bb8b-345e0ee045f1)

ESPHome is very useful to control the ESP32 and expose the information it offers in Home Assistant
![image](https://github.com/Coroebus/-HA-tank-level/assets/11136092/2bf8b717-9ec3-4dcf-850f-32a56e1f75a3)


Another interesting piece of information to have when you have a rainwater tank and a pump is the temperature near the pump because in the event of frost, it can be damaged.
![image](https://github.com/Coroebus/-HA-tank-level/assets/11136092/18b20d2a-489e-41b8-9c6e-0b13dbec9eec)

Once you have an ESP32 for the level in the tank, it is very simple to add a DS18B20 temperature probe.
![image](https://github.com/Coroebus/-HA-tank-level/assets/11136092/828407e5-20b8-4788-9367-bb38d3ccf13c)

Here is the shopping list:
- ESP32
  https://www.amazon.fr/dp/B071P98VTG
- JSN-SR04T Waterproof Ultrasonic Sensor Distance Detection
  https://www.amazon.fr/gp/product/B07Z915YCY
- DS18B20 temperature sensor modules with waterproof stainless steel probe
  https://www.amazon.fr/gp/product/B094FKQ9BS

In my particular case, my pump shelter is buried and it is difficult to receive WiFi correctly. So I ran an Ethernet cable from the house and used an ESP32 powered by POE and connected by Ethernet
- https://www.amazon.fr/Olimex-ESP32-POE-ISO/dp/B08NWLHH8V

And to complete a 3D printed case
![image](https://github.com/Coroebus/-HA-tank-level/assets/11136092/7aa7ff78-e344-4888-8d8b-6a796d0f4094)

and its cover
![image](https://github.com/Coroebus/-HA-tank-level/assets/11136092/5a379158-2766-4b99-bffe-68fd9c214ab1)

![image](https://github.com/Coroebus/-HA-tank-level/assets/11136092/966216db-0d93-46c4-887a-c943f19d083a)
