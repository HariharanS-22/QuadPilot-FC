# 🚁 QuadPilot-FC – STM32F411-Based Flight Controller

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1qYn6Pgk2dRrZZ9FfdGF-8EtIsHSCfpHK" alt="QuadPilot FC" width="600"/>
</p>

**QuadPilot-FC** is a custom-built, INAV-compatible flight controller designed for quadcopters using the powerful **STM32F411 Blackpill** board. Engineered with a **zero PCB layout**, it features a modular sensor suite and streamlined integration—ideal for compact, agile aerial platforms.


## 📸 Overview

- **Flight Stack**: INAV firmware for GPS-aware stabilization  
- **Controller**: STM32F411 (Blackpill) with F4 core  
- **Sensor Suite**: MPU6050, ADXL345, BM280, HMC5883  
- **Control Loop**: PID-based real-time flight control  
- **Connectivity**: FlySky i6 RC (PPM input)  
- **Design**: Hand-wired zero-PCB layout with space efficiency  


## 👥 Team & Contributors

Meet the minds behind **QuadPilot-FC** – open-source drone enthusiasts crafting embedded UAV solutions:

- 🛠️ [**Akash Rajan**](https://github.com/Akashrajan10) 
- 🌐 [**Hariharan**](https://github.com/HariharanS-22)  

## 🔧 Hardware

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1lZXwAWgJRk456jW6qQoy4LYiFgoMexCX" alt="QuadPilot Hardware Layout" width="535"/>
</p>

<div align="center">

<table>
  <tr>
    <th>Component</th>
    <th>Purpose</th>
  </tr>
  <tr><td>STM32F411 Blackpill</td><td>Main flight controller (F4 core)</td></tr>
  <tr><td>MPU6050</td><td>Gyroscope + Accelerometer</td></tr>
  <tr><td>ADXL345</td><td>High-precision 3-axis accelerometer</td></tr>
  <tr><td>BM280</td><td>Barometric pressure & altitude</td></tr>
  <tr><td>HMC5883</td><td>3-axis magnetometer (compass)</td></tr>
  <tr><td>30A ESCs</td><td>Motor speed control</td></tr>
  <tr><td>1000kV BLDC Motors</td><td>Quadcopter propulsion</td></tr>
  <tr><td>3S/4S LiPo Battery</td><td>Primary power source</td></tr>
  <tr><td>F450 Frame</td><td>Lightweight quadcopter frame</td></tr>
  <tr><td>FlySky i6</td><td>PPM RC signal input</td></tr>
</table>

</div>


## 🧠 Features

- **INAV-Compatible Flight Control**  
  Supports all core INAV features like GPS, barometer-based altitude hold, horizon leveling, and more.

- **Zero PCB Integration**  
  Entire flight controller assembled without a custom PCB—space optimized and hand-wired.

- **Full Sensor Suite**  
  Multi-sensor fusion improves stability and orientation accuracy during aggressive flight.

- **PPM Receiver Input**  
  Clean signal input using FlySky i6 in PPM mode for minimal wiring and robust control.


## 🧪 Circuit & Layout

### 🔌 Wiring Layout
<p align="center">
  <img src="images/flight_controller_layout.png" width="600"/>
  <br>
  <i>Zero PCB layout with STM32F411 and sensor suite</i>
</p>

### 🔧 Circuit Diagram
<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1adNxw3GfxY16109bKmsbfa1pXdPlGDL7" alt="Circuit Diagram" width="400"/>
</p>



## 📚 Documentation

- [INAV Configurator](https://github.com/iNavFlight/inav-configurator)  
- [STM32F411 Datasheet](https://www.st.com/resource/en/datasheet/stm32f411ce.pdf)  
- [MPU6050 Register Map](https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Register-Map1.pdf)  
- [ADXL345 Datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/adxl345.pdf)  
- [BM280 Datasheet](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bme280-ds002.pdf)  
- [HMC5883 Datasheet](https://cdn.sparkfun.com/datasheets/Sensors/Magneto/HMC5883L.pdf)  



## ⚖️ License

This project is open-source under the MIT License. See [`LICENSE`](./LICENSE) for full terms.
