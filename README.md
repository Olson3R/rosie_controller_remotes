# rosie_controller_remotes
A plugin for the Rosie controller application that adds the ability to interface with an ethernet connected IR blaster. Adds /remotes endpoints.

# Dependencies
1. Ethernet Connected IR Blaster: Developed for [IRTrans Ethernet](http://www.irtrans.de/en/technicalinfo/lan.php)

# Configuration
1. On the [rosie_controller](https://github.com/Olson3R/rosie_controller) application, run `npm install rosie_controller_remotes`
2. Add and configure the plugin in the controllers rejoice configuration file.
```
"rosie_controller_remotes": {
  "IR_TRANSMITTER_URL": "http://192.168.8.12/send.htm",
  "REMOTE_LIST": [
    {"id": "receiver", "title": "Receiver", "key": "denon avr-988"},
    {"id": "tv", "title": "TV", "key": "samsung ln46a750"},
    {"id": "ps3", "title": "PS3", "key": "ps3"}
  ]
}
```
