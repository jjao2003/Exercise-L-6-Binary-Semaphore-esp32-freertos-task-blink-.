📌 ESP32 FreeRTOS Task – Binary Semaphore + Static Argument Fix

This project demonstrates how to safely pass arguments to a FreeRTOS task on ESP32 without causing stack-based pointer errors. The LED blink delay is passed to the task using a static variable, ensuring memory remains valid after setup() exits.

The project runs entirely on Wokwi (no hardware required).
