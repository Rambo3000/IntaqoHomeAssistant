# IntaqoHomeAssistant
 [Intaqo](https://intaqo.com/) aquarium controller  [HomeAssistant](https://www.home-assistant.io/) integration using basic switches and sensors

Include the sensors and switches configuration to your own home assitant configuration.
Steps:
1. find your configuration.yaml
2. Add the following lines:
   - sensor: !include sensors.yaml
   - switch: !include switches.yaml
4. Copy the sensors.yaml and switches.yaml next to your configuration.yaml
5. Edit the sensors.yaml and switches.yaml and replace the IP adres with the IP of your Intaqo device. Set your intaqo devices IP adres fixed using your router or  DHCP server.
6. Reload the configuration using the UI or restart home assistant
7. Add sensors, search by typing "Intaqo"
8. Enjoy!
