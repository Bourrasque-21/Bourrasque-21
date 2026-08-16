<h1 align="center">Bourrasque-21</h1>

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

<p>
  <img src="https://img.shields.io/badge/SystemVerilog-5C2D91?style=flat-square" alt="SystemVerilog" />
  <img src="https://img.shields.io/badge/Verilog-2F74C0?style=flat-square" alt="Verilog" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white" alt="RISC-V" />
  <img src="https://img.shields.io/badge/UVM-6A5ACD?style=flat-square" alt="UVM" />
  <img src="https://img.shields.io/badge/FPGA-E34F26?style=flat-square" alt="FPGA" />
  <img src="https://img.shields.io/badge/Xilinx%20Vivado-E01F27?style=flat-square" alt="Xilinx Vivado" />
</p>

## Featured Projects

### [AES-256-GCM & Rolling-Shutter OCC](https://github.com/Bourrasque-21/aes256-gcm-occ)

AES-256-GCM 암호화 코어와 Rolling-Shutter OCC 광통신을 결합해 보안 영상 스트림을 구현한 FPGA 프로젝트입니다.

- SystemVerilog · Vivado · Basys 3 · OV7670 · AXI4-Stream
- 128비트 AXI4-Stream 기반 [AES-256-GCM Block-Parallel Core](https://github.com/Bourrasque-21/aes256-gcm-occ/tree/main/AES256_GCM_Core) 설계
- AES와 GHASH의 중첩 실행 및 NIST AES-256 KAT 405개 통과
- Basys 3 두 대와 OV7670을 활용한 [Rolling-Shutter OCC 송수신기](https://github.com/Bourrasque-21/aes256-gcm-occ/tree/main/Rolling_Shutter_OCC) 구현
- OOK·Manchester 광통신과 자격증명·CRC 검증 적용

### [VGA Air Drawing](https://github.com/Bourrasque-21/VGA_AIR_DRAWING)

OV7670 카메라로 초록색 마커를 추적하고, 허공에 그린 궤적을 FPGA에서 실시간 합성하는 시스템입니다.

- SystemVerilog · Python · Vivado · UVM
- Basys 3 FPGA, OV7670 카메라, VGA 및 UART 연동
- 64라인 링버퍼 구조로 영상 메모리를 줄이고 640×480 화면 구현
- FPGA 영상처리와 Python UI를 결합한 하드웨어·소프트웨어 통합 프로젝트

### [RISC-V RV32I MCU](https://github.com/Bourrasque-21/RV32I_mcu)

싱글사이클 RV32I CPU 설계를 기반으로 멀티사이클 구조까지 확장하고, 메모리와 APB 주변장치를 하나의 MCU 형태로 통합한 프로젝트입니다.

- 싱글사이클 RV32I CPU 설계 및 멀티사이클 구조 확장
- IF · ID · EX · MEM · WB 단계 기반 제어
- 4 KB 데이터 RAM과 메모리 맵 설계
- APB 기반 GPIO, UART, FND 주변장치
- Basys 3 보드에서 동작하도록 설계한 SystemVerilog SoC

### [Driver Monitoring System](https://github.com/Bourrasque-21/driver_monitoring_system)

운전자 눈 상태와 눈 위치를 분석하기 위한 머신러닝 모델 실험 및 배포 파이프라인입니다.

- MobileNetV3 및 YOLOv8 분류 모델 비교
- 회전 증강 기반 미세조정과 눈 위치 탐지
- ONNX 모델 변환 및 TensorRT 벤치마크

## Project Index

| Project | Description |
| --- | --- |
| [VGA Air Drawing](https://github.com/Bourrasque-21/VGA_AIR_DRAWING) | FPGA 기반 실시간 영상처리 및 에어 드로잉 시스템 |
| [AES-256-GCM Core](https://github.com/Bourrasque-21/aes256-gcm-occ/tree/main/AES256_GCM_Core) | 128비트 AXI4-Stream 기반 AES-256-GCM TX/RX RTL 및 NIST KAT 검증 |
| [Rolling-Shutter OCC v3](https://github.com/Bourrasque-21/aes256-gcm-occ/tree/main/Rolling_Shutter_OCC) | Basys3·OV7670 기반 OOK/Manchester 광통신 송수신 설계 |
| [RISC-V RV32I MCU](https://github.com/Bourrasque-21/RV32I_mcu) | 싱글사이클·멀티사이클 RV32I 기반 MCU/SoC 설계 |
| [Driver Monitoring System](https://github.com/Bourrasque-21/driver_monitoring_system) | 눈 상태·위치 분석 머신러닝 및 배포 파이프라인 |
| [Piano to Score](https://github.com/Bourrasque-21/piano_to_score) | 피아노 오디오 자동 악보화 연구 아카이브 |
| [AES128 SoC System](https://github.com/Bourrasque-21/AES128-soc-system) | AES-128 SoC 설계 |
| [RV32I Single-Cycle](https://github.com/Bourrasque-21/RV32I_mcu/tree/main/single_cycle) | 싱글사이클 RV32I CPU RTL 설계 |
| [I2C](https://github.com/Bourrasque-21/I2C) | I2C 통신 컨트롤러 설계 및 검증 |
| [SPI](https://github.com/Bourrasque-21/SPI) | SPI 통신 컨트롤러 설계 및 검증 |
| [UART](https://github.com/Bourrasque-21/UART) | UART 송수신 모듈 설계 및 검증 |
| [RAM](https://github.com/Bourrasque-21/RAM) | RAM 설계 및 검증 |
| [Digital System](https://github.com/Bourrasque-21/DIGITAL_SYS) | Stopwatch/Clock, SR04, DHT11, 7-Segment를 통합한 멀티모드 센서 시스템 및 UART ASCII 명령 기반 PC 제어·Watchdog Timer 구현 |

<p align="center">
  <a href="https://github.com/Bourrasque-21?tab=repositories">View all repositories →</a>
</p>

