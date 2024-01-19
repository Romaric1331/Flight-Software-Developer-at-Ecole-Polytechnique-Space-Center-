<<<<<<< HEAD
## 🛰️ IONSAT CubeSat Communication Bus Interface
=======
# 🛰️ IONSAT CubeSat Communication Bus Interface
>>>>>>> 8ebc21c0c739f2226085d3a7b32279fc5c1c8f13

Welcome to the IONSAT project, a collaborative effort by ONERA, CNES, ThrustMe, and École Polytechnique, focused on developing and maintaining a powered nanosatellite in a very low orbit. The project aims to leverage the advantages of low orbits, such as reduced communication latency, enhanced resolution, and cost-effective launches.

## 🌌 Mission Overview
The IONSAT satellite is designed to launch from the International Space Station (ISS) and utilize aerobreaking techniques to descend to an altitude of 300 km. This involves harnessing atmospheric drag by orienting the satellite's largest surface perpendicular to its trajectory.

Once at 300 km altitude, the station-keeping mission commences. The nanosatellite undergoes periodic descents to achieve a lower altitude of 10 km, marking a phased flight operation spanning a desired duration of six months, with potential extensions upon successful mission milestones.

### 🚀 CAN Communication with ADCS
Effective communication between systems is pivotal for the success of the IONSAT mission. In this initial stage, the MCP2515 CAN bus stand-alone module is deployed to facilitate seamless data exchange between systems via CANH and CAN L bus connectors. This setup ensures inter-system coordination without reliance on a host computer.

#### I2C Communication with Thruster
To establish I2C communication, the STM32F429I Discovery board is utilized. Pinout connections include SCL and SDA pins between the emulator and microcontroller. Additionally, a logic analyzer is employed to debug if no data transfer occurs.

### 🔗 Resources
1. [MCP2515 CAN Module Arduino Tutorial](https://lastminuteengineers.com/mcp2515-can-module-arduino-tutorial/)
2. [STM32 I2C Tutorial](https://deepbluembedded.com/stm32-i2c-tutorial-hal-examples-slave-dma/)

## 📁 Repository Structure
- **/CAN_Module_Code:** Contains the code for MCP2515 CAN Module integration.
- **/I2C:** Includes code and documentation for establishing I2C communication with the thruster using the STM32F429I Discovery board.
- **/Resources:** Supplementary materials, datasheets, and documentation related to the project.

