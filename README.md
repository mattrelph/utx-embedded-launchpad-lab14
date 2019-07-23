# utx-embedded-launchpad-lab14
UTX Embedded - Lab 14 - Measurement of Distance

Purpose
This lab has these major objectives: 1) an introduction to sampling analog signals using the ADC interface; 2) the development of an ADC device driver; 3) learning data conversion and calibration techniques; 4) the use of fixed-point numbers, which are integers used to represent non-integer values; 5) the development of an interrupt-driven real-time sampling device driver; 6) the development of a software system involving multiple files; and 7) learn how to debug one module at a time.

System Requirements
In this lab you will design a distance meter. A linear slide potentiometer converts distance into resistance (0 ≤ R ≤ 10 kΩ). Your software will use the 12-bit ADC built into the microcontroller. The ADC will be sampled at 40 Hz using SysTick interrupts. You will write a C function that converts the ADC sample into distance, with units of 0.001 cm. That data stream will be passed from the ISR into the main program using a mailbox, and the main program will output the data on a display. The display is optional.

https://www.youtube.com/watch?v=URHdTlCaJ1o
