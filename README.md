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

### [Piano to Score](https://github.com/Bourrasque-21/piano_to_score)

피아노 오디오를 MIDI와 MusicXML 악보로 변환하기 위해 전사, 박자 분석, 리듬 양자화 및 성부 분리를 실험한 연구 아카이브입니다.

- 오디오 전사부터 악보 출력까지의 전체 파이프라인 설계
- 규칙 기반 양자화와 Bi-LSTM 리듬 모델 비교
- 실험 결과와 한계, 중단 이유까지 기록한 프로젝트

## RTL & Verification Projects

| Project | Description |
| --- | --- |
| [AES128 SoC System](https://github.com/Bourrasque-21/AES128-soc-system) | AES-128 기반 SoC 설계 프로젝트 |
| [RISC-V](https://github.com/Bourrasque-21/RISC-V) | 싱글사이클 RV32I CPU RTL 설계 |
| [I2C](https://github.com/Bourrasque-21/I2C) | I2C 통신 컨트롤러 설계 및 검증 |
| [SPI](https://github.com/Bourrasque-21/SPI) | SPI 통신 컨트롤러 설계 및 검증 |
| [UART](https://github.com/Bourrasque-21/UART) | UART 송수신 모듈 설계 및 검증 |
| [RAM](https://github.com/Bourrasque-21/RAM) | RAM 설계 및 검증 |
| [Digital System](https://github.com/Bourrasque-21/DIGITAL_SYS) | Verilog 기반 디지털 시스템 설계 |

<p align="center">
  <a href="https://github.com/Bourrasque-21?tab=repositories">View all repositories →</a>
</p>
