# IntaqoHomeAssistant
Intaqo Aquarium controller HomeAssistant integration using basic switches and sensors

Include the sensors and switches configuration to your own home assitant configuration.
Steps:
1. find your configuration.yaml
2. Add the following lines:
     sensor: !include sensors.yaml
     switch: !include switches.yaml
3. Copy the sensors.yaml and switches.yaml next to your configuration.yaml
4. Edit the sensors.yaml and switches.yaml and replace the IP adres with the IP of your Intaqo device.
5. Reload the configuration using the UI or restart home assistant
6. Add sensors, search by typing "Intaqo"
