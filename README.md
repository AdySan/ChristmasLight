# ChristmasLight

A simple evening hack to remotely control a ralay connected to some Christmas Lights. The relay is conected to a GPIO of an ESP8266, which hosts a webserver and serves files stored on the SPIFFS file system. The web pages can be updated remotely via the browser (http://ChristmasLight.local/edit).

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
