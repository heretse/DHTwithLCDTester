# DHTwithLCDTester
DHT Temp &amp; Humidity Sensors with LCD Display

## Usage
Define your DHT digital pin and type

```ino
// Example testing sketch for various DHT humidity/temperature sensors
// Written by ladyada, public domain

#include <Wire.h>
#include "DHT.h"
#include "rgb_lcd.h"

rgb_lcd lcd;

#define DHTPIN A2     // what digital pin we're connected to

// Uncomment whatever type you're using!
//#define DHTTYPE DHT11   // DHT 11
#define DHTTYPE DHT22   // DHT 22  (AM2302), AM2321
//#define DHTTYPE DHT21   // DHT 21 (AM2301)

```
