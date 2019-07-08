# ESP8266-E12-Arducam-OV5642
If you encounter a "SPI1 interface error" on the serial monitor, uncomment ```#define OV5642_MINI_5MP_BIT_ROTATION_FIXED``` in the "memorysaver.h" file.

#Wiring
```
    ArduCAM mini   ->    ESP8266-12E
        CS         ->        D0
       MOSI        ->        D7
       MISC        ->        D6
        SCK        ->        D5
        GND        ->       GND
        VCC        ->       3V3
        SDA        ->        D2
        SCL        ->        D1```
