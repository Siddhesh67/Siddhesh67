<div align="center">

# Siddhesh Saraf

**Embedded Firmware Engineer · MS ECE @ Rutgers (GPA 3.9)**

![Status](https://img.shields.io/badge/Open_to_roles-May_2026-brightgreen?style=flat-square)
![OPT](https://img.shields.io/badge/OPT%2FSTEM--OPT-Authorized-blue?style=flat-square)

*I build real-time embedded firmware, from bare-metal register-level drivers to RTOS-based multi-task systems. I care about timing determinism, thread safety, and production-grade reliability.*

</div>

---

### 🔩 Tech Stack

![ARM](https://img.shields.io/badge/ARM_Cortex--M4-0C447C?style=flat-square&logo=arm&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-085041?style=flat-square)
![C](https://img.shields.io/badge/C-3C3489?style=flat-square&logo=c&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-003399?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-grey?style=flat-square)
![Python](https://img.shields.io/badge/Python-3572A5?style=flat-square&logo=python&logoColor=white)

**Protocols:** I2C · SPI · UART · DMA · Interrupts  
**Debug:** Logic Analyzer · Oscilloscope · JTAG/SWD · GDB  
**Tools:** STM32CubeIDE · STM32CubeProgrammer · QEMU

---

### 🚀 Featured Projects

#### [FreeRTOS Multi-Task IMU System](https://github.com/Siddhesh67/freertos-imu-stm32)
Preemptive multitasking firmware on STM32 Nucleo F401RE — 4 concurrent tasks at defined priorities with inter-task queues, mutex-protected UART, and 100 Hz Kalman filter sensor fusion.
- Mutex-guarded shared peripheral bus across tasks — no data races
- IWDG watchdog + stack high-water mark monitoring for fault recovery
- Kalman filter tuned for roll/pitch @ 100 Hz on Cortex-M4 FPU

`C` `FreeRTOS` `STM32` `I2C` `Kalman Filter` `Mutexes` `IWDG`

---

#### [MPU6050 Bare-Metal Sensor Fusion](https://github.com/Siddhesh67/STM32-IMU-Sensor-Fusion)
Bare-metal firmware with no HAL abstraction for core sensor logic. Direct register-level I2C driver with real-time roll/pitch estimation via Kalman filter.
- Wrote I2C driver at register level — no STM32 HAL dependency
- Demonstrates deep understanding of I2C timing, ACK/NACK, and clock stretching

`C` `Bare-Metal` `STM32` `I2C` `Kalman Filter` `UART`

---

#### [Negative Voltage Generator](https://github.com/Siddhesh67/negative-voltage-generator-verilog)
Verilog implementation of a negative voltage generator with two submodules: a charge pump for voltage inversion and a current mirror for stable biasing. Verified across three testbenches covering zero-delay, real-world timing delays, and transistor state transitions.
- Modular design — charge pump and current mirror developed and tested independently before integration
- Three testbenches with VCD output, viewed in GTKWave for waveform analysis
- Simulated with Icarus Verilog (`iverilog` + `vvp`)

`Verilog` `Digital Design` `Charge Pump` `Current Mirror` `GTKWave` `Icarus Verilog`

---

### 📡 Currently Building Toward

- **CAN bus** — automotive embedded protocols (ISO 11898)
- **Linux kernel drivers** — character device + I2C driver on Raspberry Pi *(in progress)*
- **MISRA-C** — safety-critical firmware coding standards
- **Unity/CMock** — unit testing embedded C with mocking



### 📬 Reach Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Siddhesh_Saraf-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siddhesh-saraf-034364229/)
[![Email](https://img.shields.io/badge/Email-siddheshsaraf2002@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:siddheshsaraf2002@gmail.com)
