# stm32morse (Morse code transmitter )
# Task
- Modigy the blink to transmit 3 different letters representing 3 group members repeatedly

# Group 2
1) Zhang Zhen
2) Tian Linxue
3) Lim Zhi

# Steps
1) Create a new project in STM32CudeIDE
2) Select the correct board (STM32F103C8)
3) Define the on-board LED pin (PC-13) into GPIO_Output pin in Pinout & Configuration
4) Modify code inside the while loop (core/src/main.c)
5) Inside Core/src/main.c, long_press represent dashes while short_press represent dots in morse code.
6) Three letters that represent out group members are Z (Zhang Zhen), T (Tian Linxue) and L (Lim Zhi) is shows repeatly 
7) Build-in functions like HAL_GPIO_WritePin and HAL_Delay is used in this milestone. 

# References  
- https://morsecode.tools/
- https://github.com/martonbognar/stm32-morse
