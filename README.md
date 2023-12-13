# MMConfig
MMConfig is responsible storing/loading config on the microcontroller. It's dependant on MMNetwork because it will change MMNetwork to Access Point mode so that other WiFi device can connect to it.
MMConfig automatically generate a HTML page based on the config available hence it also run a web server.This configuration page can be accessed by connect to it's WiFi or when it's connected to your WiFI router.
Currently, it also support config changes from MMNetwork, hence allowing you to change config over Internet but however MMNetwork is not publically available right now.

> Future Roadmap:
> - Allow custom HTML page to be set so we get nicer configuration page if the developer choose to do so
> - Optimise the memory usage by releasing array memory after use 

> Dependencies:
> - ArduinoJSON

# Note
This is designed for RP2040 using Arduino-Pico and ESP32.

# Credits
- Pure CSS is included in MMConfig to beautify the HTML configuration page
