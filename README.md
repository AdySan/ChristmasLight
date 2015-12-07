# ChristmasLight

A simple evening hack to remotely control a relay connected to some [Christmas Lights](http://www.aliexpress.com/item/Free-shipping-led-string-light-10M-100led-AC110V-or-AC220V-colorful-holiday-led-lighting-waterproof-outdoor/1920704737.html). The relay is conected to a GPIO of an [ESP8266](http://www.aliexpress.com/item/New-Wireless-module-NodeMcu-Lua-WIFI-Internet-of-Things-development-board-based-ESP8266-with-pcb-Antenna/32299982691.html), which hosts a webserver and serves files stored on the SPIFFS file system. The web pages can be updated remotely via the browser (http://ChristmasLight.local/edit).

## Features

 - SPIFFS filesystem to store webpages
 - File uploads to SPIFFS filesystem via browser
 - OTA firmware update (using ArduinoOTA)

</br>
<p align="center">
<img src="/images/circuit_bb.png" align="middle"alt="Circuit" height="600">
</p>
</br>
<p align="center">
<img src="/images/screenshot.png" align="middle" alt="webpage" height="600">
</p>
</br>
<p align="center">
<img src="/images/edit.png" align="middle" alt="File uploads" height="600">
</p>
