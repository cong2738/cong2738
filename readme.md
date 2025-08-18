# 박호윤 (Park HoYoun)

> 안녕하세요! 이론과 실습을 모두 겪은 손으로 설계하는 RISC-V 기반 시스템 개발자입니다.

# 🌟 About Me

🏫  강원대학교 전기전자공학과

🕍  서울기술교육센터 Harman Semicon Academy 수료

🏆 **강원대학교 IT대학 졸업작품 경진대회 우수상 수상**

📧  **Email** | cong2738@gmail.com

# 🛠️ HW Engineer

> 💡 저는  RTL Design / Verification에 분야에 열정을 가진 **HW 엔지니어** 박호윤 입니다!

- FPGA 기반 **멀티사이클 RV32I CPU 및 SoC 설계** 경험이 있습니다.
- **SPI, I2C, APB 버스** 등 다양한 통신 모듈을 RTL로 구현하고, **SystemVerilog**로 검증 환경을 구축한 경험이 있습니다.
- **Testbench 작성**, **파형 분석**, **단위/통합 검증**에 능숙하며, 구조적이고 반복 가능한 검증 시스템을 설계할 수 있습니다.
- **디지털 회로의 흐름과 제어 로직**을 깊이 있게 이해하고 있으며, **설계 → 시뮬레이션 → 개선**의 과정을 체계적으로 수행할 수 있습니다.
- 문제 해결 과정에서 **논리적 사고와 디버깅 역량**, 그리고 협업을 위한 **명확한 커뮤니케이션**에 강점을 가지고 있습니다.

---

# ✏️기술 STACK

## Verilog HDL

- **멀티사이클 RV32I CPU**를 직접 설계하여 컴퓨터 구조에 대한 높은 이해를 보유하고있습니다.
- APB(Advanced Peripheral Bus) 버스 설계를 다뤄본 경험을 통해 **CPU와 주변장치 간의 연결 프로토콜과 동작 방식**을 깊이 있게 이해하고 있습니다.
- **UART, SPI, I2C** 등 통신 모듈을 직접 구현하고, **기능 단위 테스트벤치**를 통해 명확히 검증했습니다.
- **통합 센서 시스템**에서 각 센서 모듈을 Verilog로 구현하고 상호 연동을 위한 구조적 설계를 수행했습니다.
- **FSM 기반 제어 설계**, **모듈화**, **시뮬레이션 파형 해석 능력**에 강점을 가지고 있습니다.

## System Verilog & UVM

- **SystemVerilog**로 복잡한 테스트벤치 환경을 구축하고, 다양한 명령어/모듈의 검증을 수행한 경험이 있습니다.
- **RISC-V APB 시스템**, **SPI/I2C 모듈**, **영상처리 시스템**에 대한 테스트 환경을 직접 작성하였습니다.
- **I2C 통신 모듈**을 대상으로 **UVM**(Universal Verification Methodology)을 적용하여, **단위 모듈 및 시스템 통합 수준의 검증 흐름 구성** 경험이 있습니다.

## Embedded

- STM32 (Cortex-M4)를 활용한 시스템 제어 경험이 있으며, 센서 제어, UART/I2C/SPI 통신 구현 등을 직접 개발했습니다.
- 임베디드 시스템에 **RTOS**를 사용하여 **멀티스레딩 환경에서의 시스템 설계와 디자인패턴 적용**한 경험이 있습니다.
- 하드웨어 설계 외에도 **Python을 활용한 API 기반 어플리케이션 개발** 경험이 있으며, **출퇴근 안내 보조 시스템**을 구현했습니다.
- 데이터시트 기반 시스템 설계 및 **로우레벨 통신 구현**에 익숙합니다.

## 영상처리 / 인터랙션 시스템

- 머신러닝 없이 **Verilog만으로 색상 추출 기반 마커 트래킹 시스템**을 구현했습니다.
- FPGA에 연결된 카메라 데이터를 처리하여 **청기백기 게임** 등 인터랙티브 시스템을 완성했습니다.
- RGB-HSV 색상 공간 처리, 마커 위치 추적, 속도 추정 등 **간단한 비전 로직을 HDL로 직접 구현**한 경험이 있습니다.

----

# 📑Project

- **[HandBand](https://github.com/cong2738/HandBand)** | `SystemVerilog` `verilog` `ISP` `C` `Python` `RTL` `Embedded` `Multithreading`
  - 영상처리 모션인식 무대장치 제어시스템

- **[FlagGame](https://github.com/cong2738/FlagGame)** | `SystemVerilog` `RTL`
  - 영상처리 마커 트래킹 알고리즘을 활용한 FlagGame RTL Design 
  
- **[RTOS-Winecellar](https://github.com/cong2738/wine_celler)** | `C` `Embedded` `RTOS` `ARM Coretex M`
  - RTOS 기반 와인셀러
  - RTOS를 활용하여 확장성과 동시입력,처리를 보장한다
  
- **[I2C/SPI Team Project](https://github.com/cong2738/May_team_project_I2C_SPI)** | `SystemVerilog` `C` `RTL` `UVM`
  - I2C, SPI 통신 RTL 설계/검증 with AMBA AXI
  - 통신 프로토콜을 직접  RTL설계하고 UVM검증한다

- **[SmartFarmSensorSystem](https://github.com/cong2738/SmartFarmSensorSystem)** | `SystemVerilog` `RTL` `C`
  - AMBA APB Interface my RISC-V을 활용한 스마트팜 센서 시스템
  - AMBA APB Interface를 직접 구현한다
  
- **[my_RISC-V](https://github.com/cong2738/my_RISC-V)** | `Verilog` `RTL` `C`
  - 멀티사이클 RISC-V CPU 설계
  - RISC-V를 직접 RTL설계하며 CPU구조와 동작에 대해 이해한다

- **[출근비서](https://github.com/cong2738/HarmanCA_project1)** | `Python` `API` 
  - Python AIP를 활용한출근비서 

- **[실시간 영상처리를 이용한 로봇 제어의 방법과 필요성](https://github.com/cong2738/Kangwon_university_senior_project)** | `Python` `Deeplearning` 
  - 머신러닝 영상처리를 활용한 로봇제어

- **[전체 레포지토리](https://github.com/cong2738?tab=repositories)**
---

