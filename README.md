# Some Examples for the WT32-SC01 
The WT32-SC01 is a ESP32 Development board with a 3.5-inch color touch screen

## Build

* platformio run
* platformio run -t upload
* pio remote run -t upload

## "Arduino" Example
Fork of [WT32-SC01-Exp](https://github.com/seaniefs/WT32-SC01-Exp) with platformio Support


## "Arduino_lvgl" Example
A simple examples to show how to use lvgl with the WT32-SC01. The Arduino Framework and Platform.io as the build environment are used.

Based on the work of several people:
* WT32-SC01-Exp for the Basis support of TFT und Touchscreen
* [Platformio-Example from lvgl](https://github.com/lvgl/lv_platformio)
* [Example from daumemo.com](https://daumemo.com/how-to-use-lvgl-library-on-arduino-with-an-esp-32-and-spi-lcd/) 
* Random remakrs about lv_tick_task and the freertos tick hook

