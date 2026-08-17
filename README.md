<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Sanjeev%20Kumar&fontSize=46&fontColor=ffffff&fontAlignY=32&desc=FPGA%20%E2%80%A2%20RTL%20Design%20%E2%80%A2%20Bare-Metal%20Firmware%20%E2%80%A2%20Hardware%2FSoftware%20Co-Design&descSize=15&descColor=c9d1d9&descAlignY=52&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="mailto:sanjusaravananx1@gmail.com"><img src="https://img.shields.io/badge/Email-0f0c29?style=for-the-badge&logo=gmail&logoColor=e06c75" alt="Email"/></a>&nbsp;
  <a href="https://linkedin.com/in/sanjeev-kumarx2"><img src="https://img.shields.io/badge/LinkedIn-0f0c29?style=for-the-badge&logo=linkedin&logoColor=61afef" alt="LinkedIn"/></a>&nbsp;
  <a href="https://github.com/sanjusaravananx2-hub"><img src="https://img.shields.io/badge/GitHub-0f0c29?style=for-the-badge&logo=github&logoColor=ffffff" alt="GitHub"/></a>&nbsp;
  <img src="https://img.shields.io/badge/Leeds,%20UK-0f0c29?style=for-the-badge&logo=googlemaps&logoColor=98c379" alt="Location"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3200&pause=900&color=C678DD&center=true&vCenter=true&repeat=true&width=780&height=30&lines=MSc+Embedded+Systems+Engineering+%40+University+of+Leeds;Verilog+RTL+taken+through+timing+closure+onto+real+silicon;Custom+FPGA+datapaths+%7C+no+vendor+IP%2C+no+soft+processor;I+quote+cycle+counts+because+I+measured+them" alt="Typing SVG"/>
</p>

<br>

## `> dmesg | grep flagship`

<p align="center">
  <img src="assets/datapath.svg" alt="CAN Sensor Fusion Platform datapath: STM32F4 over 500 kbps CAN into custom Verilog IP on the Cyclone V fabric, through a self-written AXI4-Lite slave to a Cortex-A9 running Linux" width="100%"/>
</p>

<br>

## `> whoami`

```c
typedef struct {
    const char *name;
    const char *degree;
    const char *university;
    const char *graduating;
    const char *focus[5];
} engineer_t;

static const engineer_t me = {
    .name       = "Sanjeev Kumar",
    .degree     = "MSc Embedded Systems Engineering",
    .university = "University of Leeds",
    .graduating = "September 2026 (Predicted Distinction)",
    .focus      = {
        "FPGA & digital design in Verilog / VHDL",
        "Testbench-driven verification, then silicon",
        "Bare-metal firmware on ARM Cortex-M",
        "Hardware-software co-design on heterogeneous SoC",
        NULL
    }
};
```

I work on the boundary between software and hardware, and I like the part where you
find out whether the thing you built actually behaves the way you claimed. Most of what
is here was built solo, from architecture through to a board on the desk.

<br>

## `> cat /proc/skills`

<table>
<tr><td width="50%" valign="top">

**HDL &amp; Digital Design**

![Verilog](https://img.shields.io/badge/Verilog_HDL-c678dd?style=for-the-badge&logoColor=fff)
![VHDL](https://img.shields.io/badge/VHDL-c678dd?style=for-the-badge&logoColor=fff)
![RTL](https://img.shields.io/badge/RTL_Design-282c34?style=for-the-badge)
![FSM](https://img.shields.io/badge/FSM_&_Datapath-282c34?style=for-the-badge)

**FPGA Flow &amp; EDA**

![Quartus](https://img.shields.io/badge/Intel_Quartus_Prime-61afef?style=for-the-badge&logo=intel&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-282c34?style=for-the-badge)
![STA](https://img.shields.io/badge/Static_Timing_Analysis-282c34?style=for-the-badge)

</td><td width="50%" valign="top">

**Languages**

![C](https://img.shields.io/badge/C-e06c75?style=for-the-badge&logo=c&logoColor=fff)
![C++](https://img.shields.io/badge/C++-e06c75?style=for-the-badge&logo=cplusplus&logoColor=fff)
![Python](https://img.shields.io/badge/Python-98c379?style=for-the-badge&logo=python&logoColor=fff)
![MATLAB](https://img.shields.io/badge/MATLAB-e5c07b?style=for-the-badge)

**Embedded &amp; Interfaces**

![ARM](https://img.shields.io/badge/ARM_Cortex--M_/_A9-61afef?style=for-the-badge&logo=arm&logoColor=fff)
![CAN](https://img.shields.io/badge/CAN_2.0B-282c34?style=for-the-badge)
![AXI](https://img.shields.io/badge/AXI4--Lite-282c34?style=for-the-badge)
![SPI](https://img.shields.io/badge/SPI_/_I2C_/_UART_/_USB_CDC-282c34?style=for-the-badge)

</td></tr>
</table>

<br>

## `> ls -la ~/projects`

<table>
<tr><td width="55%" valign="top">

### 01 &nbsp;CAN Sensor Fusion Platform
`Verilog RTL` `AXI4-Lite` `Cyclone V SoC` `Cortex-A9 Linux`

A four-stage heterogeneous platform, built end to end. Custom
Verilog IP on the FPGA fabric with **no vendor cores and no soft
processor**: SPI master, a register-level MCP2515 driver written
from the datasheet, a CAN frame parser, a 1&nbsp;&micro;s hardware
timestamp unit and an 8-tap pipelined FIR.

Every block got its own self-checking testbench before integration.
Then I found the bug that only ever reproduced on silicon: the data
register was written a cycle ahead of the valid flag, so the CPU
could latch a half-updated word.

<a href="https://github.com/sanjusaravananx2-hub/Can-sensor-fusion"><img src="https://img.shields.io/badge/View_Code-c678dd?style=flat-square&logo=github&logoColor=fff"/></a>

</td><td width="45%" valign="top">

### 02 &nbsp;Predictive Thermal Protection
`STM32F411` `C` `MATLAB/Simulink` `MSc Thesis`

Replaces a reactive thermistor with a model that predicts IGBT
junction temperature on the MCU.

| | |
|---|---|
| Hazardous conditions caught | **47 / 47**, never late |
| Thermistor baseline | 21 / 47 |
| Inference | **284.7 &micro;s** @ 96 MHz |
| Processor load | **2.85 %** |
| Footprint | 7,868 B flash, 0 B RAM |

Evaluated int8 via CMSIS-NN and **rejected it**: 17 % faster, but
worst-case error went from 1.35 to 11.51 &deg;C. The benchmark
decided, not preference.

<a href="https://github.com/sanjusaravananx2-hub/AI-driven-Thermal-analysis-of-an-Ev-inverter-using-STM32"><img src="https://img.shields.io/badge/View_Code-61afef?style=flat-square&logo=github&logoColor=fff"/></a>

</td></tr>
<tr><td valign="top">

### 03 &nbsp;AR PCB Debugger &nbsp;🥇
`STM32F411` `USB CDC` `OpenCV` `ArUco`

Firmware streams live GPIO, ADC and timer state over USB at 30 Hz
while a Python host tracks the physical board by computer vision and
overlays pin state and waveforms onto it in real time.

Built solo in two days because the existing debug workflow was
tedious. **1st place, EGN Build-a-thon 2026.**

<a href="https://github.com/sanjusaravananx2-hub/ar-pcb-debugger"><img src="https://img.shields.io/badge/View_Code-98c379?style=flat-square&logo=github&logoColor=fff"/></a>

</td><td valign="top">

### 04 &nbsp;STM32 USB Signal Analyser
`STM32F411` `DMA` `FFT` `USB CDC`

A real-time USB oscilloscope and FFT analyser on a Black Pill.
Bare-metal C with DMA double-buffering feeding a streaming USB CDC
link, plotted by a Python host.

<a href="https://github.com/sanjusaravananx2-hub/stm32-usb-signal-analyser"><img src="https://img.shields.io/badge/View_Code-e5c07b?style=flat-square&logo=github&logoColor=fff"/></a>

</td></tr>
</table>

<br>

## `> git log --stat`

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=sanjusaravananx2-hub&show_icons=true&hide_border=true&bg_color=0d1117&title_color=c678dd&icon_color=98c379&text_color=c9d1d9&include_all_commits=true" alt="GitHub stats"/>
  <img width="41%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanjusaravananx2-hub&layout=compact&hide_border=true&bg_color=0d1117&title_color=c678dd&text_color=c9d1d9&langs_count=8" alt="Top languages"/>
</p>

<br>

## `> tail ~/.education`

**MSc Embedded Systems Engineering** &nbsp;&middot;&nbsp; University of Leeds &nbsp;&middot;&nbsp; 2025 to 2026 &nbsp;&middot;&nbsp; *Predicted Distinction*
<br><sub>Hardware/Software Co-Design &middot; Real-Time Systems &middot; Digital Signal Processing &middot; Advanced Control &middot; Course Representative</sub>

**BEng Electronics &amp; Communication Engineering** &nbsp;&middot;&nbsp; Sathyabama Institute of Science &amp; Technology &nbsp;&middot;&nbsp; *First Class with Distinction*

**Published** &nbsp;&middot;&nbsp; *Multi-Object Trajectory Prediction for Moving Object Localisation* &nbsp;&middot;&nbsp; *Enhanced Fish Freshness Detection Using Image Processing Techniques*

<br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>
</p>
