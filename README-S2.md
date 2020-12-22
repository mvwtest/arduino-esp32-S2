1，Download the manager from the ESP32s2 branch

https://github.com/espressif/arduino-esp32/tree/esp32s2

https://github.com/mvwtest/arduino-esp32-S2/tree/esp32s2

then you have to open the path where the Arduino IDE stores its preferences:

![Pin Functions](https://github.com/mvwtest/arduino-esp32-S2/blob/master/docs/ESP32-S2-download-Arduino-IDE-boards-implementation-download-selected.jpg)

Now find the esp32 implementation, in my case it’s the folder


![Pin Functions](https://github.com/mvwtest/arduino-esp32-S2/blob/master/docs/ESP32-S2-download-Arduino-IDE-preferences-folder-path.jpg)

<Arduino IDE preferences path>\packages\esp32\hardware\esp32.0.4

the result become

C:\Users\renzo\AppData\Local\Arduino15\packages\esp32\hardware\esp32.0.4


Than open the zip of the branch and copy the same file and folder to the esp32 path


![Pin Functions](https://github.com/mvwtest/arduino-esp32-S2/blob/master/docs/ESP32-S2-copy-branch-to-esp32-implementation.jpg)

Now you can find the ESP32s2 Dev Kit implementation on your Arduino IDE:


![Pin Functions](https://github.com/mvwtest/arduino-esp32-S2/blob/master/docs/ESP32-S2-board-manager-ESP32s2-Dev-Module.jpg)


thanks 4 ：

https://www.mischianti.org/2020/12/01/esp32-s2-pinout-specs-and-arduino-ide-configuration-1/
