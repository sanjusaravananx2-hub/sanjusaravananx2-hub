<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00d4aa,100:00b4d8&height=220&section=header&text=Sanjeev%20Kumar&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=Embedded%20Systems%20Engineer%20%7C%20Digital%20Design%20%7C%20FPGA%20%7C%20Firmware&descSize=16&descColor=cccccc&descAlignY=55&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="mailto:sanjeevsaravanakumarx1@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=00d4aa" alt="Email"/></a>
  <a href="https://linkedin.com/in/sanjeev-kumarx2"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00b4d8" alt="LinkedIn"/></a>
  <a href="https://github.com/sanjusaravananx2-hub"><img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=ffffff" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Location-Leeds,%20UK-0d1117?style=for-the-badge&logo=googlemaps&logoColor=00d4aa" alt="Location"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=00D4AA&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=MSc+Embedded+Systems+Engineering+%40+University+of+Leeds;FPGA+%7C+RTL+Design+%7C+ARM+Cortex+%7C+Real-Time+Systems" alt="Typing SVG" />
</p>

---

## `> whoami`

```c
typedef struct {
    char *name;
    char *degree;
    char *university;
    char *focus[];
} engineer_t;

engineer_t sanjeev = {
    .name       = "Sanjeev Kumar",
    .degree     = "MSc Embedded Systems Engineering (Predicted First Class)",
    .university = "University of Leeds — Graduating Sep 2026",
    .focus      = {
        "FPGA & Digital Design (Verilog HDL)",
        "ARM Cortex-M/A Firmware Development",
        "Hardware-Software Co-Design",
        "Real-Time Signal Processing",
        NULL
    }
};
```

---

## `> cat /proc/skills`

<table>
<tr>
<td width="50%">

### HDL & Digital Design
![Verilog](https://img.shields.io/badge/Verilog_HDL-00d4aa?style=flat-square&logo=v&logoColor=0d1117)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-00b4d8?style=flat-square&logo=v&logoColor=0d1117)
![RTL Design](https://img.shields.io/badge/RTL_Design-0d1117?style=flat-square&logoColor=00d4aa)
![FSM Design](https://img.shields.io/badge/FSM_Design-0d1117?style=flat-square)
![Testbench](https://img.shields.io/badge/Simulation_%26_Testbench-0d1117?style=flat-square)

### FPGA & ASIC Flow
![Quartus](https://img.shields.io/badge/Intel_Quartus_Prime-00b4d8?style=flat-square&logo=intel&logoColor=white)
![SignalTap](https://img.shields.io/badge/SignalTap_II-0d1117?style=flat-square)
![Timing Closure](https://img.shields.io/badge/Timing_Closure-0d1117?style=flat-square)
![ModelSim](https://img.shields.io/badge/ModelSim-0d1117?style=flat-square)

</td>
<td width="50%">

### Languages & Frameworks
![C](https://img.shields.io/badge/C-00d4aa?style=flat-square&logo=c&logoColor=0d1117)
![C++](https://img.shields.io/badge/C++-00b4d8?style=flat-square&logo=cplusplus&logoColor=0d1117)
![Python](https://img.shields.io/badge/Python-00d4aa?style=flat-square&logo=python&logoColor=0d1117)
![MATLAB](https://img.shields.io/badge/MATLAB/Simulink-00b4d8?style=flat-square&logo=mathworks&logoColor=white)

### Embedded Platforms
![STM32](https://img.shields.io/badge/STM32_(Cortex--M)-00d4aa?style=flat-square&logo=stmicroelectronics&logoColor=0d1117)
![Cyclone V](https://img.shields.io/badge/Cyclone_V_SoC_(Cortex--A9)-00b4d8?style=flat-square&logo=intel&logoColor=white)
![Pixhawk](https://img.shields.io/badge/Pixhawk_(PX4/NuttX)-0d1117?style=flat-square)

</td>
</tr>
</table>

### Protocols & Interfaces
<p>
  <img src="https://img.shields.io/badge/AXI4--Lite-00d4aa?style=for-the-badge&logoColor=0d1117" alt="AXI4-Lite"/>
  <img src="https://img.shields.io/badge/SPI-00b4d8?style=for-the-badge" alt="SPI"/>
  <img src="https://img.shields.io/badge/I2C-00d4aa?style=for-the-badge" alt="I2C"/>
  <img src="https://img.shields.io/badge/CAN_2.0B-00b4d8?style=for-the-badge" alt="CAN"/>
  <img src="https://img.shields.io/badge/UART-00d4aa?style=for-the-badge" alt="UART"/>
  <img src="https://img.shields.io/badge/PWM-00b4d8?style=for-the-badge" alt="PWM"/>
</p>

---

## `> ls ~/projects/`

### FPGA-Based Servo Motor Control System
> **Cyclone V DE1-SoC (5CSEMA5F31C6)** | Verilog HDL | Intel Quartus Prime 22.1

```
                          ┌─── Cyclone V DE1-SoC ────────────────────────────────┐
                          │                                                       │
    ┌──────────┐          │   FPGA Fabric (50 MHz)                                │
    │          │          │   ┌─────────┐  ┌──────────┐  ┌───────────┐            │
    │  Servo   │◄── PWM ──│───│ PWM Gen │◄─│Sweep FSM │  │ LCD       │            │
    │  Motor   │          │   │ 20-bit  │  │ multi-   │  │ ILI9341   │            │
    │          │          │   │ counter │  │ state    │  │ 16-bit    │            │
    └──────────┘          │   └─────────┘  └──────────┘  └───────────┘            │
                          │                                                       │
                          │   ┌──────────────────────────────────────┐             │
                          │   │ AXI4-Lite Slave                      │             │
                          │   │ ┌──────┐┌──────┐┌──────┐┌──────┐   │             │
                          │   │ │REG 0 ││REG 1 ││REG 2 ││REG 3 │   │             │
                          │   │ │Period ││Duty  ││Status││IRQ   │   │             │
                          │   │ └──┬───┘└──┬───┘└──┬───┘└──┬───┘   │             │
                          │   │    └───────┴───────┴───────┘        │             │
                          │   │         W1C IRQ → GIC SPI #72       │             │
                          │   └──────────────┬───────────────────────┘             │
                          │                  │ AXI4-Lite                           │
                          │   ┌──────────────▼──────────────────────┐              │
                          │   │  HPS ARM Cortex-A9                  │              │
                          │   │  Runtime PWM control via /dev/mem   │              │
                          │   └─────────────────────────────────────┘              │
                          └───────────────────────────────────────────────────────┘
```

<details>
<summary><b>RTL Module Breakdown</b></summary>

| Module | Lines | Description |
|:-------|:------|:------------|
| `pwm_generator.v` | ~180 | 20-bit counter, configurable period/duty, 50 Hz output |
| `sweep_fsm.v` | ~200 | Multi-state FSM driving sweep patterns across servo range |
| `lcd_driver.v` | ~280 | 16-bit parallel interface for ILI9341 (240x320), init sequence FSM |
| `axi4_lite_slave.v` | ~240 | 4-register map, write-strobe, read-back, W1C interrupt pending |

**Total: ~900 lines of synthesizable Verilog — zero IP cores, zero soft processors.**

</details>

- Full RTL flow: functional simulation → synthesis → P&R → timing closure at **50 MHz**
- On-chip validation using **SignalTap II** logic analyser
- AXI4-Lite slave with write-strobe handling, read-back, and IRQ-pending latch

---

### CAN Bus Sensor Fusion Platform
> **STM32F4 + Cyclone V SoC** | Verilog | CAN 2.0B | SPI | I2C | AXI4-Lite

```
  ┌─── STM32F4 Sensor Node ──────┐                    ┌─── Cyclone V DE1-SoC ─────────────────────┐
  │                               │                    │                                            │
  │  ┌────────┐    ┌──────────┐  │   CAN 2.0B         │  ┌─── FPGA Fabric ──────────────────────┐  │
  │  │MPU6050 ├─┐  │          │  │   500 kbps          │  │                                      │  │
  │  │6-axis  │ │  │ STM32F4  │  │  ┌──────────┐       │  │  ┌───────────┐    ┌──────────────┐   │  │
  │  │IMU     │ ├──► Cortex-M4├──┼──►MCP2515   ├─CANH──┼──►  │SPI Master │───►│CAN Frame     │   │  │
  │  └────────┘ │  │          │  │  │+TJA1050  ├─CANL──┼──►  │Controller │    │Parser        │   │  │
  │  ┌────────┐ │  │ ISR-driven  │  └──────────┘       │  │  └───────────┘    └──────┬───────┘   │  │
  │  │BMP280  ├─┘  │ bare-metal  │                     │  │                          │            │  │
  │  │Temp/   │    │ firmware │  │                     │  │               ┌──────────▼─────────┐  │  │
  │  │Pressure│    └──────────┘  │                     │  │               │ HW Timestamp       │  │  │
  │  └────────┘                  │                     │  │               │ + 8-Tap FIR Filter  │  │  │
  │                               │                    │  │               │ (pipelined,         │  │  │
  │  I2C @ 400kHz                │                    │  │               │  configurable coeff) │  │  │
  │  Timer ISR → 100Hz sampling  │                    │  │               └──────────┬───────────┘  │  │
  └───────────────────────────────┘                    │  │                          │ AXI4-Lite    │  │
                                                       │  └──────────────────────────┼──────────────┘  │
                                                       │                             │                 │
                                                       │  ┌──────────────────────────▼──────────────┐  │
                                                       │  │  HPS ARM Cortex-A9 (Linux)               │  │
                                                       │  │  ┌────────────────────────────────────┐  │  │
                                                       │  │  │ can_monitor — real-time dashboard   │  │  │
                                                       │  │  │ • mmap() FPGA regs @ 0xFF200000    │  │  │
                                                       │  │  │ • CSV logging with HW timestamps   │  │  │
                                                       │  │  │ • 7-seg display: frame stats       │  │  │
                                                       │  │  └────────────────────────────────────┘  │  │
                                                       │  └─────────────────────────────────────────┘  │
                                                       │                                               │
                                                       │  LEDs: CAN RX/TX/ERR    SW: filter config     │
                                                       └───────────────────────────────────────────────┘
```

<details>
<summary><b>FPGA Register Map (AXI4-Lite, base 0xFF200000)</b></summary>

| Offset | Name | Access | Description |
|:-------|:-----|:-------|:------------|
| `0x00` | STATUS | R | `[0]` frame_valid, `[1]` error, `[15:8]` error_count |
| `0x04` | CAN_ID | R | `[10:0]` Latest received CAN ID |
| `0x08` | CAN_DATA_LO | R | CAN data bytes `[3:0]` |
| `0x0C` | CAN_DATA_HI | R | CAN data bytes `[7:4]` |
| `0x10` | TIMESTAMP | R | 32-bit hardware timestamp (1 us resolution) |
| `0x14–0x1C` | ACCEL_RAW_X/Y/Z | R | Raw accelerometer (signed 16-bit) |
| `0x20–0x28` | ACCEL_FILT_X/Y/Z | R | FIR-filtered accelerometer (signed 32-bit) |
| `0x30` | FIR_COEFF | W | Write FIR coefficient (auto-increment, 8 taps) |
| `0x40` | FRAME_COUNT | R | Total CAN frames received |
| `0x44` | ERROR_COUNT | R | Total CAN errors detected |

</details>

<details>
<summary><b>CAN Message Protocol</b></summary>

| CAN ID | Payload | DLC | Rate |
|:-------|:--------|:----|:-----|
| `0x100` | Accel X, Y, Z (3 x int16) | 6 | 100 Hz |
| `0x101` | Gyro X, Y, Z (3 x int16) | 6 | 100 Hz |
| `0x102` | Temperature (int16) + Pressure (uint32) | 6 | 10 Hz |
| `0x1FF` | Frame counter (uint16) + Uptime (uint32) | 6 | 1 Hz |

All standard 11-bit CAN IDs @ 500 kbps.

</details>

- Custom Verilog IP: SPI master, CAN frame parser, 8-tap pipelined FIR filter — **90% latency reduction** vs software
- Heterogeneous SoC pipeline with HW timestamping — **35% throughput improvement**
- Full 2-node CAN 2.0B network with real hardware-accelerated signal processing

---

### AI-Driven Thermal Prediction for EV Inverter Power Modules
> **MSc Dissertation — In Progress** | STM32 | Embedded C | Python | MATLAB/Simulink

```
  ┌─── MATLAB/Simulink Modelling ──────────────────────────────────────────────┐
  │                                                                             │
  │   SPWM Inverter Model          Foster RC Thermal Network                   │
  │   ┌───────────────┐            ┌───┐ ┌───┐ ┌───┐ ┌───┐                   │
  │   │ 600V DC Bus   │   Ploss    │R1 │ │R2 │ │R3 │ │R4 │    Tj             │
  │   │ 10 kHz SPWM   ├──────────► │C1 │►│C2 │►│C3 │►│C4 │──► (junction     │
  │   │ 35A peak      │            │   │ │   │ │   │ │   │    temperature)   │
  │   └───────────────┘            └───┘ └───┘ └───┘ └───┘                   │
  │                                 4-layer thermal network                    │
  │                                 Validated ±3–5°C vs datasheet              │
  └─────────────────────────────────────────┬──────────────────────────────────┘
                                            │ Training data
                                            ▼
  ┌─── Edge ML Deployment ─────────────────────────────────────────────────────┐
  │                                                                             │
  │   ┌──────────────┐    X-CUBE-AI     ┌──────────────────────────┐           │
  │   │ Trained       │   / CMSIS-NN     │ STM32 Cortex-M           │           │
  │   │ Regression    ├────────────────► │ ┌──────────────────────┐ │           │
  │   │ Model         │   quantised      │ │ Lightweight inference │ │           │
  │   └──────────────┘   int8/float16    │ │ < 1 ms per prediction │ │           │
  │                                       │ │ 95%+ faster than sim  │ │           │
  │                                       │ └──────────────────────┘ │           │
  │                                       └──────────────────────────┘           │
  └─────────────────────────────────────────────────────────────────────────────┘
```

- Coupled electrothermal IGBT model (10 kHz SPWM, 600V DC, 35A peak) with 4-layer Foster RC network
- Validated within **±3–5°C** of datasheet references
- Deploying lightweight ML model on STM32 via X-CUBE-AI/CMSIS-NN — **95%+ latency reduction**

---

### STM32 USB Signal Analyser
> **STM32 + USB** | Embedded C | Real-Time Capture

```
    Analog/Digital         ┌─── STM32 MCU ───────────────────┐        Host PC
    Signal Input           │                                  │
   ─────────────►  GPIO/   │  ┌──────────┐   ┌────────────┐  │  USB   ┌──────────┐
                   ADC ────┼──► Capture   ├──►│ Ring Buffer │──┼───────►│ Analysis │
                           │  │ Engine    │   │ + DMA      │  │  CDC   │ Software │
                           │  │ (ISR/DMA) │   └────────────┘  │        └──────────┘
                           │  └──────────┘                    │
                           │  Timer-triggered sampling        │
                           │  Configurable sample rate        │
                           └──────────────────────────────────┘
```

- Real-time signal capture using DMA + timer-triggered ADC sampling
- USB CDC interface for high-throughput data transfer to host
- Ring buffer architecture for zero-copy continuous acquisition

---

## `> cat /proc/mcu/pinout`

```
            ╔═══════════════════════════════════════════════════════════╗
            ║              STM32F4 — My Go-To MCU                      ║
            ╠═══════════════════════════════════════════════════════════╣
            ║                                                           ║
            ║   PA0  ○──── ADC_IN0 (signal capture)                    ║
            ║   PA5  ○──── SPI1_SCK  ──► MCP2515 (CAN controller)     ║
            ║   PA6  ○──── SPI1_MISO ◄── MCP2515                      ║
            ║   PA7  ○──── SPI1_MOSI ──► MCP2515                      ║
            ║   PA9  ○──── USART1_TX ──► Debug console                 ║
            ║   PA10 ○──── USART1_RX ◄── Debug console                 ║
            ║   PA11 ○──── USB_DM    ──► Host PC (CDC)                 ║
            ║   PA12 ○──── USB_DP    ──► Host PC (CDC)                 ║
            ║   PB4  ○──── SPI1_CS   ──► MCP2515 (active low)         ║
            ║   PB6  ○──── I2C1_SCL  ──► MPU6050 / BMP280             ║
            ║   PB7  ○──── I2C1_SDA  ◄─► MPU6050 / BMP280             ║
            ║   PB8  ○──── TIM4_CH3  ──► PWM output                    ║
            ║   PC13 ○──── GPIO_INT  ◄── MCP2515 /INT (CAN RX ready)  ║
            ║                                                           ║
            ║   Cortex-M4 @ 84/100 MHz  │  FPU  │  128–512 KB Flash   ║
            ║   NVIC: nested vectored interrupts for real-time tasks    ║
            ╚═══════════════════════════════════════════════════════════╝
```

---

## `> cat /sys/bus/memory_map`

```
  ┌────────────────────────────────────────────────────────────────────┐
  │                 Cyclone V SoC Memory Map                           │
  │                                                                    │
  │  0x0000_0000 ┌──────────────────────┐                             │
  │              │  SDRAM (HPS DDR3)     │  1 GB                      │
  │              │  Linux kernel + apps  │                             │
  │  0x3FFF_FFFF └──────────────────────┘                             │
  │                                                                    │
  │  0xC000_0000 ┌──────────────────────┐                             │
  │              │  FPGA Slaves          │  Lightweight HPS-to-FPGA   │
  │              │  (directly mapped)    │                             │
  │  0xFBFF_FFFF └──────────────────────┘                             │
  │                                                                    │
  │  0xFF20_0000 ┌──────────────────────┐                             │
  │              │  Lightweight Bridge   │  Custom AXI4-Lite slaves   │
  │              │  ├─ 0x00: STATUS      │  CAN sensor fusion regs    │
  │              │  ├─ 0x04: CAN_ID      │                             │
  │              │  ├─ 0x08: DATA_LO     │                             │
  │              │  ├─ 0x20: ACCEL_FILT  │                             │
  │              │  └─ 0x30: FIR_COEFF   │                             │
  │  0xFF3F_FFFF └──────────────────────┘                             │
  │                                                                    │
  │  0xFFD0_0000 ┌──────────────────────┐                             │
  │              │  HPS Peripherals      │  UART, SPI, I2C, GPIO      │
  │  0xFFFF_FFFF └──────────────────────┘                             │
  └────────────────────────────────────────────────────────────────────┘
```

---

## `> cat /etc/experience`

| Role | Organisation | Period |
|:-----|:------------|:-------|
| **Avionics & Propulsion Engineer** | Gryphon Arrows (IMechE UAS Challenge) | Oct 2025 — Present |
| **Vehicle Dynamics Engineer** | Leeds Gryphon Racing (Formula Student EV) | Oct 2025 — Present |
| **Embedded Systems Engineer** (Industrial Training) | InTrainz, India | Feb 2024 — Sep 2024 |

---

## `> cat /etc/education`

| Degree | Institution | Period |
|:-------|:-----------|:-------|
| **MSc Embedded Systems Engineering** (Predicted First Class) | University of Leeds | 2025 — 2026 |
| **B.Eng Electronics & Communication** (First Class with Distinction) | Sathyabama Institute, Chennai | 2021 — 2025 |

---

## `> cat /etc/certifications`

<p>
  <img src="https://img.shields.io/badge/UK_Amateur_Radio_Foundation_Licence_(M7KVD)-00d4aa?style=flat-square&logo=radio&logoColor=0d1117" alt="Radio"/>
  <img src="https://img.shields.io/badge/GE_Aerospace_Electrical_Engineering_Sim-00b4d8?style=flat-square&logo=ge&logoColor=white" alt="GE"/>
  <img src="https://img.shields.io/badge/Power_Electronics_(Univ._Colorado_Boulder)-00d4aa?style=flat-square&logo=coursera&logoColor=0d1117" alt="Power Electronics"/>
  <img src="https://img.shields.io/badge/MATLAB_Onramp_(MathWorks)-00b4d8?style=flat-square&logo=mathworks&logoColor=white" alt="MATLAB"/>
</p>

---

## `> top -b | head`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sanjusaravananx2-hub&show_icons=true&theme=react&bg_color=0d1117&title_color=00d4aa&icon_color=00b4d8&text_color=c9d1d9&border_color=30363d&hide_border=false" height="180"/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=sanjusaravananx2-hub&theme=react&background=0d1117&ring=00d4aa&fire=00d4aa&currStreakLabel=00d4aa&sideLabels=c9d1d9&dates=8b949e&border=30363d" height="180"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanjusaravananx2-hub&layout=compact&theme=react&bg_color=0d1117&title_color=00d4aa&text_color=c9d1d9&border_color=30363d&langs_count=8" height="160"/>
</p>

---

## `> tail -f /var/log/activity.log`

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sanjusaravananx2-hub&theme=react-dark&bg_color=0d1117&color=00d4aa&line=00b4d8&point=ffffff&area=true&area_color=00d4aa&hide_border=false" width="95%"/>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00d4aa,100:00b4d8&height=120&section=footer" width="100%"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sanjusaravananx2-hub&style=for-the-badge&color=00d4aa&label=PROFILE+VIEWS" alt="Profile views"/>
</p>

<p align="center">
  <i>"The best interface between hardware and software is a well-defined register map."</i>
</p>
