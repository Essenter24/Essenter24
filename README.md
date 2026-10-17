## Hi there! 👋

Automatic Controls and Robotics student at Gdansk Tech, fascinated with Embedded Systems and with soft spot for programming. I'm focusing
on systems based on STM32 family, being eager to always develop an entire solution from scratch - from PCB to a fully working simple or more
advanced system.

Currently diving deep into STM32 territory, actively learning RTOS. As for pure software side, I'm focusing on learning Python and Rust.
I'm planning to lean towards the machine learning side of programming somewhere in the bright future.


## My projects 

#### STM32 Weather Station based on BME690 sensor (https://github.com/Essenter24/STM32-Weather-Station) - first embedded project
* Compact weather station based on STM32L476RG6 and LCD screen with own light driver
* KiCad-made PCB from scratch
* Main functions:
  - reading information about air humidity, temperature and pressure
  - manual or automatic (based on light level) LCD brightness control
  - UART communication and JSON data sending through LPUART

#### STM32 LED Heart (https://github.com/Essenter24/STM32-LED-Heart/tree/main)
* Heart composed of 16 red LEDs on heart-shaped developed by myself PCB with simple software PWM
* Several different illumination modes (with room for creating more in the future) toggled by button

## Currently working on

#### RTOS Port of STM32 Weather Station
* Setting up the entire logic on freeRTOS
* Adding Watchdog and Energy Saving features
* Adding air quality control

#### Controller for 3D Printer Filament Recycling System, based on STM32 
* Part of currently pending group project at my university
* Expected features are:
  - UART communication with PC or TFT touchscreen compatible with UART
  - software-sided PID controller with anti wind-up algorithm for precise heater control
  - handling of the various critical scenarios

#### Simple I2C OLED screen driver 
* Written from scratch, to be used in future projects
* Handling both non-DMA and DMA-assisted I2C communication with OLED


> In case of any questions or interest, feel free to message me on LinkedIN (https://www.linkedin.com/in/łukasz-garlicki-932779215/) or directly
> to my e-mail (lukasz24garlicki@gmail.com)!
