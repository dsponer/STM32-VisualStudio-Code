# STM32-VisualStudio-Code
Запуск проекта на Windows, Linux, OSx 

За основы был взят материа: https://github.com/damogranlabs/VS-Code-STM32-IDE
Возникли проблемы на стадии сборки и debugging'a проекта 

1. пришлось изменить путь до компилятора в файле settings.json:
  "cortex-debug.armToolchainPath": "F:/VSARM/GNU MCU Eclipse/ARM Embedded GCC/8.2.1-1.7-20190524-0603/bin",
2. OpenOCD сервер не включился. Пришлось добавить:
  "cortex-debug.openocdPath": "F:/VSARM/GNU MCU Eclipse/OpenOCD/0.10.0-12-20190422-2015/bin/openocd.exe",
3. Сервер выдал timeout error
