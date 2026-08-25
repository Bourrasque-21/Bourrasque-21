<h1 align="center">하지훈 | Ha Ji Hoon</h1>

<p align="center">
  FPGA · Digital Logic · Embedded System
</p>

<p align="center">
  SystemVerilog 기반 RTL 설계·검증 · RISC-V SoC · FPGA 영상처리 프로젝트
</p>

## About Me

- SystemVerilog 기반의 RTL 설계 및 UVM 검증
- RISC-V CPU, APB 버스 및 주변장치를 포함한 SoC 구현
- FPGA 기반 실시간 영상처리와 하드웨어·소프트웨어 통합
- Python을 활용한 디바이스 UI와 머신러닝 실험

## Tech Stack

**HDL / Programming**

<p>
  <img src="https://img.shields.io/badge/Verilog-2F74C0?style=flat-square" alt="Verilog" />
  <img src="https://img.shields.io/badge/SystemVerilog-5C2D91?style=flat-square" alt="SystemVerilog" />
  <img src="https://img.shields.io/badge/VHDL-A9157E?style=flat-square" alt="VHDL" />
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
</p>

**Design / Implementation**

<p>
  <img src="https://img.shields.io/badge/Vivado-E01F27?style=flat-square" alt="Vivado" />
  <img src="https://img.shields.io/badge/Vitis%20IDE-ED1C24?style=flat-square" alt="Vitis IDE" />
  <img src="https://img.shields.io/badge/PSpice-CC0000?style=flat-square" alt="PSpice" />
  <img src="https://img.shields.io/badge/Cadence%20Virtuoso-8B0000?style=flat-square" alt="Cadence Virtuoso" />
</p>

**Verification**

<p>
  <img src="https://img.shields.io/badge/UVM-6A5ACD?style=flat-square" alt="UVM" />
  <img src="https://img.shields.io/badge/Synopsys%20VCS-7B1FA2?style=flat-square" alt="Synopsys VCS" />
  <img src="https://img.shields.io/badge/Verdi-00897B?style=flat-square" alt="Verdi" />
</p>

## Featured Projects

### [FPGA AES-256-GCM Security System](https://github.com/Rheinluft/AES256-GCM-Security-System)

Rolling-Shutter OCC 자격증명 전달부터 FPGA 영상 암호화, Jetson 중간 공격, 수신 인증 및 차단까지 통합한 팀 프로젝트입니다.

- SystemVerilog · C · Python · Vivado · Vitis IDE
- Zybo Z7-20, NVIDIA Jetson Orin Nano, Pcam 5C, Basys 3 및 OV7670 활용
- Zybo TX/RX의 AES-256-GCM 영상 암복호화와 Jetson 기반 공격·관찰 환경 통합
- [AES-256-GCM Core](https://github.com/Bourrasque-21/aes256-gcm-occ/tree/main/AES256_GCM_Core)의 TX/RX RTL 설계
- AES와 GHASH의 중첩 실행 및 NIST AES-256 KAT 405개 통과
- [Rolling-Shutter OCC 송수신기](https://github.com/Bourrasque-21/aes256-gcm-occ/tree/main/Rolling_Shutter_OCC)의 OOK·Manchester 광통신 및 자격증명·CRC 검증

### [VGA Air Drawing](https://github.com/Bourrasque-21/VGA_AIR_DRAWING)

OV7670 카메라로 초록색 마커를 추적하고, 허공에 그린 궤적을 FPGA에서 실시간 합성하는 시스템입니다.

- SystemVerilog · Python · Vivado · UVM
- Basys 3 FPGA, OV7670 카메라, VGA 및 UART 연동
- 64라인 링버퍼 구조로 영상 메모리를 줄이고 640×480 화면 구현
- FPGA 영상처리와 Python UI를 결합한 하드웨어·소프트웨어 통합 프로젝트

### [RISC-V RV32I MCU](https://github.com/Bourrasque-21/RV32I_mcu)

RV32I Multi-cycle CPU와 APB Master를 설계하고, GPIO·UART·FND Peripheral을 MMIO 방식으로 구성한 MCU/SoC 프로젝트입니다.

- RV32I Multi-cycle CPU 및 APB Master 설계
- IF · ID · EX · MEM · WB 단계 기반 제어
- 4 KB 데이터 RAM과 메모리 맵 설계
- MMIO 방식의 GPIO, UART, FND Peripheral 구성
- Basys 3 보드에서 동작하도록 설계한 SystemVerilog SoC

### [Driver Monitoring System](https://github.com/Bourrasque-21/driver_monitoring_system)

운전자의 눈 위치와 눈 상태를 분석하기 위한 비전 모델을 설계하고, 하이퍼파라미터 최적화를 통해 최종 모델을 선정한 프로젝트입니다.

- YOLOv8n 기반 눈 위치 탐지 모델 설계
- MobileNetV3 및 YOLOv8n-cls 기반 눈 상태 분류 후보 모델 설계
- TPE 베이지안 최적화 알고리즘을 활용한 하이퍼파라미터 탐색 및 최적 비전 모델 선정

## Project Index

| Project | Description |
| --- | --- |
| [FPGA AES-256-GCM Security System](https://github.com/Rheinluft/AES256-GCM-Security-System) | OCC 자격증명, FPGA 영상 암호화, Jetson 공격 및 RX 인증·차단을 통합한 팀 프로젝트 |
| [VGA Air Drawing](https://github.com/Bourrasque-21/VGA_AIR_DRAWING) | FPGA 기반 실시간 영상처리 및 에어 드로잉 시스템 |
| [AES-256-GCM Core](https://github.com/Bourrasque-21/aes256-gcm-occ/tree/main/AES256_GCM_Core) | AES-256-GCM TX/RX RTL 설계 및 NIST KAT 검증 |
| [Rolling-Shutter OCC](https://github.com/Bourrasque-21/aes256-gcm-occ/tree/main/Rolling_Shutter_OCC) | Basys3·OV7670 기반 OOK/Manchester 광통신 송수신 설계 |
| [RISC-V RV32I MCU](https://github.com/Bourrasque-21/RV32I_mcu) | RV32I Multi-cycle CPU와 APB Master 설계, MMIO 방식 Peripheral 구성 |
| [Driver Monitoring System](https://github.com/Bourrasque-21/driver_monitoring_system) | YOLOv8n 눈 위치 탐지 및 TPE 기반 눈 상태 분류 모델 최적화 |
| [Piano to Score](https://github.com/Bourrasque-21/piano_to_score) | 피아노 오디오 자동 악보화 연구 아카이브 |
| [AES128 SoC System](https://github.com/Bourrasque-21/AES128-soc-system) | AES-128 SoC 설계 |
| [RV32I Single-Cycle](https://github.com/Bourrasque-21/RV32I_mcu/tree/main/single_cycle) | 싱글사이클 RV32I CPU RTL 설계 |
| [I2C](https://github.com/Bourrasque-21/I2C) | AXI4-Lite 기반 I2C Master의 MicroBlaze SoC 통합, 보드 간 통신 구현 및 UVM 검증 |
| [SPI](https://github.com/Bourrasque-21/SPI) | AXI4-Lite 기반 SPI Master의 MicroBlaze SoC 통합, 보드 간 통신 구현 및 UVM 검증 |
| [UART](https://github.com/Bourrasque-21/UART) | UART 송수신 모듈 설계 및 검증 |
| [RAM](https://github.com/Bourrasque-21/RAM) | RAM 설계 및 검증 |
| [Digital System](https://github.com/Bourrasque-21/DIGITAL_SYS) | Stopwatch/Clock, SR04, DHT11, 7-Segment를 통합한 멀티모드 센서 시스템 및 UART ASCII 명령 기반 PC 제어·Watchdog Timer 구현 |

<p align="center">
  <a href="https://github.com/Bourrasque-21?tab=repositories">View all repositories →</a>
</p>

