# ADC-NUCLEO-G474RE
This project is based on the article http://www.bepat.de/2020/11/27/stm32f103c8-adc-dual-regular-simultaneous-mode/

## Tests to-do
- Use a circular buffer to store ADC readings and export it through the serial comm (printf)
- Use a hardware timer (TIM) to trigger the ADC (trying to reach fsample = 50 kHz)