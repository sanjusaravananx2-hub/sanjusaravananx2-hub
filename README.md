<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00d4aa,100:00b4d8&height=230&section=header&text=Sanjeev%20Kumar&fontSize=44&fontColor=ffffff&fontAlignY=32&desc=Embedded%20Systems%20Engineer%20%E2%80%A2%20FPGA%20%E2%80%A2%20RTL%20Design%20%E2%80%A2%20ARM%20Cortex%20%E2%80%A2%20Firmware&descSize=15&descColor=c9d1d9&descAlignY=52&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="mailto:sanjeevsaravanakumarx1@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=00d4aa" alt="Email"/></a>&nbsp;
  <a href="https://linkedin.com/in/sanjeev-kumarx2"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00b4d8" alt="LinkedIn"/></a>&nbsp;
  <a href="https://github.com/sanjusaravananx2-hub"><img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=ffffff" alt="GitHub"/></a>&nbsp;
  <img src="https://img.shields.io/badge/Leeds,%20UK-0d1117?style=for-the-badge&logo=googlemaps&logoColor=00d4aa" alt="Location"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=00D4AA&center=true&vCenter=true&repeat=true&width=620&height=30&lines=MSc+Embedded+Systems+Engineering+%40+Leeds;FPGA+%7C+Verilog+RTL+%7C+ARM+Cortex+%7C+Real-Time+Systems;900%2B+lines+of+synthesizable+Verilog+%E2%80%94+no+IP+cores;Hardware-software+co-design+on+heterogeneous+SoCs" alt="Typing SVG" />
</p>

<br>

## `> whoami`

```c
#define ENGINEER "Sanjeev Kumar"

typedef struct {
    const char *name;
    const char *degree;
    const char *university;
    const char *graduation;
    const char *focus[5];
} embedded_engineer_t;

static const embedded_engineer_t me = {
    .name       = ENGINEER,
    .degree     = "MSc Embedded Systems Engineering",
    .university = "University of Leeds",
    .graduation = "September 2026 (Predicted First Class)",
    .focus      = {
        "FPGA & Digital Design (Verilog HDL)",
        "ARM Cortex-M/A Firmware (bare-metal & RTOS)",
        "Hardware-Software Co-Design on SoC",
        "Real-Time Signal Processing & Edge AI",
        NULL
    }
};
```

<br>

## `> cat /proc/skills`

<table>
<tr><td>

**HDL & Digital Design**

![Verilog](https://img.shields.io/badge/Verilog_HDL-00d4aa?style=for-the-badge&logoColor=0d1117)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-00b4d8?style=for-the-badge&logoColor=0d1117)
![RTL](https://img.shields.io/badge/RTL_Design-0d1117?style=for-the-badge)
![FSM](https://img.shields.io/badge/FSM_Design-0d1117?style=for-the-badge)

**FPGA & EDA Tools**

![Quartus](https://img.shields.io/badge/Intel_Quartus_Prime-00b4d8?style=for-the-badge&logo=intel&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-0d1117?style=for-the-badge)
![SignalTap](https://img.shields.io/badge/SignalTap_II-0d1117?style=for-the-badge)

</td><td>

**Languages**

![C](https://img.shields.io/badge/C-00d4aa?style=for-the-badge&logo=c&logoColor=0d1117)
![C++](https://img.shields.io/badge/C++-00b4d8?style=for-the-badge&logo=cplusplus&logoColor=0d1117)
![Python](https://img.shields.io/badge/Python-00d4aa?style=for-the-badge&logo=python&logoColor=0d1117)
![MATLAB](https://img.shields.io/badge/MATLAB-00b4d8?style=for-the-badge&logo=mathworks&logoColor=white)

**Embedded Platforms**

![STM32](https://img.shields.io/badge/STM32_Cortex--M-00d4aa?style=for-the-badge&logo=stmicroelectronics&logoColor=0d1117)
![CycloneV](https://img.shields.io/badge/Cyclone_V_SoC-00b4d8?style=for-the-badge&logo=intel&logoColor=white)
![Pixhawk](https://img.shields.io/badge/PX4_NuttX-0d1117?style=for-the-badge)

</td></tr>
</table>

<p align="center">
  <img src="https://img.shields.io/badge/AXI4--Lite-00d4aa?style=for-the-badge" alt="AXI4-Lite"/>
  <img src="https://img.shields.io/badge/SPI-00b4d8?style=for-the-badge" alt="SPI"/>
  <img src="https://img.shields.io/badge/I2C-00d4aa?style=for-the-badge" alt="I2C"/>
  <img src="https://img.shields.io/badge/CAN_2.0B-00b4d8?style=for-the-badge" alt="CAN"/>
  <img src="https://img.shields.io/badge/UART-00d4aa?style=for-the-badge" alt="UART"/>
  <img src="https://img.shields.io/badge/PWM-00b4d8?style=for-the-badge" alt="PWM"/>
  <img src="https://img.shields.io/badge/DMA-00d4aa?style=for-the-badge" alt="DMA"/>
  <img src="https://img.shields.io/badge/USB_CDC-00b4d8?style=for-the-badge" alt="USB"/>
</p>

<br>

## `> ls ~/projects/`

---

### <img src="https://img.shields.io/badge/01-00d4aa?style=for-the-badge" alt="01"/> FPGA Servo Motor Control System

> `Cyclone V DE1-SoC` | `Verilog HDL` | `Quartus Prime 22.1` | `50 MHz`

```
              CYCLONE V DE1-SoC
    ==========================================

    +-------------+      +-------------+
    |  PWM Gen    |<-----| Sweep FSM   |
    |  20-bit ctr |      | multi-state |
    |  50 Hz out  |      +-------------+
    +------+------+
           |               +-------------+
           v               | LCD Driver  |
      [Servo Motor]        | ILI9341     |
                           | 240x320 px  |
                           +-------------+

    +------------------------------------+
    |  AXI4-Lite Slave (4 registers)     |
    |                                    |
    |  REG0: Period   REG1: Duty Cycle   |
    |  REG2: Status   REG3: IRQ (W1C)   |
    |                                    |
    |  IRQ Pending --> GIC SPI #72       |
    +-----------------+------------------+
                      | AXI4-Lite Bus
                      v
    +------------------------------------+
    |  HPS ARM Cortex-A9                 |
    |  Runtime control via /dev/mem      |
    +------------------------------------+

    ==========================================
```

<details>
<summary><b>RTL Module Breakdown (click to expand)</b></summary>

| Module | Lines | Function |
|:-------|------:|:---------|
| `pwm_generator.v` | 180 | 20-bit counter, configurable period & duty, 50 Hz |
| `sweep_fsm.v` | 200 | Multi-state FSM, sweep patterns across servo range |
| `lcd_driver.v` | 280 | ILI9341 16-bit parallel, init FSM, real-time gauge |
| `axi4_lite_slave.v` | 240 | 4-register map, write-strobe, W1C interrupt |
| **Total** | **900** | **Zero IP cores. Zero soft processors.** |

</details>

**Key achievements:**
- Full RTL flow: simulation ➜ synthesis ➜ P&R ➜ timing closure at **50 MHz**
- On-chip validation with **SignalTap II** logic analyser
- AXI4-Lite slave with write-strobe, read-back, and W1C IRQ latch

---

### <img src="https://img.shields.io/badge/02-00b4d8?style=for-the-badge" alt="02"/> CAN Bus Sensor Fusion Platform

> `STM32F4` | `Cyclone V SoC` | `Verilog` | `CAN 2.0B` | `AXI4-Lite`

```
  NODE 1: STM32F4                NODE 2: CYCLONE V SoC
  ====================           ==============================

  +--------+                     FPGA FABRIC
  |MPU6050 |--+                  +---------------------------+
  |6-axis  |  |  I2C             |                           |
  +--------+  |  400kHz          |  SPI Master Controller    |
              +-->+----------+   |      |                    |
  +--------+     |  STM32   |   |      v                    |
  |BMP280  |---->| Cortex-M4|   |  CAN Frame Parser         |
  |Temp/Prs|     |          |   |      |                    |
  +--------+     | ISR-based|   |      v                    |
                 | bare-    |   |  8-Tap FIR Filter         |
                 | metal    |   |  (pipelined, configurable)|
                 +----+-----+   |      |                    |
                      |         |  HW Timestamp Generator   |
                      v         +------------+--------------+
                 +----------+                |
                 | MCP2515  |   AXI4-Lite    |
                 | TJA1050  |   Bus Bridge   |
                 +----+-----+                v
                      |         +---------------------------+
              CAN Bus |         | HPS ARM Cortex-A9 (Linux) |
              500kbps |         |                           |
              CANH ---+-------->| can_monitor application   |
              CANL ---+-------->| mmap() @ 0xFF200000       |
                                | CSV logging + 7-seg stats |
                                +---------------------------+
```

<details>
<summary><b>FPGA Register Map — base 0xFF200000 (click to expand)</b></summary>

| Offset | Register | R/W | Description |
|:-------|:---------|:---:|:------------|
| `0x00` | STATUS | R | `[0]` frame_valid `[1]` error `[15:8]` err_count |
| `0x04` | CAN_ID | R | `[10:0]` Latest CAN ID |
| `0x08` | DATA_LO | R | CAN bytes `[3:0]` |
| `0x0C` | DATA_HI | R | CAN bytes `[7:4]` |
| `0x10` | TIMESTAMP | R | 32-bit HW timestamp (1 us) |
| `0x14` | ACCEL_RAW | R | Raw accel X/Y/Z (int16) |
| `0x20` | ACCEL_FILT | R | FIR-filtered accel (int32) |
| `0x30` | FIR_COEFF | W | Coefficient write (auto-incr, 8 taps) |
| `0x40` | FRAME_CNT | R | Total frames received |
| `0x44` | ERROR_CNT | R | Total errors detected |

</details>

<details>
<summary><b>CAN Message Protocol (click to expand)</b></summary>

| CAN ID | Payload | DLC | Rate |
|:-------|:--------|:---:|:-----|
| `0x100` | Accel X/Y/Z (3 x int16) | 6 | 100 Hz |
| `0x101` | Gyro X/Y/Z (3 x int16) | 6 | 100 Hz |
| `0x102` | Temp (int16) + Press (uint32) | 6 | 10 Hz |
| `0x1FF` | Frame count + Uptime | 6 | 1 Hz |

All standard 11-bit IDs @ 500 kbps

</details>

**Key achievements:**
- Custom Verilog IP blocks — **90% signal-processing latency reduction** vs software
- HW timestamping + FPGA-to-HPS pipeline — **35% data throughput improvement**
- Full 2-node CAN 2.0B network with real hardware

---

### <img src="https://img.shields.io/badge/03-00d4aa?style=for-the-badge" alt="03"/> AI Thermal Prediction — EV Inverter

> `MSc Dissertation` | `STM32` | `MATLAB/Simulink` | `Edge AI`

```
  MODELLING STAGE                  DEPLOYMENT STAGE
  ===================              =======================

  SPWM Inverter Model              Trained Model
  +------------------+             +------------------+
  | 600V DC bus      |             | Regression Model |
  | 10 kHz switching |  Ploss      |                  |
  | 35A peak current |---->+       +--------+---------+
  +------------------+     |                |
                           v                | X-CUBE-AI
  Foster RC Network        |                | CMSIS-NN
  +---+  +---+  +---+  +---+               | quantised
  |R1 |->|R2 |->|R3 |->|R4 |               v
  |C1 |  |C2 |  |C3 |  |C4 |      +------------------+
  +---+  +---+  +---+  +---+      | STM32 Cortex-M   |
       |                           |                  |
       +--> Tj (junction temp)     | < 1ms inference  |
            +/- 3-5C accuracy      | 95%+ faster      |
                                   +------------------+
```

**Key achievements:**
- 4-layer Foster RC thermal network validated **±3–5°C** vs datasheet
- Edge deployment on STM32 via X-CUBE-AI — **95%+ inference latency reduction**
- Bridging physics-based modelling with embedded ML

---

### <img src="https://img.shields.io/badge/04-00b4d8?style=for-the-badge" alt="04"/> STM32 USB Signal Analyser

> `STM32F411` | `Bare-metal C` | `USB CDC` | `DMA` | `Python Host`

```
  Signal In        STM32F411 Black Pill         Host PC
  =========        ========================     ============

                   +----------------------+
  Analog/   ADC    | Capture Engine       |     +---------+
  Digital --+----->| (Timer-triggered     | USB | Python  |
  Signal    |      |  ISR + DMA)          | CDC | FFT     |
            |      |         |            |---->| Analysis|
            |      |         v            |     | Tool    |
            |      | Ring Buffer          |     +---------+
            |      | (zero-copy, double-  |
            |      |  buffered DMA xfer)  |
            |      +----------------------+
            |
            |      Configurable sample rate
            +----> up to 2.4 MSPS (12-bit)
```

**Key achievements:**
- Real-time oscilloscope + FFT analyser on STM32
- DMA double-buffering for zero-copy continuous acquisition
- USB CDC streaming to Python host application

<br>

## `> cat /proc/mcu/pinout`

```
      STM32F4 PIN CONFIGURATION (across all projects)
     +================================================+
     |                                                  |
     |  PA0  o---- ADC_IN0 -----> Signal Capture        |
     |  PA5  o---- SPI1_SCK ----> MCP2515 CAN           |
     |  PA6  o---- SPI1_MISO <--- MCP2515 CAN           |
     |  PA7  o---- SPI1_MOSI ---> MCP2515 CAN           |
     |  PA9  o---- USART1_TX ---> Debug Console          |
     |  PA10 o---- USART1_RX <--- Debug Console          |
     |  PA11 o---- USB_DM ------> Host PC                |
     |  PA12 o---- USB_DP ------> Host PC                |
     |  PB4  o---- SPI1_CS -----> MCP2515 (/CS)          |
     |  PB6  o---- I2C1_SCL ----> MPU6050 + BMP280       |
     |  PB7  o---- I2C1_SDA <---> MPU6050 + BMP280       |
     |  PB8  o---- TIM4_CH3 ----> PWM Output             |
     |  PC13 o---- EXTI --------< MCP2515 /INT           |
     |                                                  |
     |  [Cortex-M4F @ 100MHz] [FPU] [512KB Flash]      |
     |  [NVIC] [DMA2] [12-bit ADC @ 2.4MSPS]           |
     +================================================+
```

<br>

## `> cat /sys/bus/memory_map`

```
    CYCLONE V SOC MEMORY MAP
    ========================================

    0x0000_0000  +--------------------+
                 | SDRAM (DDR3)       |
                 | 1 GB               |
                 | Linux + userspace  |
    0x3FFF_FFFF  +--------------------+

    0xC000_0000  +--------------------+
                 | FPGA Slaves        |
                 | (HPS-to-FPGA       |
                 |  bridge, 960 MB)   |
    0xFBFF_FFFF  +--------------------+

    0xFF20_0000  +--------------------+
                 | Lightweight Bridge |
                 | (custom registers) |
                 |  0x00 STATUS       |
                 |  0x04 CAN_ID       |
                 |  0x10 TIMESTAMP    |
                 |  0x20 ACCEL_FILT   |
                 |  0x30 FIR_COEFF    |
    0xFF3F_FFFF  +--------------------+

    0xFFD0_0000  +--------------------+
                 | HPS Peripherals    |
                 | UART SPI I2C GPIO  |
    0xFFFF_FFFF  +--------------------+
```

<br>

## `> cat /etc/experience`

| Role | Organisation | Period |
|:-----|:------------|:-------|
| **Avionics & Propulsion Engineer** | Gryphon Arrows — IMechE UAS Challenge | Oct 2025 — Present |
| **Vehicle Dynamics Engineer** | Leeds Gryphon Racing — Formula Student EV | Oct 2025 — Present |
| **Embedded Systems Engineer** (Industrial Placement) | InTrainz, India | Feb 2024 — Sep 2024 |

<br>

## `> cat /etc/education`

| Degree | Institution | Period |
|:-------|:-----------|:-------|
| **MSc Embedded Systems Engineering** (Predicted 1st) | University of Leeds | 2025 — 2026 |
| **B.Eng Electronics & Communication** (1st with Distinction) | Sathyabama Institute, Chennai | 2021 — 2025 |

<br>

## `> cat /etc/certs`

<p>
  <img src="https://img.shields.io/badge/UK_Amateur_Radio_M7KVD-00d4aa?style=for-the-badge&logo=radio&logoColor=0d1117" alt="Radio"/>
  <img src="https://img.shields.io/badge/GE_Aerospace_EE_Sim-00b4d8?style=for-the-badge&logo=ge&logoColor=white" alt="GE"/>
  <img src="https://img.shields.io/badge/Power_Electronics-00d4aa?style=for-the-badge&logo=coursera&logoColor=0d1117" alt="Power"/>
  <img src="https://img.shields.io/badge/MATLAB_Onramp-00b4d8?style=for-the-badge&logo=mathworks&logoColor=white" alt="MATLAB"/>
</p>

<br>

## `> top -b | head`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sanjusaravananx2-hub&show_icons=true&theme=react&bg_color=0d1117&title_color=00d4aa&icon_color=00b4d8&text_color=c9d1d9&border_color=30363d" height="180"/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=sanjusaravananx2-hub&theme=react&background=0d1117&ring=00d4aa&fire=00d4aa&currStreakLabel=00d4aa&sideLabels=c9d1d9&dates=8b949e&border=30363d" height="180"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanjusaravananx2-hub&layout=compact&theme=react&bg_color=0d1117&title_color=00d4aa&text_color=c9d1d9&border_color=30363d&langs_count=8" height="160"/>
</p>

<br>

## `> tail -f /var/log/activity.log`

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sanjusaravananx2-hub&theme=react-dark&bg_color=0d1117&color=00d4aa&line=00b4d8&point=ffffff&area=true&area_color=00d4aa&hide_border=false" width="95%"/>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00d4aa,100:00b4d8&height=120&section=footer" width="100%"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sanjusaravananx2-hub&style=for-the-badge&color=00d4aa&label=PROFILE+VIEWS" alt="views"/>
</p>

<p align="center">
  <i>"The best interface between hardware and software is a well-defined register map."</i>
</p>
