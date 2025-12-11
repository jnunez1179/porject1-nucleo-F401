# porject1-nucleo-F401

This repository contains a progressively constructed firmware framework
for the STM32F401RE Nucleo board.

Stage 0: Environment setup  
Stage 1: SysTick-based delay  
Stage 2: Cooperative scheduler  
Stage 3: Button EXTI interrupt + debounce  
Stage 4: UART driver + CLI  
Stage 5: Modular driver libraries  
Stage 6: Documentation + testing  
Stage 7: Bare-metal register research

STM32F401 Data Sheet: https://www.st.com/resource/en/datasheet/stm32f401re.pdf
Reference Manual: https://www.st.com/resource/en/reference_manual/rm0368-stm32f401xbc-and-stm32f401xde-advanced-armbased-32bit-mcus-stmicroelectronics.pdf
Nucleo User Guide: https://www.st.com/resource/en/user_manual/um1724-stm32-nucleo64-boards-mb1136-stmicroelectronics.pdf
