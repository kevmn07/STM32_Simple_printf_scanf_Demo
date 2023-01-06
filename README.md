# STM32 Demos from Eugene Kalosha.

## Simple printf/scanf functions implementation for the Nucleo-G491RE evaluation board.

STM32CubeIDE ver. 1.11.0 used to build the Demo. 
VCP UART port is dedicated to the data transfer, see the board user manual.
- Port setting
  BaudRate : 115200 bps
  Length   : 8 bits
  StopBits : 1 bit
  Parity   : None

- Maximal length of the transmitted string : 63 chars.

__This is the simplest and most portable implementation, but it has major drawbacks and cannot be recommended for commercial applications.
Use this software at your own risk, no support, help, or comments are provided now or in the future.__

You are welcome to email kevmn07@gmail.com to report a bug, suggest improvements to the current Demo, or request a more reliable and fully documented version.
However, no obligation to respond.

## References:
1. [STM32G4 Nucleo-64 boards User Manual](https://www.st.com/resource/en/user_manual/dm00556337-stm32g4-nucleo64-boards-mb1367-stmicroelectronics.pdf)
2. [How to redirect the printf function to a UART for Debug messages](https://community.st.com/s/article/how-to-redirect-the-printf-function-to-a-uart-for-debug-messages)
3. [Easily use printf on STM32](https://forum.digikey.com/t/easily-use-printf-on-stm32/20157)
4. [Easily use scanf on STM32](https://forum.digikey.com/t/easily-use-scanf-on-stm32/21103)
