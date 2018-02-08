# ESP SPIFFS Uploader + Firmware Updater
Simple HTML file uploader for ESP 8266 SPIFFS 

A substitute of https://github.com/esp8266/arduino-esp8266fs-plugin

I found that Plugin to ruin several Working Hours, Unable to Upload Data files to SPIFFS on ESP 8266.

This simple method helps to upload files to ESP8266 Over the Air.

Hope it helps.

## Device Discovery

Install the Apple Bonjure Service on Windows.

Browse all the Web servers on your local network, open command prompt and type this:

```
 dns-sd -B _http._tcp
```
To get info of a particular one
```
dns-sd -L "<instance Name>" _http._tcp
```

If you need the ip and other info
```
dns-sd -Q my_server.local 
```
