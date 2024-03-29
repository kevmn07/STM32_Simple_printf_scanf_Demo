# STM32 Demos by EK

## Simple printf/scanf functions implementation for the Nucleo-G491RE evaluation board.

STM32CubeIDE ver. 1.11.0 used to build the Demo. 
VCP UART port is dedicated to the data transfer, see the board user manual.
Port setting
  BaudRate : 115200 bps
  Length   : 8 bits
  StopBits : 1 bit
  Parity   : None

Maximal length of the transmitted string : 63 chars.

This is the simplest and most portable implementation, but it has major drawbacks and cannot be recommended for commercial applications.
__Use this software at your own risk, no support, help, or comments are provided now or in the future.__

## References:

- https://www.st.com/resource/en/user_manual/dm00556337-stm32g4-nucleo64-boards-mb1367-stmicroelectronics.pdf
- https://community.st.com/s/article/how-to-redirect-the-printf-function-to-a-uart-for-debug-messages
- https://forum.digikey.com/t/easily-use-printf-on-stm32/20157
- https://forum.digikey.com/t/easily-use-scanf-on-stm32/21103

You are welcome to email <kevmn07@gmail.com> to report a bug, suggest improvements to the current Demo, or request a more reliable and fully documented commercial version.
However, no obligation to respond.

