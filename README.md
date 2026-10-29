# moonwake--feng

STM32F103xB ADC 工程，完整源码及配置位于 [adc/](adc/)。

- `adc/Core/`：应用代码、ADC、USART 和 GPIO 配置。
- `adc/Drivers/`：STM32 HAL 驱动和 CMSIS 库。
- `adc/adc.ioc`：STM32CubeMX 工程配置。
- `adc/CMakeLists.txt`、`adc/CMakePresets.json`、`adc/cmake/`：CMake 构建配置。
- `adc/EWARM/`：IAR Embedded Workbench 工程文件。

仓库根目录的 `.gitignore` 用于排除编译产物、本机 IDE 缓存等文件。
