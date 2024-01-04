# Tracker_STM32
Tx and Rx module for tracking lost rockens.

*****************************************************************************************************************************

<b>HARDWARE</b>

STM32WL microcontrollers:
https://www.st.com/en/microcontrollers-microprocessors/stm32wl-series.html

Selected MCU:
STMicroelectronics STM32WLE5CCU6 (single core)

MCU STM32WLEx - Documentation
\Documentation\STM32WLEx\
https://www.st.com/en/microcontrollers-microprocessors/stm32wlex/documentation.html

STLINK-V3 modular in-circuit debugger and programmer for STM32/STM8:
https://www.st.com/en/development-tools/stlink-v3set.html
Mouser: https://www.mouser.se/ProductDetail/STMicroelectronics/STLINK-V3SET?qs=sGAEpiMZZMuqBwn8WqcFUj2aNd7i9W7uzHMzYy6qD5f5R5n3HCQ2Rg%3D%3D

Dev-board NUCLEO-WL55JC2, similiar MCU (STM32WL55JC) for prototyping:
\IO-board_Nucleo-WL5JC2\
https://www.st.com/en/evaluation-tools/nucleo-wl55jc.html#overview
Buy from Mouser (no external programer required): https://www.mouser.se/ProductDetail/STMicroelectronics/NUCLEO-WL55JC2?qs=%252B6g0mu59x7KaOy%2FAefj%252BRg%3D%3D

PCB design with KiCAD:
\KiCad\STM32_tracker\

Manufacturer of PCB, JLCPCB:
https://m.jlcpcb.com/more/componentDetail?componentCode=C2888218


*****************************************************************************************************************************

<b>DEVELOPMENT</b>

Recommended IDE, STM32CubeIDE (Eclipse):
https://www.st.com/en/development-tools/stm32cubeide.html

STM32Cube MCU Package for STM32WL series (HAL, Low-Layer APIs and CMSIS, File system, RTOS, KMS, Secure Engine, Sub-GHz Phy, LoRaWAN and Sigfox stacks - and examples running on ST boards):
\Documentation\STM32CubeWL_HAL_LL\
https://www.st.com/en/embedded-software/stm32cubewl.html


*****************************************************************************************************************************

<b>GETTING STARTED</b>
IDE:
1. Download STM32CubeIDE
2. Download STM32Cube MCU Package for STM32WL series (from URL or through IDE)
3. Log in to STM in the IDE (right most top-menu).
4. Start a new project and select WL55JC2 under BOARDS.
5. Find example projects under the STM32Cube_FW_WL_n firmware package folder (see info to path below)
Read:
1. IDE STM32cubeWL: \Documentation\STM32CubeWL_HAL_LL\um2643-getting-started-with-stm32cubewl-for-stm32wl-series-stmicroelectronics.pdf
2. Dev-board NUCLEO-WL55JC: \IO-board_Nucleo-WL5JC2\Documentation\User-Manual_STM_NUCLEO-WL55JC.pdf
3. Online video training: https://youtube.com/playlist?list=PLnMKNibPkDnGnd25b995A5xzV7gUnC1NP&si=fuwf-YcDqdPsEJno


*****************************************************************************************************************************

<b>STM32Cube_FW_WL_V1.3.0</b>
MAC local path to firmware package and documentation with examples
/System/Volumes/Data/Users/peter/STM32Cube/Repository/STM32Cube_FW_WL_V1.3.0
Windows: in the IDE go to Window - Preferences - STM32CUBE - Firmware Updater - Repository Setup.
