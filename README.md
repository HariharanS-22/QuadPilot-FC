# 🚁 QuadPilot-FC – STM32F411-Based Flight Controller

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1qYn6Pgk2dRrZZ9FfdGF-8EtIsHSCfpHK" alt="Drone Icon" width="500"/>
</p>

**QuadPilot-FC** is a compact, custom-built quadcopter flight controller powered by the **STM32F411 Blackpill** board. It uses the **INAV configurator** for real-time flight tuning and control, with an integrated sensor suite for accurate stabilization and environmental awareness. Designed using a **zero PCB layout**, it offers a space-saving, minimalistic form factor—perfect for lightweight UAVs.



## 🛠️ Features

- ✅ STM32F411 Blackpill-based flight controller  
- ✅ INAV-compatible firmware & configuration  
- ✅ Sensor suite:
  - MPU6050 (Gyroscope + Accelerometer)  
  - ADXL345 (Precision Accelerometer)  
  - BM280 (Barometer)  
  - HMC5883 (Magnetometer)
- ✅ PID-based control loop  
- ✅ Space-efficient Zero PCB design  
- ✅ Lightweight hardware footprint  



## 🧩 Hardware

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1lZXwAWgJRk456jW6qQoy4LYiFgoMexCX" alt="Structure" width="500"/>
</p>

<table align="center">
  <thead>
    <tr>
      <th>Component</th>
      <th>Specification</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>MCU</td><td>STM32F411CEU6 (Blackpill)</td></tr>
    <tr><td>IMU</td><td>MPU6050 (Gyro + Accelerometer)</td></tr>
    <tr><td>Accelerometer</td><td>ADXL345 (3-axis, high precision)</td></tr>
    <tr><td>Barometer</td><td>BM280 (Altitude & pressure)</td></tr>
    <tr><td>Magnetometer</td><td>HMC5883 (Compass)</td></tr>
    <tr><td>ESCs</td><td>30A ESCs (INAV compatible)</td></tr>
    <tr><td>Motors</td><td>1000kV Brushless Motors</td></tr>
    <tr><td>Battery</td><td>3S/4S LiPo</td></tr>
    <tr><td>Frame</td><td>F450 Quadcopter Frame</td></tr>
    <tr><td>Receiver</td><td>FlySky i6 (PPM Signal)</td></tr>
  </tbody>
</table>


## 🧾 Zero PCB Layout

<p align="center">
  <img src="images/flight_controller_layout.png" width="600"/>
  <br>
  <i>Custom Zero PCB layout integrating STM32F411 and all sensors</i>
</p>



## ⚡ Circuitary

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

This project is licensed under the MIT License. See the [`LICENSE`](./LICENSE) file for details.
