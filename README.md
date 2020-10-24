# SmartHome FW For NodeMcuV3
This is firmware for NodeMcu V3 board that works with custom blynk server and allows you to remote control your devices
## Features
* AUTO OTA Updates from your github repository(public rep's only)
* LED Control - you may turn on/off your led, control it's color
* Sketch for Arduino ide and certificates for OTA updates
## WIP
* Documentation
* Blynk official server support(not only your custom server)
* Web Interface
* SD-card support and logs(with logs accesible in web interface)
* Roller blinds control(via H-Bridge, reed switch and rotation sensor)(all of them will be controlled as one roller blind, due to small number of digital pins without pwm on NodeMcuV3(But it will be able do control any amounts of roller blinds separetely using external ATMega chips)
* Curtain Control (via stepper motor, like Aqara Curtain controller(but via wifi,not zigbee,and with blynk protocol)
* Wall Switch control(you'll be able to install nodemcu v3 and relay into wall switch and use it local(by switching wall switch) or via blynk)
* Plug control(i.e. smart plug) (will work with relay)
* Support for esp8266 chip(not only for nodemcu v3 board)
* Communication with external ATMega chips(Arduino) to use them as source of additional digital pins without pwm(To control more devices)
* Support various H-Bridges, not only L9110-like
* Support various Dual Full-Bridge Drivers, not only L298N-like
* Settings save/load from eeprom and it's setup from blynk app and from web interface
* More settings for more customization
* Automatic ssl certificates retrieving(w/o pc)
* Server-mode for devices with miOT and miOI protocols(Xiaomi smart home devices) (No hub will be required for WiFi device, communication throw blynk)
* MQTT support(not only blynk)
* More beautiful and readable code
* Less memory usage
* Low energy sleeping mode while not active
* Autonomous mode(it'l be able to work from battery, and to see it's charge)
* Correct English translation 😊
## Dependencies
* Blynk library - https://github.com/blynkkk/blynk-library/releases/
* ESP_OTA_GitHub - https://github.com/yknivag/ESP_OTA_GitHub
* ESP8266 Boards installed in your Arduino Ide
## Keep in mind
Remember that this project is licensed under GNU GPLv3, and you are allowed to do anything with it, excepting distributing it with some device or w/o any device with closed source.
If you use this project in yours code, please leave a link to this repository.
