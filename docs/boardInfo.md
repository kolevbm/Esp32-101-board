# Информация за развойната платка

## ESP32-30pin

> **ESP32-101-board** е платка, състояща се от микронтролер и редица периферни модули, свързани към него. Използваният микроконтролер е ***ESP32*** под формата на ***30 pin***-ов модул, който има следните характеристики:

- 32-битов микропроцесор, 1 или 2 ядра, до 240MHz

- 520КB SRAM, 4MB flash

- 802.11 b/g/n WiFi (2.4GHz)

- Bluetooth v4.2 Classic, BLE

- 34 програмируеми входо-изхода

- 12-битов аналогово-цифров преобразувателен модул (до 18 канала)

- 8-битов цифрово-аналогов преобразувател (2 канала)

- Капацитивни входове за сензори на допир (10 канала)

- **SPI**: [Serial Peripheral Interface](<https://en.wikipedia.org/wiki/Serial_Peripheral_Interface>) 4 интерфейса

- **I2S**: [Inter-IC Sound](https://en.wikipedia.org/wiki/I%C2%B2S) (2 интерфейса)

- **I2C**: [Inter-Integrated Circuit](https://en.wikipedia.org/wiki/I%C2%B2C) (2 интерфейса)

- **UART**: [Universal asynchronous receiver-transmitter](https://en.wikipedia.org/wiki/Universal_asynchronous_receiver-transmitter) (3 интерфейса, един от които през вграден USB преобразувател)

- **PWM**: [Pulse-width modulation](https://en.wikipedia.org/wiki/Pulse-width_modulation) (широчинно-импулсна модулация *ШИМ*, 16 канала)

- Вграден датчик на Хол ([сензор за магнитно поле](https://en.wikipedia.org/wiki/Hall_effect_sensor))

- **3.3V** работно напрежение

![image](img/ESP32-30PIN-DEVBOARD.png)

<img src="img/ESP32-VROOM-32D-PINOUT.png" alt="Screenshot" style="zoom:33%;" />


  *ESP32-devBoard 30pins*
## Периферни модули

> Заложни периферни модули в ***ESP32-101-board***:

- Бутони – 2 броя
- Ротационен енкодер + бутон на остта
- RGB-светодиод
- Транзисторни цифрови изходи – 3 броя
- Аналогов джойстик (2 оси) + бутон
- Графичен OLED дисплей (128x64 пиксела, едноцветен)
- Температурен сензор
- Фотодиод
- Инфрачервен светодиод
- Инфрачервен приемник с демодулатор (38kHz)
- Пиезо-зумер
- Сензори за допир – 3 броя
- Жироскоп/акселерометър (3 оси)
- Допълнителна (външна) EEPROM памет (опция)
