# ESP-12E-MQTT-Subscriber
ESP-12E MQTT Subscriber for ESP8266(NodeMCU v3)

1. Import ESP8266MQTTLibary.zip in arduino studio.
   Sketch->Include Library->Add .zip Library


2. Change below variables:
/************************* WiFi Access Point *********************************/

#define WLAN_SSID       "SSID"

#define WLAN_PASS       "PASS"

3. Burn mqtt_esp12e.ino on chip.

4. Login https://io.adafruit.com/

5. Install https://play.google.com/store/apps/details?id=com.thn.iotmqttdashboard&hl=en_IN and configure broker details (refer "Adafruit.io Setup" in mqtt_esp12e.ino).

6. Start publishing on topic "ADAFRUIT_USERNAME/f/onoff"

7. Check serial monitor output and LED on pin 13.
