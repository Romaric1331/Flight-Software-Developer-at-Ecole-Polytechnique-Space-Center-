
# 🛰️ IONSAT CubeSat Communication Bus Interface
<a href="https://archive.softwareheritage.org/swh:1:dir:691f227f0733ec7c0b1d911e117bea9834a23a4e;origin=https://github.com/Romaric1331/Flight-Software-Developer-at-Ecole-Polytechnique-Space-Center-;visit=swh:1:snp:b8ca5733a44ec299585409956c3125df1aa283e3;anchor=swh:1:rev:0ac3cd6ec9646ecfb5196246bb2552398d553c8d">
    <img src="https://archive.softwareheritage.org/badge/swh:1:dir:691f227f0733ec7c0b1d911e117bea9834a23a4e/" alt="Archived | swh:1:dir:691f227f0733ec7c0b1d911e117bea9834a23a4e"/>
</a>

Welcome to the IONSAT project, a collaborative effort by ONERA, CNES, ThrustMe, and École Polytechnique, focused on developing and maintaining a powered nanosatellite in a very low orbit. The project aims to leverage the advantages of low orbits, such as reduced communication latency, enhanced resolution, and cost-effective launches.

## 🌌 Mission Overview
The IONSAT satellite is designed to launch from the International Space Station (ISS) and utilize aerobreaking techniques to descend to an altitude of 300 km. This involves harnessing atmospheric drag by orienting the satellite's largest surface perpendicular to its trajectory.

Once at 300 km altitude, the station-keeping mission commences. The nanosatellite undergoes periodic descents to achieve a lower altitude of 10 km, marking a phased flight operation spanning a desired duration of six months, with potential extensions upon successful mission milestones.

###  CAN Communication with ADCS
Effective communication between systems is pivotal for the success of the IONSAT mission. In this initial stage, the MCP2515 CAN bus stand-alone module is deployed to facilitate seamless data exchange between systems via CANH and CAN L bus connectors. This setup ensures inter-system coordination without reliance on a host computer.

### I2C Communication with Thruster
To establish I2C communication, the STM32F429I Discovery board is utilized. Pinout connections include SCL and SDA pins between the emulator and microcontroller. Additionally, a logic analyzer is employed to debug if no data transfer occurs.
### Architecture of IonSat
Established a balanced architecutre and the Logiciel de Vol with different partitions and combinations of various structures from FPGA to program logic
### 🔗 Resources
1. [MCP2515 CAN Module Arduino Tutorial](https://lastminuteengineers.com/mcp2515-can-module-arduino-tutorial/)
2. [STM32 I2C Tutorial](https://deepbluembedded.com/stm32-i2c-tutorial-hal-examples-slave-dma/)

## 📁 Repository Structure
- **/CAN_Module_Code:** Contains the code for MCP2515 CAN Module integration.
- **/I2C:** Includes code and documentation for establishing I2C communication with the thruster using the STM32F429I Discovery board.
- **/Resources:** Supplementary materials, datasheets, and documentation related to the project.

