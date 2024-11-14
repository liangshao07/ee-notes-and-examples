#macOS 硬件开发环境搭建

> 软件开发环境见：

- Arduino IDE
    - Arduino
    - ESP32
    - STM32
- STM32CubeIDE
- VSC（VS code）
    - PlatformIO
    - ESP-IDF
    - Remote - SSH
- Clion
- Thonny

# Arduino IDE

> Arduino 官方推出的专门用于，开发自家 Arduino 框架的 IDE，简单的配置环境、代码调试、上传烧录，非常适合初学者使用。
>
> 缺陷是，Arduino IDE 代码提示和补全能力弱，且 Arduino IDE 风格的项目，普遍项目分文件编写差，大多写在同一代码文件里。故而只适合学习和小项目（小项目的意思是你做的全部都算）使用。

- 官方下载：

## Arduino 开发环境

安装完软件后，首次打开，Arduino IDE 会自动下载 Arduino 开发板的环境依赖，耐心等待完成即可。

## ESP32 开发环境

三步走：

- 添加 ESP32 开发板
- 下载 ESP32 开发板
- 检验是否安装成功

## STM32 开发环境

三步走

- 添加 STM32 开发板
- 下载 STM32 开发板
- 检验是否安装成功

# STM32CubeIDE

> STM32CubeIDE 是 STM32 官方推出的 IDE，用于开发自家的 STM32 芯片，使用 STM32 官方最新的 STM32Cube 框架（HAL 库），与网络上 Keil5 开发使用的 STM32 标准库，同样能够开发 STM32，但是标准库已经被 STM32 停止更新，不再推崇。

- 官方下载：

全部默认，安装完成后，会出现安装依赖提示，跟随提示耐心安装即可。

# VSC（VS code）



## PlatformIO



## ESP-IDF



## Remote - SSH



# Clion



## Clion STM32-STM32Cube

> 确保已经完成了 STM32CubeIDE 的安装。

## Clion 开发 ESP32



##PlatformIO



# Thonny

> Thonny 主要用于开发使用 MicroPython 框架的芯片（主要是 ESP32）。博主虽然只在少数时候使用此 IDE，不过它有时候，“只有它能做”，比如在使用 HomeAssistant 时，ESPHome 烧录 bin 时，使用它就非常便利。

- 官方下载：



